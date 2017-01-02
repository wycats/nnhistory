==================================================================
                Netscape Navigator 3.04  (Windows)
==================================================================

Netscape Navigator 3.04 is subject to the terms detailed in the
license agreement accompanying it.

       ************************************************
        IMPORTANT!  Before going any further, please
        read and accept the terms in the file LICENSE.
       ************************************************


Release notes for this version of the Netscape Navigator are
available online.  After starting Netscape, select "Release
Notes" from the "Help" menu. This will take you to the following
URL:

 http://home.netscape.com/eng/mozilla/3.0/relnotes/windows-3.04.html

All the New Features and the Known Problems of this release are
listed there.

To submit bugs or other feedback, use the "How To Give Feedback"
option (also in the "Help" menu), which will take you to this URL:

    http://cgi.netscape.com/cgi-bin/auto_bug.cgi


==================================================================
                 Installation Instructions
==================================================================

* Installation

   Netscape Navigator 3.04 is being distributed as both a 16-bit
   Windows program and a 32-bit Windows program.  Both the 16-bit
   and 32-bit versions of Netscape are shipped in a Premium
   package that includes Plug-ins, and a Standard package that
   does not include Plug-ins.

   If you are running Windows 3.x or Windows for Workgroups,
   you MUST use the 16-bit Navigator even if you have Win32s
   installed. If you are running Windows 95 or Windows NT,
   use the 32-bit Navigator.  To run the 32bit Navigator,
   you MUST have a 32-bit TCP/IP stack.

   Both Windows 95 and Windows NT provide built-in 32bit TCP/IP
   stacks that you can setup.  You can also get (32 bit) TCP/IP
   software from third party vendors like Trumpet Software,
   and Ftp Software. 

   To obtain a copy of Netscape Navigator, download one of the
   self-extracting executable files into a temporary directory.

        for 16-bit : n16e304.exe  
                     n16e304.exe  (with Live3D and CoolTalk)
        for 32-bit : n32e304.exe  
                     n32e304.exe  (with Live3D and CoolTalk)

   16 bit users:  First double click on the self-extracting
   file in the File Manager to extract the setup files,
   then run "setup.exe" to install Netscape Navigator.

   32-bit users, just double click on the self-extracting file
   to automatically start the installation process.

* Win95 users, if you are using any versions prior to this
  release, you will get multiple uninstall entries in your
  Add/Remove program.  If you prefer not having multiple
  entries, you should do an uninstall to remove your previous
  version of Netscape before you install the new release.

* The Netscape Audio Plug-in will only work if you have a sound
  card installed and configured properly.  It will not work
  with the PC speaker driver. Please check your sound card manual
  to configure the sound card.

* If you had previously installed CoolTalk Watchdog, then you must
  uninstall the version you have and reboot your machine before
  installing the latest version.  You might experience some
  problems running Cooltalk with Matrox MGA Millennium graphic 
  adapters using early Windows95 drivers. Make sure that you are 
  running version 2.22.039 or above.

* Both CoolTalk and AVI Plugins on 16-bit version of Netscape
  require Video for  Windows.  You can download Video for Windows
  from:
     ftp://ftp.netscape.com/pub/navigator/3.04/current/windows

* For Information about Live3D, please read the Release Notes 
  under "Help-->Release Notes".

* Java is enabled in 32-bit version only.

* Please delete or rename your old CACHE directory and
  Netscape.hst file.

* For more information about this release, please read the release
  notes under "Help -> Release Notes".

==================================================================
                           Win32s
==================================================================

 Windows 3.1, Windows 3.11, and Windows for Workgroups users:

If you are running version 1.15 or below of Win32s, you will be
unable to install the Netscape Navigator unless you upgrade to
version 1.20 (or above) of Win32s.

For more information on determining the Win32s version, obtaining
or removing Win32s, please read W32info.txt included in the
self-extracting executable.

==================================================================
                          OLE 2.02
==================================================================

 Windows 3.1, Windows 3.11, and Windows for Workgroups users:

The Netscape 16bit Installer will install the following OLE2
files into the Windows System directory if there is no existing
DLL or if the existing DLL is older:

    COMPOBJ.DLL         108544          10-10-94
    MFCOLEUI.DLL        146976           1-13-95
    OLE2.DLL            302592          10-10-94
    OLE2.REG             27026          10-10-94
    OLE2CONV.DLL         57328          10-10-94
    OLE2DISP.DLL        164832          10-10-94
    OLE2NLS.DLL         150976          10-10-94
    OLE2PROX.DLL         51712          10-10-94
    STDOLE.TLB            4304          10-10-94
    STORAGE.DLL         157696          10-10-94
    TYPELIB.DLL         177216          10-10-94

