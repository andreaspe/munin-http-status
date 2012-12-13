munin-http-status
=================

Munin monitor, uses logtail for get http status codes between calls


Fast hack, it's intended for nginx default ""combined" access.log

It depends on "logtail" package on debian, other linuxes may work as well.

This is a wildcard plugin you should make a link to it with the name of the log you want to parse.

It needs some configuration, use environment variable to select status codes to monitor. Read the code it's almost same size of this readme

Sorry no newbie instructions if you really want to use it drop me a line. If you patch it to work in a more generic way show me the code (via pull request)

