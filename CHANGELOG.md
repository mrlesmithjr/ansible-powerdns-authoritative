commit 07b5480bff42bd7e9e01c5a7eb7f7cc79f6d147d
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Thu Apr 9 15:09:05 2020 -0400

    Rolling back version until further review
    
    4.3 fails to start service. Need to review this and figure out what is going on

commit 8cd4624b1fcad76cf2bf01b7abaa508e93d18041
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Thu Apr 9 15:08:26 2020 -0400

    Fixing Ansible notification for priority being an int

commit eef9a435e3ad564fdba7fc9764df62b7f9f237c5
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Thu Apr 9 14:28:52 2020 -0400

    Exposed ports and updated version

commit 08b2e78ca0d0cac696c0f0f0f2f7c9b96e1269d8
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Thu Apr 9 11:51:20 2020 -0400

    Removed lingering force check
    
    Not sure where this ever came into play but it needed to go

commit 60f2f4a4d31e292584b2ee3e84e72b3cb32f6bf2
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Thu Apr 9 11:23:59 2020 -0400

    Refactored code structure
    
    So much more that needs to be cleaned up with this role

commit 8cec6d3386ac02e72c52b824963086d1ed003923
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Thu Apr 9 11:23:59 2020 -0400

    Refactored code structure
    
    So much more that needs to be cleaned up with this role

commit 2a5c7d4e7124618c01c97451ddc4b677b69c48a7
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Thu Apr 9 09:50:49 2020 -0400

    Disabled Debian 9/10 testing
    
    Issues with importing DB schema and adding package for Debian 10

commit 0c66e96be966e26afe72abf0c0cf703fc4602f6f
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Thu Apr 9 09:34:36 2020 -0400

    Cleaned up code formatting a bit

commit da43a0cc0a9808f3fde8e3e98e94e3191db83dc4
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Thu Apr 9 09:33:52 2020 -0400

    Fixed linting issues

commit c039a7d98c440160ce247ab551d46e41ce6ba274
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Thu Apr 9 09:32:48 2020 -0400

    Tweaked Molecule testing
    
    Added MySQL role req. and disabled Fedora testing for now

commit 82f9292a59899b38c858c8a05851691956264276
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Thu Apr 9 01:42:27 2020 -0400

    Added: New files, etc. from cookiecutter template

commit 642c118376f7b13dd51fae945293e63868642aa7
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Thu Apr 9 01:42:05 2020 -0400

    Updated files, etc. after new structure
    
    This aligns to cookiecutter template

commit 4c717a6a2f204a657dbc63c731d09138c8d255e2
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Thu Apr 9 01:37:55 2020 -0400

    Deleted old tests, etc. not needed
    
    These files are no longer required for new format

commit 4adb28e9acffcd1afe81afd660cd8c812b9f5bde
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Wed Dec 19 00:44:28 2018 -0500

    Updated repo info and added Travis build status

commit e9bf5550c86d8b0d83f2de36529dd9867a26c956
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Wed Dec 19 00:37:51 2018 -0500

    Create LICENSE

commit b3ec2f76131e0b5f7179f4c322d3825689b78e57
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Wed Dec 19 00:24:42 2018 -0500

    Resolving updated ansible lint issues

commit ea9ea6897e6edc948da51189db5793875d7f2e66
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Sun Dec 16 10:14:36 2018 -0500

    Disabled Trusty and Debian Jessie for now

commit 3a484b1a122599819f5813df15b74061e9d4549c
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Sun Dec 16 10:04:18 2018 -0500

    Fixing Debian mysql service pre-req

commit 7943e478547837e28597f6c9cd510212a94035b8
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Sun Dec 16 09:54:01 2018 -0500

    Fixing issues with Travis pre-reqs

commit e0ad0c7862b2a5487ff07062771890e0d7dc3d1c
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Sun Dec 16 09:43:57 2018 -0500

    Installing pre-reqs for testing

commit 1eccf9e368ed5ffcfb9d6f1c854af3b11e735641
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Sun Dec 16 09:24:57 2018 -0500

    Added MySQL pre-req for testing

