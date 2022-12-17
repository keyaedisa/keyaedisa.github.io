---
title: "newKai + newKaiso"
date: 2022-12-14T17:57:33-05:00
type: post
---

newKai is the successor to a project I called Kairo. Kairo was my first
attempt at building my own Arch ISO. Kairo used Arco's base. newKai was
created because I quickly realized Kairo was not truly a custom Arch ISO.
Since it used a lot of Arco's stuff it was really just a custom Arco ISO.
newKai was created to remedy this.

As development on newKai moved forward a few core ideals were realized.
- Stay as light as possible
- Replace Calamares
- Provide out of the box support for my 2011 Macbook Pro
- Create a live USB environment (newKaiso)


newKaiso is the live USB portion of newKai. newKaiso was designed to be
a fully functioning system that could be used every day without needing
to be installed onto physical hardware. It also came bundled with everything
needed to install newKai to a physical system.

newKai only comes with exactly what is needed to boot and install to
physical hardware. This presented a few issues for me at first. The biggest
and most annoying one was that due to Apple using a proprietary net card,
there wasn't an out of the box solution for working ethernet and wifi.
I tried several drivers and none of them worked. Ultimately I had to modify
a b83 driver and several other system functions like the order that drivers
and modules came online during boot as well as blacklisting (and unblacklisting)
certain modules. This was a problem that was not properly documented online and
something that affects nearly every Macbook using the same family of network
controllers. I fixed it and simplified everything like DHCP and more. It also
was very security focused.

Calamares was replaced with two scripts I wrote. They work in unison as a CLI
installer. It is used today in ValenOS and ValenSE.

newKai was ultimately abandoned because after finally learning everything I
needed to properly setup Arch from scratch and then automate it, the time to
theme newKai arrived. This is where I lost motivation. The motivation for newKai
was to build an OS that used only my stuff. When the time came to decide what it
looked like I could not make up my mind on what WM or desktop to use. This led to
newKai being split into two versions: KDE and DWM. Ricing just really isnt my fancy
and after finishing the DWM rice I decided I didn't want to do this anymore let alone
maintain it. Around this time I became an official member of XeroLinux and decided to
just help Xero be the best it could be.
