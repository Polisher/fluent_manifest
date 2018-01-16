FluentOS Privative Source Project
===========

![fluent_logo](fluent_logo.png)

This project is based on [**Android Open Source Project**](https://android.googlesource.com), [**AOSPExtended**](https://github.com/AOSPExtended), [**AOSP-JF-MM**](https://github.com/AOSP-JF-MM) and the Ideas of [**MaruOS**](https://github.com/maruos).

##Credits
* [**Android Open Source Project (Based ROM)**](https://android.googlesource.com)
* [**AOSPExtended (Modifications to build the System)**](https://github.com/AOSPExtended)
* [**AOSP-JF-MM**](https://github.com/AOSP-JF-MM)
* [**MaruOS (Inspired)**](https://github.com/maruos)

##How to Build?

To initialize your local repository using the AospExtended trees, use a command like this:

        repo init -u git://gitlab.com/FluentOS/fluent_manifest.git -b fluent-1.0

Sync up the Repo:

        repo sync -c -f -j8 --force-sync --no-clone-bundle --no-tags

Build to your Device:

        . build/envsetup.sh 

        launch fluent_(codename)-userdebug

        mka fluent

        
