
==================================================================
                 Netscape Navigator 2.02 (Windows)
==================================================================

Netscape Navigator 2.02 is subject to the terms detailed in the
license agreement accompanying it.

Version 2.02 contains new security and privacy enhancements.
Release notes for this version of the Netscape Navigator are 
available online. After starting the program, select 
"Release Notes" from the "Help" menu. This will take you to 
the following URL:

http://home.netscape.com/eng/mozilla/2.02/relnotes/windows-2.02.html

New features and known problems in this release are listed at this
location.

To submit bugs or other feedback, use the "How To Give Feedback"
option (also in the "Help" menu), which will take you to this URL:

    http://cgi.netscape.com/cgi-bin/auto_bug.cgi


NOTE: Installation is different for International and U.S Security 
      Versions. If you are in doubt about which version you have, 
      check the "About Netscape..." option under the Help menu. 
      The security capability of your Navigator will be shown in 
      the text next to the RSA logo.


==================================================================
 Instructions for International Security Version of the Navigator 
==================================================================

* Installation

   Version 2.02 is being distributed as both a 16-bit Windows
   program and a 32-bit windows program.

   If you are running Windows 3.x or WFW, you MUST use the
   16-bit Navigator even if you have Win32s installed. If you
   are running Windows 95 or Windows NT, use the 32-bit Navigator.
   To run the 32bit Navigator, you MUST have a 32-bit TCP/IP 
   stack. Both Windows 95 and Windows NT provide 32bit TCP/IP 
   stacks that you can setup.

   To obtain a copy of Netscape Navigator, first download one of
   the self-extracting executable files into a temporary 
   directory.

        for 16-bit : N16E202.EXE
        for 32-bit : N32E202.EXE

   For 16-bit users, first double click on the self-extracting
   file in the File Manager, then run the setup.exe program to
   install Netscape Navigator on your machine.

   For 32-bit users, double click on the self-extracting file
   to start the installation.

* For Win95 users, if you are using any versions prior to this
  release, you will get multiple uninstall entries in your
  Add/Remove program.  If you prefer not having multiple
  entries, you should do an uninstall to remove your previous
  version of Netscape before you install the new release.


==================================================================
      Instructions for U.S Security Version of the Navigator 
==================================================================

* Upgrading

   Version 2.02 is being distributed both as 16-bit Windows
   program and as 32-bit Windows program.

   If you are running Windows 3.x or WFW, you MUST use the
   16-bit patch file even if you have Win32s installed.  If you
   are running Windows 95 or Windows NT, use the 32-bit patch 
   file. To run the 32bit Navigator, you MUST have a 32-bit 
   TCP/IP stack. Both Windows 95 and Windows NT provide 32bit 
   TCP/IP stacks that you can setup.

   To upgrade to 2.02, first download the appropriate patch file 
   into a temporary directory. **** This Patch file will only work
   if you are upgrading from Netscape Navigator 2.01 ****
   
        for 16-bit : P202_16.EXE
        for 32-bit : P202_32.EXE

   For 16-bit users,double click on the P202_16.EXE program
   to upgrade to Netscape Navigator 2.02.

   For 32-bit users, double click on the P202_32.EXE program
   to start the upgrading.



 =================================================================
                     General Information
 =================================================================

* NAPLAYER, the Netscape audio player, will only work if you have
  a sound card installed and configured properly.  It will not 
  work with the PC speaker driver. Please check your sound card 
  manual to configure the sound card.

* Java is enabled in 32-bit version only.

* Please delete or rename your old CACHE directory and
  Netscape.hst file.

* For more information about this release, please read the release
  notes under "Help -> Release Notes".


 =================================================================
                             Win32s
 =================================================================

For Windows 3.1, Windows 3.11, and Windows for Workgroups users:

If you are running version 1.15 or below of Win32s, you will be
unable to install the Netscape Navigator unless you upgrade to 
version 1.20 of Win32s or you remove Win32.

For more information on determining the Win32s version, obtaining
or removing Win32s, please read W32info.txt included in the
self-extracting executable.

==================================================================
                            OLE 2.02
==================================================================

For Windows 3.1, Windows 3.11, and Windows for Workgroups users:

The Netscape 16bit install program will install the following OLE2
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
for the WINSOCK.DLL file that is part of a winsock package.


==================================================================
                          International
==================================================================

The Netscape installer will overwrite existing OLE2 DLLs with the
latest versions for US Windows.This will not affect 32-bit 
Windows. For 16-bit Windows, the only difference between the US
and the Japanese versions are the internationalization of error 
strings. Occasionally, the Japanese user may see an English 
language OLE2 error message after installing Netscape. Currently,
there are no Japanese versions available for the OLE2 DLLs.
Netscape is working with Microsoft to make the Japanese version 
of the OLE2 DLLs available.


==================================================================
                           Known Bugs
==================================================================

* Please see the Release Notes for a complete listing of known 
  bugs.

