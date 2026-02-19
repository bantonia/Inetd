# Inetd
RISCOS application to serve tcp and udp sockets

Licence Agreement
~~~~~~~~~~~~~~~~~
The software here is PUBLIC DOMAIN in that it may be copied and distributed
to anyone and by any method which is at ones disposal. However I do hope that
the contents of this archive will remain mostly intact and unchanged in any
way as it should be seen as a collection of interworking units. However I do
expect that the modules may be distributed separately as part of other
software as long as no charge is made regarding the modules.

Feel free to modify or use code contained therein, but if any major
improvements are added, please inform me so they can be added to the
release.

Disclaimer
~~~~~~~~~~
I do not claim that this software is totally robust, as with all software
there may be undesired features which I have not taken into account.  This
software is supplied 'as is', with no guarantee of its suitablity for any
purpose.  The author cannot accept resposibility for any loss or damage
caused by the use, or mis-use, of this software or its documentation.

If you find a feature please let me know!

Sources
~~~~~~~
Sources of the daemons and !Inetd are included. They may
or may not be examples of good coding, but they work!

PollWord and AsyncSocket modules. These are at the core of all the above
applications.

Look inside !SysLog for SysLog C stuff.
I use modified headers and libraries so you may not be able to compile the
sources here directly. Also I use OSLib for the sockets library. If linked in
the correct order you can still use the wimp libraries from the toolbox.
