Role Name
=========

Installs PowerDNS https://www.powerdns.com/ (MySQL cluster ready)

Requirements
------------

Any pre-requisites that may not be covered by Ansible itself or the role should be mentioned here. For instance, if the role uses the EC2 module, it may be a good idea to mention in this section that the boto package is required.

Role Variables
--------------

````
allow_ddns_updates: false  #define here or globally in group_vars/group
allow_ddns_updates_from: 0.0.0.0/0  #defines subnet to allow DDNS updates from if allowed...define here or globally in group_vars/group
config_logstash: false  #defines if logstash should be configured if installed...define here or globally in group_vars/group
dns_hostmaster: 'hostmaster.{{ pri_domain_name }}'  define here or globally in group_vars/group
enable_pdns_anycast: false  #define here or globally in group_vars/group
enable_pdns_recursive_lookups: true  #define here or globally in group_vars/group
enable_pdns_server_logging: false  #define here or globally in group_vars/group
enable_pdns_web_server: false  #define here or globally in group_vars/group
install_logstash: false  #defines if logstash should be installed and configured for DNS logging..define here or globally in group_vars/group
install_pdns_recursor: true   #defines if recursive caching server is to be installed
install_pdns_server: true  #defines if authoriative dns server is to be installed
install_poweradmin: false  #use NSEDIT instead
pdns_api_key: changeme  #define here or globally in group_vars/group
pdns_api_url: http://127.0.0.1:8081/servers/localhost/zones
pdns_create_fwd_zones: ''  #defined in group_vars/ip-services
#  - '_msdcs.{{ pri_domain_name }}'
#  - '_sites.{{ pri_domain_name }}'
#  - '_tcp.{{ pri_domain_name }}'
#  - '_udp.{{ pri_domain_name }}'
#  - '{{ pri_domain_name }}'
pdns_create_rev_zones: ''  #defined in group_vars/ip-services
#  - 0.0.10
#  - 101.0.10
pdns_create_zones: false  # set to false if you do not want to create zones... defined in group_vars/ip-services
pdns_curl_header: "-H 'X-API-Key: {{ pdns_api_key }}'"
pdns_db_cluster: false  #defines if backend db for pdns is clustered...define here or in group_vars/group
pdns_db_host: localhost
pdns_db_name: powerdns  #define here or globally in group_vars/group
pdns_db_pass: powerdns  #define here or globally in group_vars/group
pdns_db_user: powerdns  #define here or globally in group_vars/group
pdns_default_soa_mail: 'hostmaster.{{ pri_domain_name }}' #define here or globally in group_vars/group
pdns_default_soa_name: '{{ ansible_hostname }}.{{ pri_domain_name }}' #define here or globally in group_vars/group
pdns_json_interface: true
pdns_recursor_host: 127.0.0.1  #should be 127.0.0.1 unless recursor is running on a separate host
pdns_recursor_port: 5300  #port pdns_recursor should listen on...default is 53 but needs to be changed to run both pdns services on same host
pdns_recursor_version: 3.7.3-1
pdns_server_version: 3.4.5-1
pdns_webserver_address: 0.0.0.0
pdns_webserver_allow: '0.0.0.0/0,::/0'
pdns_webserver_password: []  #define here or globally in group_vars/group
pdns_webserver_port: 8081
poweradmin_db_host: localhost  #define here or globally in group_vars/group
poweradmin_pass: admin  #define here or globally in group_vars/group
poweradmin_user: admin  #define here or globally in group_vars/group
poweradmin_ver: poweradmin-2.1.7
pri_dns: []  #defines primary dns server on network...define here or globally in group_vars/all
pri_domain_name: example.org  #define here or globally in group_vars/all
sec_dns: []  #defines secondary dns server on network...define here or globally in group_vars/all
web_root: /var/www/html
zone_types: native
````

Dependencies
------------

````
mrlesmithjr.mariadb-galera-cluster  #if clustering
mrlesmithjr.mariadb-mysql  #if not clustering
mrlesmithjr.apache2
mrlesmithjr.logstash  #if using logstash
````

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: mrlesmithjr.powerdns }

License
-------

BSD

Author Information
------------------

Larry Smith Jr.
- @mrlesmithjr
- http://everythingshouldbevirtual.com
- mrlesmithjr [at] gmail.com
