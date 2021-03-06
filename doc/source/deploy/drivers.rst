.. _drivers:

================
Enabling drivers
================

Ironic-Python-Agent (agent)
---------------------------

Ironic-Python-Agent is an agent that handles *ironic* bare metal
nodes in various actions such as inspection and deployment of such
nodes, and runs processes inside of a ramdisk.

For more information on this, see :ref:`IPA`.

IPMITool driver
---------------

.. toctree::
  :maxdepth: 1

  ../drivers/ipmitool

DRAC driver
-----------

DRAC with PXE deploy
^^^^^^^^^^^^^^^^^^^^

- Add ``pxe_drac`` to the list of ``enabled_drivers`` in
  ``/etc/ironic/ironic.conf``
- Install python-dracclient package


SNMP driver
-----------

.. toctree::
  :maxdepth: 1

  ../drivers/snmp

iLO driver
----------

.. toctree::
  :maxdepth: 1

  ../drivers/ilo

SeaMicro driver
---------------

.. toctree::
  :maxdepth: 1

  ../drivers/seamicro

iRMC driver
-----------

.. toctree::
  :maxdepth: 1

  ../drivers/irmc

VirtualBox driver
-----------------

.. toctree::
  :maxdepth: 1

  ../drivers/vbox


Cisco UCS driver
----------------

.. toctree::
  :maxdepth: 1

  ../drivers/ucs


CIMC driver
-----------

.. toctree::
  :maxdepth: 1

  ../drivers/cimc


OneView driver
--------------

.. toctree::
  :maxdepth: 1

  ../drivers/oneview


XenServer ssh driver
--------------------

.. toctree::
  :maxdepth: 1

  ../drivers/xenserver


Unsupported drivers
-------------------

The following drivers were declared as unsupported in ironic Newton release
and as of Ocata release they are removed form ironic:

- AMT driver - available as part of ironic-staging-drivers_
- iBoot driver - available as part of ironic-staging-drivers_
- Wake-On-Lan driver - available as part of ironic-staging-drivers_

.. _ironic-staging-drivers: http://ironic-staging-drivers.readthedocs.io
