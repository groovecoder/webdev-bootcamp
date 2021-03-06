.. index:: servers

Servers
=======

We have a number of servers that you'll regularly encounter as a web dev.

**khan** is a development server. If you choose not to develop locally, this
option is available.

**\*.allizom.org**: all our staging servers share this domain.

**webdev1.db.scl3.mozilla.com** is the webdev mysql server. See :ref:`db-cluster`.

**cm-vpn01** is where our server logs are copied. Note that you need to file
a bug to get access to this server.

Served Environments
-------------------

There are two or three main environments for our web sites:

* **dev** (currently "stage" or "preview") which serves the latest `master`.
* **stage**

  * Currently ``amo-next`` and ``crash-stats.stage`` are
    our only "stage" environments.
  * This is what will go live to production.

* **production**

.. _vpn-info:

VPN
---

To get to any Mozilla servers you will need VPN access. There are two VPN
networks: Mozilla-MV_ (Mountain View office VPN) and Mozilla-MPT_ (for access
to khan, staging servers, etc.).

If you want to use Mozilla's shared network volumes (like ``fs2``) you can
connect to the Mozilla-MV VPN.

If you need to access khan, database servers, or the cm-vpn01 server, connect
to Mozilla MPT. You'll need to file a ticket for `access to MPT`_. If you're a
web dev for Mozilla, **you need this**.

We recommend Viscosity_ for VPN.

.. _Mozilla-MPT: https://intranet.mozilla.org/IT_MPT-RemoteAccess
.. _Mozilla-MV: https://intranet.mozilla.org/JumpHost
.. _access to MPT: https://intranet.mozilla.org/IT_MPT-RemoteAccess#Login_.26_Passwords
.. _Viscosity: https://intranet.mozilla.org/IT_MPT-RemoteAccess#Viscosity_.28TunnelBlick_alternative.29