commit eaa845e4bda99125b9df75b06233da9187f1d9fa
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Sun Dec 16 09:16:29 2018 -0500

    First attempt at complete refactor

commit 73d35d0b4f4a1bc9bb0ea42dd23e34db05259ef1
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Fri Sep 22 15:36:34 2017 -0400

    Updated default vars
    
    Signed-off-by: Larry Smith Jr <mrlesmithjr@gmail.com>

commit 4d4f76247e5f5f3321364604ea29d35066b82e0e
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Thu May 18 18:49:09 2017 -0400

    Added support for Raspberry PI #8
    
    Signed-off-by: Larry Smith Jr <mrlesmithjr@gmail.com>

commit 473765843aebae062fc2486425ec761752b8b380
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Thu May 18 13:25:25 2017 -0400

    Cleaned up code/vars and changed to 4.x version
    
    Signed-off-by: Larry Smith Jr <mrlesmithjr@gmail.com>

commit a000eca83b432805ad8930ef48fc73d55a7461ce
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Fri Feb 24 23:10:45 2017 -0500

    Cleaned up vars
    
    Signed-off-by: Larry Smith Jr <mrlesmithjr@gmail.com>

commit 479f9efbda2ecb2eec42f32965195f85aeb65469
Author: James Farr <james@nertwork.com>
Date:   Sun Feb 19 19:41:09 2017 -0800

    Adding in the ability to opt-out of PTRS and the abilitiy to add multi-line records, like MX records. Also adding in the ability to have a "default" name for the record of the main host

commit b0f9fb83caadd85f09ebfdf1992db20158f8eb92
Author: Ewoud Kohl van Wijngaarden <ewoud@kohlvanwijngaarden.nl>
Date:   Fri Dec 30 18:52:50 2016 +0100

    Correct the config for 4.x api-key

commit 1c09ae527e8dda18c13b98d8fdaa797823ec4b1a
Author: Ewoud Kohl van Wijngaarden <ewoud@kohlvanwijngaarden.nl>
Date:   Fri Dec 30 18:51:52 2016 +0100

    Remove unused file

commit 10206ce102e16282ffe440c36365989b6742fbcb
Author: Ewoud Kohl van Wijngaarden <ewoud@kohlvanwijngaarden.nl>
Date:   Wed Dec 28 14:12:21 2016 +0100

    Match the repository name to the actual content

commit eb7222d16b8defca2f0c5fd8ccf4ab60d37db31f
Author: Lewis Burgess <lewis.burgess@priceline.com>
Date:   Tue Nov 22 12:04:29 2016 -0500

    support using a local repo for powerdns packages/gpgkey

commit 6c84d1f25209faf61dd347a774dbf69e051506f4
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Fri Oct 21 09:40:47 2016 -0400

    Addresses issue #2
    
    Signed-off-by: Larry Smith Jr <mrlesmithjr@gmail.com>

commit 38298244b0a0838edd8f40ae7bd9ef7f93f3e2b7
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Fri Oct 21 01:42:30 2016 -0400

    Added carbon output functionality in regards to issue #1
    
    Signed-off-by: Larry Smith Jr <mrlesmithjr@gmail.com>

commit 7328eae306c91d3bb3855f64507f74878cb22d22
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Tue Oct 18 00:37:28 2016 -0400

    Updated changes
    
    Signed-off-by: Larry Smith Jr <mrlesmithjr@gmail.com>

commit d6f1c16fcba2e8fc950b941f239ebf72dcad6323
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Wed Oct 12 15:33:49 2016 -0400

    Fixed issues with installing 4.x
    
    Signed-off-by: Larry Smith Jr <mrlesmithjr@gmail.com>

commit 923f06d80ab9c2163f1c5f757f0b50f67dd2ac69
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Tue Oct 11 14:18:45 2016 -0400

    Added new existing DB import check method...
    Instead of checking for a file to exist if import has
    occured. We now actually query the DB and look for the
    existence of a table and make our decision based on that
    
    Signed-off-by: Larry Smith Jr <mrlesmithjr@gmail.com>

