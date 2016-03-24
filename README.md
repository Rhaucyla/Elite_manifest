# Elite_manifest
=====================

Getting Started
---------------

To initialize your local repository, use this command:

	repo init -u https://github.com/Elite-Kernels/Elite_manifest.git -b android-n-preview-1

Then to sync source, use this command:

	repo sync -j# (where # is the number of cpu threads you want to use)

After syncing is done, use these commands to build:

    1.) . build/envsetup.sh
    2.) brunch xxxx yyyy
    
    xxxx= device name aka shamu
    yyyy= build type (user,userdebug,eng)*

    *if no build type is specified "userdebug" is default
