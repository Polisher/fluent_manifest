XenonOS Privative Source Project
===========

This project is based on [**Android Open Source Project**](https://android.googlesource.com) & [**AOSPExtended**](https://github.com/AOSPExtended).

##Credits
* [**Android Open Source Project**](https://android.googlesource.com)
* [**AOSPExtended (Based ROM)**](https://github.com/AOSPExtended)

##How to Build?

To initialize your local repository using the AospExtended trees, use a command like this:

        repo init -u git://gitlab.com/XenonOS/xenon_manifest.git -b xos-1.0

Sync up the Repo:

        repo sync -c -f -j8 --force-sync --no-clone-bundle --no-tags

Build to your Device:

        . build/envsetup.sh 

        launch aosp_(codename)-userdebug

        mka xos

        