commit b486fca44fc3ebbea4150c21d790a27a87c5f3d3
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Tue Oct 11 12:05:41 2016 -0400

    Added ability to define PDNS DB host access
    
    Signed-off-by: Larry Smith Jr <mrlesmithjr@gmail.com>

commit 43306e362e672823e0f39836471c67f3a6b4cd4a
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Tue Oct 11 08:47:55 2016 -0400

    Fixed conditionals for reconfigurations
    
    Signed-off-by: Larry Smith Jr <mrlesmithjr@gmail.com>

commit 1b381cd224c04e2dbf2006494e652b33948a493b
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Tue Oct 11 08:45:44 2016 -0400

    Cleaned up task names
    
    Signed-off-by: Larry Smith Jr <mrlesmithjr@gmail.com>

commit 74024e707261da608eead5d125e80a3b540eb68e
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Mon Oct 10 16:06:08 2016 -0400

    Updated Repo info
    
    Signed-off-by: Larry Smith Jr <mrlesmithjr@gmail.com>

commit 7ef92cd44705323b31a38dd31ff5752653e8e487
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Mon Oct 10 15:56:12 2016 -0400

    Added support of PDNS 4.x
    
    Signed-off-by: Larry Smith Jr <mrlesmithjr@gmail.com>

commit 05b9718d7596763341c3876098899c50433d4930
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Wed Oct 5 21:13:49 2016 -0400

    Updated changes
    
    Signed-off-by: Larry Smith Jr <mrlesmithjr@gmail.com>

commit b267793932b661cf0be7184d76c90dfeb6d977ef
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Wed Oct 5 20:04:54 2016 -0400

    Updated changes
    
    Signed-off-by: Larry Smith Jr <mrlesmithjr@gmail.com>

commit 03fef37e06108ea1aceb81098aec0dd4263f0587
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Wed Oct 5 20:03:17 2016 -0400

    Updated to version 3.4.10
    
    Signed-off-by: Larry Smith Jr <mrlesmithjr@gmail.com>

commit 19d968fad9f542693480366f64680e2fdb30c2d3
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Wed Oct 5 20:02:10 2016 -0400

    Updated to version 3.4.9
    
    Signed-off-by: Larry Smith Jr <mrlesmithjr@gmail.com>

commit 1b25fb95ef8a31fcda8720c27132f0aca09bcbb6
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Wed Oct 5 20:01:08 2016 -0400

    Updated to version 3.4.8
    
    Signed-off-by: Larry Smith Jr <mrlesmithjr@gmail.com>

commit 83857eccfc7ae7e4ba245d04f7cc439b56059990
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Wed Oct 5 19:59:14 2016 -0400

    Updated to version 3.4.7
    
    Signed-off-by: Larry Smith Jr <mrlesmithjr@gmail.com>

commit 9c7e5609c25cee5017c1a78928492ac54d94c1b3
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Wed Oct 5 19:58:10 2016 -0400

    Updated to version 3.4.6
    
    Signed-off-by: Larry Smith Jr <mrlesmithjr@gmail.com>

commit f0d6f11ba1a01a03c9575645ba5ca6a314107e0c
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Wed Oct 5 19:56:47 2016 -0400

    Updated to version 3.4.5
    
    Signed-off-by: Larry Smith Jr <mrlesmithjr@gmail.com>

commit db2d245d9ec82553790d0c52fe7a5487c6028f42
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Wed Oct 5 19:51:27 2016 -0400

    Updated to version 3.4.4
    
    Signed-off-by: Larry Smith Jr <mrlesmithjr@gmail.com>

commit 378ae572d119c7d5ea9191ab1a654cf12042be4d
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Wed Oct 5 19:49:54 2016 -0400

    Updated to version 3.4.3
    
    Signed-off-by: Larry Smith Jr <mrlesmithjr@gmail.com>

commit a25abb46df4e5b5ae1556cada1fa9a803703a3ad
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Wed Oct 5 19:37:52 2016 -0400

    Split into sep. repos for Auth/Recursor
    
    Signed-off-by: Larry Smith Jr <mrlesmithjr@gmail.com>

