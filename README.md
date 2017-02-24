The Android Open Source Project For LG G3 D855 - Nougat 7.1.1
===========


Getting Started
---------------

To get started with Android, you'll need to get familiar with [Git and Repo](http://source.android.com/source/using-repo.html).

To initialize your local repository using the AOSP trees, use a command like this:

    repo init -u git://github.com/G3-aosp-N/platform_manifest.git -b aosp-7.1.1

Then to sync up:

    repo sync

Set up build enviroment

    . build/envsetup.sh

Select device

    lunch d855 userdebug

Compile the rom

    mka otapackage
