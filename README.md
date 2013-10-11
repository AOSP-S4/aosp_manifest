AOSP 4.3 FOR I9505 (Galaxy S4)
===============================



Download:
----------
* mkdir ~/AOSP
* cd ~/AOSP
* repo init -u git://github.com/AOSP-S4/aosp_manifest -b jb-4.3
* repo sync


Building:
----------
* . build/envsetup.sh
* lunch 
* make otapackage -j5 

(where 5 is the number of cpu cores + 1)





