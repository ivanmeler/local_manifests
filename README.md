local_manifests
===============
SM-G93XX

This goes in /android/system/.repo/local_manifests/roomservice.xml

You will also need 

https://review.lineageos.org/c/LineageOS/android_system_bpf/+/320591
https://review.lineageos.org/c/LineageOS/android_system_netd/+/320592

for build to boot as 3.18 kernels lack ebpf support and it has not been ported over to any 3.18 kernel yet
