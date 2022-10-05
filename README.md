local_manifests
===============
S7 Edge Exynos, S7 Exynos, S8 Exynos, S8+ Exynos, Note8 Exynos

This goes in /android/system/.repo/local_manifests/roomservice.xml

You will also need to apply

https://review.lineageos.org/c/LineageOS/android_vendor_lineage/+/340865

and on s7 also all of https://github.com/8890q/patches/tree/lineage-20.0

8895 can use system_security patch to work around keystore but doesnt need other patches