==================================================================
                        Running Netscape
==================================================================

What do I need to run Netscape Navigator?

You must have a direct Internet connection before you can use
Netscape. The ability to send and receive e-mail does not
necessarily mean you can run Netscape. There are three
requirements for Netscape Navigator:

    1. A direct Ethernet connection to the net, or a dialup
       SLIP or PPP account from an Internet service provider.

    2. TCP/IP stack

    3. Netscape Navigator software

You can get a direct connection to the Internet through a service
provider in your area.  You will need to get a SLIP or a PPP
account from an Internet provider (for a dialup account).

When you have full Internet connectivity, you need to have a
TCP/IP stack, dialer, and WINSOCK.DLL file.

If you get the error message "Cannot find WINSOCK.DLL" when
running Netscape Navigator, this means your computer is looking
for the WINSOCK.DLL file which is part of the winsock package.

==================================================================
                         International
==================================================================

The Netscape installer will overwrite existing OLE2 DLLs with the
latest versions for US Windows. This will not affect 32-bit
Windows. For 16-bit Windows, the only difference between the US
and the Japanese versions are the internationalization of error
strings. Occasionally, the Japanese user may see an English
language OLE2 error message after installing Netscape. Currently,
there are no Japanese versions available for the OLE2 DLLs.
Netscape is working with Microsoft to make the Japanese version of
the OLE2 DLLs available.

==================================================================
              Information about the Quicktime Plug-in
==================================================================


This part describes what you will need and how to use the
Windows version of Apple's QuickTime plug-ins for Netscape
Navigator 3.04.

WHAT THE QUICKTIME PLUG-IN DOES:

Apple's QuickTime plug-in for Netscape Navigator 3.04 or
later lets you experience QuickTime content directly in the
Navigator browser window. You no longer need a "helper
application" like MoviePlayer to view QuickTime content with
Navigator 3.04. You can also view QuickTime VR Panoramas and
Objects inline, after downloading the QuickTime VR component
from Apple. As a web developer, you can control the
QuickTime playback experience through HTML commands. You can
choose to have a movie automatically played for a user, or
present a controller giving users the ability to play, stop,
fastforward, and rewind.

The QuickTime plug-in works with existing QuickTime movies,
and with movies prepared to take advantage of the plug-in's
"fast start" feature. The "fast start" feature will present
the first frame of the movie almost immediately and can
begin playing even before the movie has been completely
downloaded. The "fast start" feature saves you time waiting
for the entire movie to download, but otherwise plays just
like regular QuickTime movie.

Netscape Navigator will use the QuickTime plug-in
automatically to play any QuickTime movie while browsing the
internet.  The plug-in can play many kinds of QuickTime
movies (.mov files) including movies with text, MIDI, and
other kinds of data. If you have downloaded and installed
the QuickTime VR component, it will also let you interact
with QuickTime VR Panoramas and Objects.

WHAT YOU NEED:

* A PC running Windows 95, NT, or 3.1.

* Latest version(s) of QuickTime : 
   - QuickTime 2.1.1 for Windows

You can download version of QuickTime from 
http://quicktime.apple.com/qt/sw/sw.html
Follow the instructions on the page to install the software.
The PC files are in ZIP format and you will need a utility
such as pkunzip to extract the software.

