FluentOS Privative Source Project
===========

![fluent_logo](fluent_logo.png)

**This information has unused for now**

**This project is unestable for now - Wait for the last changes later...**

This project is based on [**Android Open Source Project**](https://android.googlesource.com), [**AOSPExtended**](https://github.com/AOSPExtended), and [**MaruOS**](https://github.com/maruos) has inspired us to make this project.

##Credits
* [**Android Open Source Project (Based ROM)**](https://android.googlesource.com)
* [**AOSPExtended (Dual Base ROM)**](https://github.com/AOSPExtended)
* [**MaruOS (Inspired)**](https://github.com/maruos)

##How to Build?

To initialize your local repository using the FluentOS Android trees, use a command like this:

        repo init -u git://github.com/FluentOS-DevLab/fluent_manifest.git -b fluent-1.0

Sync up the Repo:

        repo sync -c -f -j8 --force-sync --no-clone-bundle --no-tags

Build to your Device:

        . build/envsetup.sh 

        lunch fluent_(codename)-userdebug

        mka fluent

        