commit a724e0d3c09f78ecdf7d4322ae1a7314c5240a22
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Wed Oct 5 18:22:18 2016 -0400

    Made pdns_zone executable
    
    Signed-off-by: Larry Smith Jr <mrlesmithjr@gmail.com>

commit 31268c1a62ec96bd4c8b1c2c1e30944d90fcec44
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Wed Oct 5 16:51:23 2016 -0400

    Added ability to define both auth/recursor ports
    
    Signed-off-by: Larry Smith Jr <mrlesmithjr@gmail.com>

commit 5717047b278ef25701c6be3ca72bb4799d462459
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Thu Sep 1 21:46:30 2016 -0400

    Added PDNS notify option
    
    Signed-off-by: Larry Smith Jr <mrlesmithjr@gmail.com>

commit 7b8c5ab857a35f7aa044067d938f4369d666d7ee
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Mon Jun 27 22:43:17 2016 -0400

    Added SOA API function
    
    Signed-off-by: Larry Smith Jr <mrlesmithjr@gmail.com>

commit dd2b5f7fc75a339fdf9af4cc1fed20300ecd5188
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Sat Jun 25 11:28:46 2016 -0400

    Added Master/Slave zone functionality
    
    Signed-off-by: Larry Smith Jr <mrlesmithjr@gmail.com>

commit 4fb327e7f7b2838d3d82a9346270b16fdd4428a5
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Thu Jun 23 16:00:40 2016 -0400

    Added ability for Master/Slave setups
    
    Signed-off-by: Larry Smith Jr <mrlesmithjr@gmail.com>

commit 892494b7e995ced308b84b4614a1f45fa95fd026
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Thu Jun 9 18:06:54 2016 -0400

    Added option to listen on all interfaces
    
    Signed-off-by: Larry Smith Jr <mrlesmithjr@gmail.com>

commit 757e029599e736d6cad4ebfe0ca8f6752f12decc
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Thu Jun 9 14:25:51 2016 -0400

    Added i386 support
    
    Signed-off-by: Larry Smith Jr <mrlesmithjr@gmail.com>

commit 8ad2767dcbb516c4b204fd2b3d935b82a928c04b
Author: Larry Smith Jr <mrlesmithjr@gmail.coml>
Date:   Sun May 15 13:40:36 2016 -0400

    Added Debian Jessie support
    
    Signed-off-by: Larry Smith Jr <mrlesmithjr@gmail.coml>

commit d908f78018e412f1f8eb9d240be35980f2d30c9e
Author: Larry Smith Jr <mrlesmithjr@gmail.coml>
Date:   Sun May 15 10:28:57 2016 -0400

    Cleaned up formatting
    
    Signed-off-by: Larry Smith Jr <mrlesmithjr@gmail.coml>

commit 90b4e9bd2887007b92c3fbd386adc5fed6d1e80e
Author: Larry Smith Jr <mrlesmithjr@gmail.coml>
Date:   Sun May 15 10:20:30 2016 -0400

    Cleaned up formatting
    
    Signed-off-by: Larry Smith Jr <mrlesmithjr@gmail.coml>

commit 577d99cb073f8bdd488ba1151bc8440e8fc8d7a5
Author: Larry Smith Jr <mrlesmithjr@gmail.coml>
Date:   Sun May 15 10:19:34 2016 -0400

    First commit after re-design
    
    Completely rewrote this role to allow
    for other distro installs..Now supports
    Debian and CentOS..
    
    Signed-off-by: Larry Smith Jr <mrlesmithjr@gmail.coml>

commit c8b3a1c1c2fb81980c9a1eca86a1656d29003496
Author: Larry Smith Jr <mrlesmithjr@gmail.coml>
Date:   Sun May 15 00:24:12 2016 -0400

    Cleaned up conditional formatting
    
    Signed-off-by: Larry Smith Jr <mrlesmithjr@gmail.coml>

commit ab9f5771cf9e3a131f869d876494af3ef4c379e0
Author: Larry Smith Jr <mrlesmithjr@gmail.coml>
Date:   Sun May 15 00:17:07 2016 -0400

    Added conditional for Debian
    
    Signed-off-by: Larry Smith Jr <mrlesmithjr@gmail.coml>

