check_openhab
=============

This is a very simple Nagios plugin that checks on items in an [OpenHAB][]
instance.  It uses OpenHAB's REST API.

  [OpenHAB]: http://www.openhab.org/

The plugin can retrieve the state of an item and either compare it
numerically to critical and warning thresholds or treat the state as a
string and match patterns against it.


Installation
------------

The plugin requires Python version 2.6 or later on the testing system and
python-dateutil.


Usage
-----

The help function (`check_openhab --help`) should cover everything you
need to know.
