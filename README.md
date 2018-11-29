local_manifests
===============
SM-G93XX

After syncing this run
```
cd frameworks/native/
git fetch https://github.com/TeamNexus/android_frameworks_native nx-9.0 
git cherry-pick aa1fe72ba54b8f1ff94cbf0dea65bd463cd9010f

cd ../../build/soong/
git fetch https://github.com/TeamNexus/android_build_soong/ nx-9.0
git cherry-pick 632057110764ba1dd169496a4a2799b277c385da

cd ../../system/netd
git reset --hard cf8382eb3d3ec48a08aa4af33a1c4b53ee508276
git cherry-pick 36d8397e936b6893447426f281b5bb463f2b9912

cd ../../hardware/interfaces
git fetch https://github.com/TeamNexus/android_hardware_interfaces/ nx-9.0
git cherry-pick 4fa05e6ab7a1219dd33432abe653ad027fd93413

cd ../..
```
from root directory of your android source, This wont be required further down the line

This goes in /android/system/.repo/local_manifests/roomservice.xml