commit 0049833e709dcfeb3819aef2bf2c3adee4faaf4a
Author: Larry Smith Jr <mrlesmithjr@gmail.coml>
Date:   Sat May 14 10:29:08 2016 -0400

    Fixed conditions for installing poweradmin
    
    Signed-off-by: Larry Smith Jr <mrlesmithjr@gmail.coml>

commit 46237cb679bbaa0a51775aef8135405d6618e15f
Author: Larry Smith Jr <mrlesmithjr@gmail.coml>
Date:   Sat May 14 09:42:51 2016 -0400

    Fixed conditions for installing poweradmin
    
    Signed-off-by: Larry Smith Jr <mrlesmithjr@gmail.coml>

commit f7fe68c37b2468304a123d766d38170d144f2bb6
Author: Larry Smith Jr <mrlesmithjr@gmail.coml>
Date:   Fri May 13 12:20:24 2016 -0400

    Removed ansible_managed from templates
    
    Signed-off-by: Larry Smith Jr <mrlesmithjr@gmail.coml>

commit 88b56a784ec18da59e7331a89a438ed606cdfab4
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Wed Jan 20 15:17:18 2016 -0500

    Added apiip var for nsedit
    
    Signed-off-by: Larry Smith Jr <mrlesmithjr@gmail.com>

commit 6d13a01d285b68e081d3d6bc6988a9fe8da622ac
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Thu Jan 7 20:54:52 2016 -0500

    Fixed nsedit webUI issue
    
    After pulling down the latest version of nsedit the webUI was broken and not allowing
    anyone to log in. A change to the template for config.inc.php was required as well as
    changing the path for config.inc.php to be within includes/ which was the way it was
    to be for some time. However it was still working in the root of nsedit. But this has been
    resolved.
    
    Signed-off-by: Larry Smith Jr <mrlesmithjr@gmail.com>

commit fd49de3c7c4356320def9f3394d77f11cabbab16
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Mon Nov 2 10:25:30 2015 -0500

    removed allow recursive from only localhost

commit 48f217a905076e12d0aa865f786f0118b0415eb5
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Mon Nov 2 10:13:37 2015 -0500

    updated formatting of tasks and fixed missing var when authorative is not installed

commit d56901a301eeed36413c77430ce53e024b4c9590
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Tue Oct 27 09:08:18 2015 -0400

    updated template

commit 3679beac9034ee4087f5ec5f278d894d333e261e
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Tue Oct 27 08:35:19 2015 -0400

    updated template

commit fecc5de60a7af520ffa5a0a2c76c0b7a7104c188
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Tue Oct 27 07:32:55 2015 -0400

    added forward zone lookups

commit ce3459c61d19407c33b5bbe7ecbeb841249c31c9
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Sun Oct 25 19:34:40 2015 -0400

    added sleep for service to correctly start

commit ef271799b3afacf9cc18873d63407f4f60ebff4f
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Sat Oct 24 18:02:04 2015 -0400

    removed cron for dns_check

commit cd8664464d0468588a7a61e3a34d0240020eac92
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Fri Oct 23 15:09:18 2015 -0400

    fixing missing task from previous commit

commit 8013874ec9297b661e321efcf17cc921547be666
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Fri Oct 23 15:07:09 2015 -0400

    changed download location to save pdns packages

commit a752d79f4fb0784be39f937a685758460cb17e20
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Sun Oct 11 11:49:22 2015 -0400

    added force create pdns records

commit f1e8ba164304d7d789b29da852c50d8751562b52
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Sat Oct 10 16:04:27 2015 -0400

    updated meta and created force create zones

commit dae465e065b5a2d27be638baefde0b1f56db89c2
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Sat Oct 10 15:22:07 2015 -0400

    cleaned up vars,tags and updated meta

commit d0b4a68e18cf64f83a66a33f86e3d4061b07efc0
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Sat Oct 10 15:19:19 2015 -0400

    cleaned up vars,tags and updated meta

