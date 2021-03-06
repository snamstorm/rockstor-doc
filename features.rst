Feature overview
================

User friendly web-ui
--------------------

Rockstor web-ui is designed to efficiently manage large and complex storage
infrastructure. It is also designed for intuitive user experience, which
eliminates the need to read extensive documentation and learning to be able to
use it. Below are the feature highlights. See :ref:`webui` for a more detailed
explanation.

* Secure access via HTTPS.

* Efficiently perform storage management including pool and share
  creation, snapshots, nfs exports, etc..

* Efficiently perform necessary system management including
  directory services, user management etc..

* Customize dashboard per admin user by choosing relevant widgets and their
  layout.

* Visualize smart probe data for deeper insights.

* Manage other Rockstor appliances by quick switching.

User friendly CLI
-----------------

Rockstor CLI is designed to provide every necessary command without
overwhelming the user. All commands have documentation and examples. Below are
the feature highlights. See :ref:`cli` for a more detailed explanation.

* Secure access via SSH

* Switch to specific consoles of subsystems like pools, shares, nfs, network
  etc.. for a clean user experience.

* Automate using CLI batch mode from any language including Shell, Perl and
  Python.

* Retrieve commands from history.

Online disk management
----------------------

* Rescan the system for any new disks and make them available instantly for
  pools. (Hardware support may be necessary)

* Visualize top disks based on activity

* Act on disk alerts, repair and remove disks from the system if necessary
  without unnecessary disruption.

Online Pool management
-----------------------

* Create pools instantly using the web-ui or CLI.

* Resize pools online by adding or removing whole disk drives.

* Schedule scrub operations for periodic maintenance

Online Share and Snapshot management
------------------------------------

* Create shares instantly using the web-ui or CLI.

* Resize pools online, thin provision or over provision according to your
  needs.

* Export shares via NFS and SMB protocols

* Create snapshots for shares instantly or schedule snapshots to be created
  periodically.

* Create unlimited number of snapshots for a given share.

* Toggle snapshot visibility to the end user via NFS.

* Rollback a share to one of it's snapshots.

Share replication
-----------------

* Replicate shares from one Rockstor appliance to others.

Directory services
------------------

* LDAP

* NIS

* AD

NFS Analytics
-------------

Server side NFS analytics are available with Rockstor's smart probes. These
probes can be run on demand to collect insightful information about NFS
workloads. The following probes are available

* Call metadata for the entire system.

* Share specific call metadata.

* Client specific call metadata.

* Call metadata for each pair of Client and Share

* Call metadata with specific uid and gid information.

See :ref:`analytics` for more details.


Support
-------

Free and commercial support is available for Rockstor. See :ref:`support` for
more information.

