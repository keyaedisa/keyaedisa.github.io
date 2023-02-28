---
title: "ValenSE"
date: 2022-12-14T17:57:13-05:00
type: page
---

##Update

I'm currently completely rebuilding ValenSE from ground up. It will
no longer come preinstalled with web server software or any of the 
specific to my use case software I bundled originally. ValenSE has
been stripped of everything not essential to boot the LiveISO (this
includes everything needed to allow it to be a headless ISO. P.S. 
SSH is only configured for my personal PC, you will need to add your
own keys), and the installation scripts will be rewritten in C and
also stripped of everything non-essential. The "completed" version
will be forked and serve as the new base for any potential future
ValenOS builds.

WiFi will not work ootb initially. I'll add support for this later
when the core of ValenSE is done.

I briefly went over BIOS support with syslinux. It should work but
if it does not let me know. All my systems are UEFI/iBoot. Grub is
currenty bootloader. I'd like to bundle it with reFind. Mainly
because reFind automatically updates boot options when new OS's
are deleted or added. If this breaks BIOS support then oh well.

---------------------------------------------------------------------

ValenSE is the ISO I built for my server. I have a server I use and
maintain for data storage purposes as well hosting my own website and
potentially minecraft server.

It taught me alot about how to setup Linux and a bootloader for a BIOS
non-UEFI system. It is a command line only OS and comes bundled only
with what's needed to boot live and install. It's meant to be an Arch
based OS that is just right for those who need a server OS and nothing
more. I use it currently and it works well for me. It can be found on
my github however it's a bit specialized to my hardware. If there were
to be interest in it by others it'd be no problem setting it up to work
on any other hardware. Earlier versions did before I stripped the support
when testing on my box.
