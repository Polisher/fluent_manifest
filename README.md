FluentOS Privative Source Project
===========

![fluent_logo](fluent_logo.png)

This project is based on [**Android Open Source Project**](https://android.googlesource.com), [**AOSP-RRO**](https://github.com/AOSP-RRO), and [**MaruOS**](https://github.com/maruos) has inspired us to make this project.

##Credits
* [**Android Open Source Project (Based ROM)**](https://android.googlesource.com)
* [**AOSPA / Paranoid Android (Dual Base ROM)**](https://github.com/AOSPA)
* [**MaruOS (Inspired)**](https://github.com/maruos)

##How to Build?

To initialize your local repository using the AospExtended trees, use a command like this:

        repo init -u git://github.com/FluentOS-DevLab/fluent_manifest.git -b fluent-1.0

Sync up the Repo:

        repo sync -c -f -j8 --force-sync --no-clone-bundle --no-tags

Build to your Device:

        . build/envsetup.sh 

        lunch fluent_(codename)-userdebug

        mka fluent

        
