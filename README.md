Android for Broadcom BCM21553 Devices - CyanogenMod 9.1
===========

Getting Started
---------------

To get started with Android for ARMv6/CyanogenMod, you'll need to get
familiar with [Git and Repo](http://source.android.com/source/developing.html).


To initialize your local repository using the CyanogenMod trees, use a command like this:

    repo init -u git://github.com/broadcomCM/android.git -b ics-plus

Then to sync up:

    repo sync
    sh vendor/cm/get-prebuilts

Build your device:

    WIP

Flash ZIP:

    out/target/product/DEVICENAME/cm-VERSION-DEVICENAME.zip


Please see the [CyanogenMod Wiki](http://wiki.cyanogenmod.org/) for building instructions.