commit 16c9275ffd694304544108ca0b41bac652c55547
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Sat Oct 10 14:49:22 2015 -0400

    cleaned up vars,tags and updated meta

commit 829c8d5f8bb21ed101cb176042a29fc09f6d2976
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Wed Oct 7 21:39:36 2015 -0400

    added cleanup task for pdns records script

commit a9ad16385ca6ee39109e4866e7fe4c4b069e3198
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Wed Oct 7 21:33:24 2015 -0400

    fixing template

commit 2fcc35692de6ca1fb48287e0878fc3484d64dc6e
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Wed Oct 7 21:30:39 2015 -0400

    fixing template

commit 486991888b5d420d8eddf4dda72474beaa8df70e
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Wed Oct 7 21:23:38 2015 -0400

    fixing template

commit df008ef2de98428fb40e34bf5468033ea7f70827
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Wed Oct 7 21:15:03 2015 -0400

    created pdns records creation script

commit 6f04b031450f0a32d4a232d5135aad34e76b24b6
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Wed Oct 7 18:08:48 2015 -0400

    cleaned up vars

commit f4e23a74fe641477de8250fb86edde30a61ce175
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Wed Oct 7 16:39:09 2015 -0400

    updated meta, added task to remove temp script

commit 34584f2b6e3449151aa040f29869523cde4e977c
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Wed Oct 7 16:33:41 2015 -0400

    updated create zones script

commit 4886bb57917481ebdf6c286f259afb5c98e8e073
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Wed Oct 7 15:36:44 2015 -0400

    cleaning up tasks

commit 7826f31b5d76d35d2f89e37bfdc4a0005c38af24
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Wed Oct 7 15:34:09 2015 -0400

    cleaning up tasks

commit 34a67765f99cd0bf31c06109dff4791796ba8d8b
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Wed Oct 7 15:28:42 2015 -0400

    trying to fix template

commit 65f3ad68206475a03f0ea97bb9deb21b3386321b
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Wed Oct 7 15:08:07 2015 -0400

    trying to fix template

commit 294eb56a784f07ad64a2c944d8f704f79d44be79
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Wed Oct 7 15:02:37 2015 -0400

    trying to fix template

commit bf58f3d54b3a78be1415b526e3a1389714b4416d
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Wed Oct 7 15:01:30 2015 -0400

    trying to fix template

commit ca2d9ca2916cedc1fb8755ce209599bf8e5d4a1a
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Wed Oct 7 14:42:04 2015 -0400

    trying to fix template

commit 72652696e08016afda2f998cdb3364fbb9e13798
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Wed Oct 7 14:18:32 2015 -0400

    fixed with_items

commit 573365712a36eba9dba614c58bfe1d49a3e70638
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Wed Oct 7 14:05:32 2015 -0400

    fixed template typo

commit 96bf035660292173d3ffbb3bcfade378489911ef
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Wed Oct 7 14:01:30 2015 -0400

    fixed when condition on zone creation

commit beec4eb157bba329b88e3e40a101a5c892a8e428
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Wed Oct 7 13:58:03 2015 -0400

    trying to fix when condition

commit c9378fa7786428b443597f3b9203280e06e6e227
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Wed Oct 7 13:51:50 2015 -0400

    trying to fix when condition

commit fc25d9ceb60ce32c54da296b00013044379fdc9f
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Wed Oct 7 13:43:20 2015 -0400

    added tasks to create fwd/rev zones

commit 4fb140337f552b45c6eaa9bd910c0f3997ba6776
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Wed Oct 7 13:43:08 2015 -0400

    added tasks to create fwd/rev zones

commit d0fd1fdc382bc43481f62175750b01831c9335a2
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Wed Oct 7 11:49:32 2015 -0400

    added register on pdns record creations

commit 4db2e5d34d775f1b1d54cae2fa538ed8e70aca42
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Wed Oct 7 11:37:39 2015 -0400

    added missing template for creating zones

commit a08d8d94b4e0b650408965f6f63a34e50f90010e
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Wed Oct 7 11:34:55 2015 -0400

    added sudo: false for local tasks

