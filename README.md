Role Name
=========

Installs PowerDNS https://www.powerdns.com/ (MySQL cluster ready)

[![Build Status](https://travis-ci.org/mrlesmithjr/ansible-powerdns.svg)](https://travis-ci.org/mrlesmithjr/ansible-powerdns)

Requirements
------------

None

Role Variables
--------------

````
---
allow_ddns_updates: false  #define here or globally in group_vars/group
allow_ddns_updates_from: 0.0.0.0/0  #defines subnet to allow DDNS updates from if allowed...define here or globally in group_vars/group
config_logstash: false  #defines if logstash should be configured if installed...define here or globally in group_vars/group
create_pdns_records: false   #defines if dns records should be created/updated
dns_hostmaster: 'hostmaster.{{ pri_domain_name }}'  #define here or globally in group_vars/group
enable_pdns_anycast: false  #define here or globally in group_vars/group
enable_pdns_recursive_lookups: true  #define here or globally in group_vars/group
enable_pdns_server_logging: false  #define here or globally in group_vars/group
enable_pdns_web_server: false  #define here or globally in group_vars/group
install_logstash: false  #defines if logstash should be installed and configured for DNS logging..define here or globally in group_vars/group
install_pdns_recursor: true   #defines if recursive caching server is to be installed
install_pdns_server: true  #defines if authoriative dns server is to be installed
install_poweradmin: false  #use NSEDIT instead
pdns_api_key: changeme  #define here or globally in group_vars/all/accounts
pdns_api_url: http://127.0.0.1:8081/servers/localhost/zones
pdns_create_zones: false  # set to false if you do not want to create zones... defined in group_vars/ip-services
pdns_curl_header: "-H 'X-API-Key: {{ pdns_api_key }}'"
pdns_db_cluster: false  #defines if backend db for pdns is clustered...define here or in group_vars/group
pdns_db_host: localhost
pdns_db_name: powerdns  #define here or globally in group_vars/group
pdns_db_pass: powerdns  #define here or globally in group_vars/all/accounts
pdns_db_user: powerdns  #define here or globally in group_vars/all/accounts
pdns_default_soa_mail: 'hostmaster.{{ pri_domain_name }}' #define here or globally in group_vars/group
pdns_default_soa_name: '{{ ansible_hostname }}.{{ pri_domain_name }}' #define here or globally in group_vars/group
pdns_json_interface: true
pdns_records:  #define DNS records to create/update...to keep this file small...define in group_vars/all/pdns_records.yml or other...
  - name: vcsa
    zone: '{{ pri_domain_name }}'
    type: A
    changetype: REPLACE
    content: 10.0.101.40
    disabled: false
    ttl: 3600
    priority: 0
  - name: logstash
    zone: '{{ pri_domain_name }}'
    type: A
    changetype: REPLACE
    content: 10.0.101.60
    disabled: false
    ttl: 3600
    priority: 0
  - name: dns
    zone: '{{ pri_domain_name }}'
    type: A
    changetype: REPLACE
    content: 192.168.70.241
    disabled: false
    ttl: 3600
    priority: 0
  - name: ntp1
    zone: '{{ pri_domain_name }}'
    type: CNAME
    changetype: REPLACE
    content: 'dns.{{ pri_domain_name }}'
    disabled: false
    ttl: 3600
    priority: 0
pdns_recursive_source_ip: false  #defines if source IP address should be defined for recursive queries...default is 0.0.0.0
pdns_recursor_host: 127.0.0.1  #should be 127.0.0.1 unless recursor is running on a separate host
pdns_recursor_port: 5300  #port pdns_recursor should listen on...default is 53 but needs to be changed to run both pdns services on same host
pdns_recursor_version: 3.7.3-1
pdns_server_version: 3.4.6-1
pdns_webserver_address: 0.0.0.0
pdns_webserver_allow: '0.0.0.0/0,::/0'
pdns_webserver_password: []  #define here or globally in group_vars/all/accounts
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
