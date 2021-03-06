
.. _installation:

Installation
============

Installation of Rockstor is a short and straight forward process. For all types
of installations, see :ref:`quickstartguide` to get started.

.. _quickeval:

Quick evaluation using a virtual environment
--------------------------------------------

Rockstor can also be evaluated quickly using a virtual machine.

See our YouTube `VirtualBox Rockstor install demo
<https://www.youtube.com/watch?v=00k_RwwC5Ms>`_ or our :ref:`kvmsetup`

Before proceeding with a serious installation that may require hardware
procurement, you can evaluate Rockstor on Amazon AWS. See our YouTube video on `Rockstor on ec2
<https://www.youtube.com/watch?v=ys_8FLVov2U>`_.

Hardware recommendations:
-------------------------

At the bare minimum, see :ref:`minsysreqs` for a basic recommendation. This
translates to most commodity servers with more than a couple of disk
drives. Based on your cost constraints and performance requirements, several
hardware configurations are possible as described below.

Small Office or Home NAS
^^^^^^^^^^^^^^^^^^^^^^^^

See our :ref:`sohoguide` or our :ref:`homenasguide`

All Flash NAS
^^^^^^^^^^^^^
Coming soon...

Upgrading Rockstor
------------------

Rockstor is under continuous development. However, we strive to make most
updates non-disruptive. You can safely update Rockstor anytime with the
following command::

    [root@localhost ~]# yum update rockstor

If an update is disruptive, the update process prompts for user action and
provides the necessary information to choose to update or not. You can safely
decide not to update if that makes sense for your environment.



