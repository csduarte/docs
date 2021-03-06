.. _install-rhel-71:

=================================
Installing Mattermost on RHEL 7.1
=================================

Install a production-ready Mattermost system on 1 to 3 machines.

.. include:: install-common-intro.rst

.. contents:: Install and configure the components in the following order. Note that you need only one database, either MySQL or PostgreSQL.
  :backlinks: top
  :local:
  
.. include:: install-rhel-71-server.rst
.. include:: install-rhel-71-mysql.rst
.. include:: install-rhel-71-postgresql.rst
.. include:: install-rhel-71-mattermost.rst
.. include:: config-mattermost-server.rst
.. include:: config-tls-mattermost.rst
.. include:: install-rhel-nginx.rst
.. include:: config-proxy-nginx.rst
.. include:: config-ssl-http2-nginx.rst