* Apple's QuickTime plug-in
You can obtain the QuickTime plug-in by downloading Netscape
Navigator 3.04 (http://home.netscape.com). Please make sure
you have downloaded the plug-in that is most appropriate for
the computer you are using.

* QuickTime VR
If you would like to view QuickTime VR (Virtual Reality)
Panoramas and Objects using the QuickTime plug-in, you will
need the QTVR library for Windows (QTVRW.QTC). The QTVR 
software is *not* included with Netscape Navigator 3.04, 
but you can download them from either the Apple QuickTime VR
site (http://qtvr.quicktime.apple.com) or the QuickTime
Software page (http://quicktime.apple.com).

On Windows, the QTVRW.QTC file must be in the WINDOWS
directory of your primary drive.

If you have never seen QuickTime VR before, be sure to stop
by Apple's QuickTime VR web page
(http://qtvr.quicktime.apple.com) to learn more about this
cool software.

* Netscape Navigator 3.04 or later
You can download Navigator 3.04 from Netscape's site at
http://home.netscape.com

HOW TO USE THE PLUG-IN:

Netscape Navigator 3.04 includes the QuickTime plug-in. When
you run Navigator 3.04, the plug-in will be ready to use.

If you are downloading the QuickTime plug-in or the
QuickTime VR components for the plug-in from Apple's web
site, you must quit Netscape Navigator and move the software
to the appropriate location (see above).  When you relaunch
Navigator, the plug-in will be loaded and ready to use.

After you have downloaded and set up the software, you may
want to re-visit our
site (http://quicktime.apple.com) for additional information
on:
   * Cool sample pages that illustrate how you can 
     incorporate Quicktime into your web pages.
   * Pointers to pages by other companies that incorporate
     QuickTime.
   * Information on how to optimize your movies for playback
     on the internet.
   * Documentation how to customize your web pages to take
     full advantage of the QuickTime plug-ins.


FREQUENT QUESTIONS:

Q: Should Windows users download the 16-bit or 32-bit
version of the QuickTime plug-in, or both?
A: First of all, if you are using Netscape Navigator 3.04,
you do not need to download the plug-in, it is bundled with
Navigator 3.04.  But beyond that,  definitely *not* both.
Download the version of the plug-in that matches the version
of Navigator you are running. If you are not sure which
version you are running, look inside the PLUGINS folder in
your NETSCAPE folder. If you see Npnull16.dll, you are using
16-bit Navigator. If you see Npnull32.dll, you are using
32-bit Navigator.

Q: I am running Windows '95 (or NT). I downloaded the
QuickTime VR software (QTVRW.QTC), installed it in my
WINDOWS directory, and rebooted. But When I run Navigator
with the QuickTime VR component, I can't view QuickTime VR
Panoramas and Objects.
A: Currently there is only a 16-bit version of the QuickTime
VR software for Windows. The 16-bit version will not work
with a 32-bit (Windows '95/NT) version of Netscape
Navigator. If you would like to use the QuickTime VR
software with Navigator, you will have to download and use
the Windows 3.1 version of Netscape Navigator. When a 32-bit
version of the QuickTime VR component is available for
Windows '95/NT users, we will post it on the QuickTime web
site (http://quicktime.apple.com).

Q: I downloaded Netscape Navigator 3.04, but the QuickTime
plug-in doesn't seem to be working.
A: Navigator 3.04 lets you pick plug-ins for different types
of content, just like you pick helper apps. You may need to
pick the QuickTime plug-in in the Navigator
"Options/Helpers" dialog to make the QuickTime plug-in work.

Q: I am using a Web browser other than Netscape Navigator
3.04 and I am experiencing problems with the QuickTime
plug-in.
A: Currently, the QuickTime plug-in only supports Netscape
Navigator 3.04 or later.

Q. I design web pages and would like to know more about
movie controls and other capabilities of the QuickTime
plug-in. Where should I look for documentation?
A: The QuickTime plug-in provides a number of new and
exciting options for internet content providers. Please
check the documentation at http://quicktime.apple.com to
learn more.

Q: I am browsing a page with a QuickTime VR panorama and
expect that I can use the option and control (shift and
control on Windows) to zoom in/zoom out of the movie.
Likewise, with a regular QuickTime movie, I expect the arrow
keys to step through the movie a frame at a time. But the
movies don't seem to respond to keystrokes.
A: You need to select the QuickTime VR panaroma or QuickTime
movie first by clicking on it. On Windows, the arrow keys do
not work.

Q. I'd like to save some of the movies to my hard drive. How
do I do this?
A. You can click on the movie and press Command-S on the
Macintosh or Control-S on the PC to bring up a "save"
dialogue. However, this will not work for QuickTime VR
movies. To save QuickTime VR movies go to the Navigator 3.04
menu, select Options/General Preferences/Helpers, then
select QuickTime from the list and choose Edit. At this
point, you'll be presented with a few options, all will work
for saving QuickTime VR files.

In case of trouble:

If you run into difficulties or have comments, please let us
know by sending e-mail to either:

Installation problems: webmaster@quicktime.apple.com
Comments/bug reports for the plugins: quicktime.apple.com

Please be sure to let us know which version of the plug-in
you are using (Mac or Windows) and which operating system
(which system software or version of Windows) you are
running. Because of the heavy traffic on the QuickTime
pages, we may not be able to respond to your e-mail
individually. We appreciate your feedback!


We hope you enjoy the QuickTime plug-in!


==================================================================
                          Known Bugs
==================================================================

* Please check the Release Notes for a complete list of known
  bugs. Release Notes are available at the following URL:

http://home.netscape.com/eng/mozilla/3.0/relnotes/windows-3.04.html
