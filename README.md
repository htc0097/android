AOKP for the HTC Wildfire S
====================
[Android Open Kang Project](http://aokp.co)
====================================

This is the manifest for build legacy-aokp (kitkat) for legacy devices. Supported devices:

    Wildfire S (marvel)


Download the Source
===================

Please read the [AOSP building instructions](http://source.android.com/source/index.html) before proceeding.


Initializing Repository
-----------------------

    $ repo init -u https://github.com/SimplicityCM/android.git -b aokp-kitkat

Sync up:

    $ repo sync

***

Building
--------

After the sync is finished, please read the [instructions from the Android site](http://s.android.com/source/building.html) on how to build.

    . build/envsetup.sh
    brunch


You can also build (and see how long it took) for specific devices like this:

    . build/envsetup.sh
    time brunch aokp_marvel-userdebug

Remember to `make clobber` every now and then!
