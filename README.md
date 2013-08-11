AOSP 4.3 FOR I9505 (Galaxy S4)
BETA
===============================

This repo is designed to build aosp 4.3 successfully, so far it needs a lot of repositories from CM.
I will reduce the number of needed CM repo's as much as possible.

The ROM will be real AOSP (except for most libraries, which are coming from CM)
So it's  possible to use this as your custom ROM base, it's better then CM as base or Google Edition 4.3 (because of reverse-engineering)


Download:
- mkdir ~/AOSP
- cd ~/AOSP
- repo init -u git://github.com/AOSP-S4/aosp_manifest
- repo sync
 

Build:
- . build/envsetup.sh
- lunch (choose full_jfltexx-userdebug)
- make
 





