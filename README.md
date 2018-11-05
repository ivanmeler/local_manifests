local_manifests
===============
SM-G93XX

After syncing this run
```
cd build/soong/
git fetch https://github.com/TeamNexus/android_build_soong/ nx-9.0
git cherry-pick 632057110764ba1dd169496a4a2799b277c385da
cd ../../system/netd
git fetch https://github.com/LineageOS/android_system_netd refs/changes/01/231201/3 && git cherry-pick FETCH_HEAD
cd ../../hardware/interfaces
git fetch https://github.com/TeamNexus/android_hardware_interfaces/ nx-9.0
git cherry-pick 4fa05e6ab7a1219dd33432abe653ad027fd93413
cd ../..
```
from root directory of your android source, This wont be required further down the line

This goes in /android/system/.repo/local_manifests/roomservice.xml
