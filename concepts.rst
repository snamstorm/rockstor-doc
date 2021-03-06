
Basic Concepts
==============

Disk
----

A disk is a block device that is usable by Rockstor. Disks can be locally
attached SCSI or SATA drives or can be SAN backed block devices.

Rockstor only works with whole drives and not partitions. If a disk has
partitions, it is displayed in the list of available disks but is
unusable. Parition table can be wiped using the UI and make the disk usable.

Disks can be added online as long as it is supported by the underlying
hardware. Rockstor can rescan to detect new disks and make them available.

Pool
----

A pool is a collection of disks with predefined redundancy strategy.  Available
redundancy options include RAID0, RAID1 and RAID10. Redundancy strategy must be
chosen during pool creation but cannot be changed afterwards.

A pool can be resized at anytime by adding or removing drives. Obviously,
success of these operations depends on the state of the pool including current
usage.

Share
-----

A share is created by carving out a chunk from a pool. Shares can be resized
at a later time as well as exported via NFS or SMB protocols.

Snapshot
--------

A snapshot is a read-only point in time copy of a share. Since BTRFS is a CoW
filesystem, snapshots are created instantly and take up no extra space when
created.

Web UI
------

The easiest way to manage your storage with Rockstor is via it's web-ui. It can
be accessed by visiting the appliance's management IP over https using the
Firefox browser. Note that other browsers are not supported.

CLI
---

Console access to Rockstor is possible by logging in as one of the admin users
using SSH. Rockstor CLI is userfriendly with help and examples available on all
commands. CLI can also be used to perform operations non-interactively.

Smart Manager
-------------

Smart Manager includes the dashboard of WebUI, smart probes, analytics and
other features that increase operational efficiency of the storage
infrastructure.


