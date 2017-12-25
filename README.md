FluentOS Privative Source Project
===========

This project is based on [**Android Open Source Project**](https://android.googlesource.com), [**AOSPExtended**](https://github.com/AOSPExtended) and the Mechanics of [**MaruOS**](https://github.com/maruos).

##Credits
* [**Android Open Source Project (Based ROM)**](https://android.googlesource.com)
* [**AOSPExtended**](https://github.com/AOSPExtended)
* [**MaruOS (Mechanics)**](https://github.com/maruos)

##How to Build?

To initialize your local repository using the AospExtended trees, use a command like this:

        repo init -u git://gitlab.com/XenonOS/xenon_manifest.git -b xos-1.0

Sync up the Repo:

        repo sync -c -f -j8 --force-sync --no-clone-bundle --no-tags

Build to your Device:

        . build/envsetup.sh 

        launch aosp_(codename)-userdebug

        mka fluent

        
