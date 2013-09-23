=============
heka-py-raven
=============

.. image:: https://secure.travis-ci.org/mozilla-services/heka-py-raven.png

heka-py-raven is a plugin extension for `heka-py
<http://github.com/mozilla-services/heka-py>`.  heka-py-raven
provides logging extensions to capture stacktraces and some frame
information such as local variables to faciliate debugging.

The plugin acts as a thin wrapper around the Raven
<https://github.com/dcramer/raven> library for Sentry.

This version of heka-py-raven must be used with :

  * Raven client version 2.0.6
  * Sentry server 5.0.13

Other versions may work, but they have not been tested.