commit 1bd51877a0eea8632235927489c326a7532be207
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Wed Oct 7 11:31:26 2015 -0400

    added var pdns_zones_dir to contain records/zones when adding

commit 40f30d2106796758485cfb0d8216fd22b1802ec2
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Wed Oct 7 11:20:32 2015 -0400

    added new task to create records

commit 42e4788206a2d2dff38b523ff462dde242656755
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Wed Oct 7 11:20:12 2015 -0400

    updated,renamed vars and removed some old tasks

commit 4aedffefa7e02d02ca88efb2fa5138cf118140de
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Thu Oct 1 11:02:17 2015 -0400

    added additional configuration for local-address when not using anycast

commit b7dbf3c01ee1da28034076d6b8482117db770e01
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Wed Sep 30 21:09:57 2015 -0400

    added listen on default IP when any cast is configured

commit 64089b9b904b31e83cfa95a6c673fc4aa2dfa8a3
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Wed Sep 30 10:22:25 2015 -0400

    fixed condition on whether to create pdns zones

commit 3e4f92aabc3f063119b077c94da718df877c5dba
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Tue Sep 29 22:29:52 2015 -0400

    added args for php5enmod

commit d67bfa74fb2c1339665caeff69bf92befb46b133
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Tue Sep 29 22:22:38 2015 -0400

    fixing travis tests

commit 82cf0445f99690ea9f719f4f0ebdd1ad580eb4fc
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Tue Sep 29 22:17:46 2015 -0400

    fixing travis testing

commit 103548d771ad6dc5097ca7172f93dab6d1fdaccb
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Tue Sep 29 22:09:46 2015 -0400

    fixing travis testing

commit eb786f8041d45f21b3462737071f17b2f8cf1ec7
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Tue Sep 29 22:04:05 2015 -0400

    fixing travis testing

commit 57e05b476ed909caba5c55a5f26a63c4c25e3913
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Tue Sep 29 21:59:20 2015 -0400

    added travis testing

commit d519a68640a80e359af824f6ae7fce1604342c66
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Tue Sep 29 13:06:01 2015 -0400

    added git package

commit 94e1b6fe1de9dcf70af68915547528252ad23b07
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Tue Sep 15 22:40:28 2015 -0400

    updated pdns authoritative server version

commit c5011221ee748ebab95e83cc3835e43ec54e955e
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Mon Aug 24 15:26:52 2015 -0400

    added ability to define recursor source ip for requests

commit 5089d64ff5b69f4feae1a71a1c37036beee19590
Author: Larry Smith Jr <larry.e.smith.jr@gmail.com>
Date:   Tue Aug 11 16:46:38 2015 -0400

    updated templates

commit 1a4c7b69d5d08c832618110bfb573744c4d4e0bc
Author: Larry Smith Jr <larry.e.smith.jr@gmail.com>
Date:   Wed Aug 5 16:48:11 2015 -0400

    added restart of services on reconfiguration

commit 5352520c187b6b46260121d9d73d87d712f180ea
Author: Larry Smith Jr <larry.e.smith.jr@gmail.com>
Date:   Wed Aug 5 08:32:59 2015 -0400

    updated for db clustered backend

commit 6a0914d29a1521d97638720081c9cfc0768f7477
Author: Larry Smith Jr <larry.e.smith.jr@gmail.com>
Date:   Wed Aug 5 08:29:33 2015 -0400

    updated for db clustered backend

commit faecbfdf66c0e816a2ef4bf00141b8ffa164d599
Author: Larry Smith Jr <larry.e.smith.jr@gmail.com>
Date:   Wed Aug 5 07:35:40 2015 -0400

    added powerdns library module

commit dae112606ccd50563fc9b3d931dd07d3a1f5dc59
Author: Larry Smith Jr <larry.e.smith.jr@gmail.com>
Date:   Wed Aug 5 07:07:36 2015 -0400

    fixed syntax in vars

commit f20595609e1060f8b1f87d8729100277d67fd883
Author: Larry Smith Jr <larry.e.smith.jr@gmail.com>
Date:   Tue Aug 4 15:10:49 2015 -0400

    first commit
