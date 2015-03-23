OpenShift Memcached Cartridge
=============================

An OpenShift cartridge to be used as an add-on for any primary cartridge.
This cartridge provides a [Memcached](http://memcached.org/) installation.

Usage
-----

The cartridge can be added to any application either through the OpenShift web console or the [OpenShift client tools](https://developers.openshift.com/en/getting-started-client-tools.html)
using the URL http://cartreflect-claytondev.rhcloud.com/github/puzzle/openshift-memcached-cartridge. 
Example using the OpenShift client tools:

    rhc -amyapp cartridge-add http://cartreflect-claytondev.rhcloud.com/github/puzzle/openshift-memcached-cartridge
    rhc -amyapp app stop
    rhc -amyapp app start

Memcached Version Info
---------------------
The [Memcached](http://memcached.org/) version provided, currently *1.4.4*, is taken from the rpm provided by CentOS 6.

Memcached sources are available at http://memcached.org/.
