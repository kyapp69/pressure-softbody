2D Pressurized Soft Body Simulation
===================================

An implementation of Maciej Matyka's soft body
[tutorial paper](http://panoramix.ift.uni.wroc.pl/~maq/soft2d/howtosoftbody.pdf).
Although Java Java is not ideal
performance-wise for this sort of thing, it has the benefit that it is readily
[demo](http://smacke.net/pressure-softbody/softbody.html)able straight from the web.

Note: I wrote this in high school, which is the reason for the single source
file, default package, and awful code. I cleaned it up a little since then, but
not by much.  Still, it is nice in that it's self-contained for anybody looking
for a terrible example of Java multithreading to manually update AWT
components.

TODO
====

Java 7 and/or current browsers don't like self-signed certs. I need to add a
cert from some trusted CA when signing. This is at the very least an enormous
pain in the arse.

License
=======

Code is released under the FreeBSD / simplified BSD license.