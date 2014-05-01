Getting Started
---------------

To get started with OMNIARMv6 ROM, you'll need to get
familiar with [Git and Repo](http://source.android.com/download/using-repo).

To initialize your local repository using the OMNIROM trees, use a command like this:

    repo init -u git://github.com/MarvelMod/android.git -b android-4.4

Then to sync up:

    repo sync

Then to build:

     cd <source-dir>
     source build/envsetup.sh
     brunch <device_name> (e.g. marvel, liberty or icong)


If you need more information or a more detailed guide, click [here to see our wiki.](http://docs.omnirom.org)

Our official IRC Channels are hosted on Freenode:

[#omnirom - USERS](http://webchat.freenode.net/?channels=omnirom/)

[#omni - DEVELOPERS](http://webchat.freenode.net/?channels=omni/)
