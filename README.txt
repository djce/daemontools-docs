What is this?
=============

A collection of supplementary documentation about daemontools
<http://cr.yp.to/daemontools.html>.

To quote the above page,

  daemontools is a collection of tools for managing UNIX services.

  supervise monitors a service. It starts the service and restarts the service
  if it dies. Setting up a new service is easy: all supervise needs is a
  directory with a run script that runs the service.

  multilog saves error messages to one or more logs. It optionally timestamps
  each line and, for each log, includes or excludes lines matching specified
  patterns. It automatically rotates logs to limit the amount of disk space used.
  If the disk fills up, it pauses and tries again, without losing any data. 

What is this NOT?
=================

It's not a reference manual for the daemontools programs.  Please refer to
your system's man pages (if provided), or the daemontools home page (see
above, otherwise), for that.

Rather, it's a collection of documentation about how to use daemontools in
practice.

Contents
========

README.txt              This file
introduction.txt        An introduction to daemontools
debugging.txt           How to debug service problems and disentangle things

Credits
=======

The documentation lives on github <https://gitcom.com/rvedotrc/daemontools-docs>
and is maintained by Rachel Evans <http://rve.org.uk/>.

