# Blobs for EAS
The following are blobs that you can swap right into your ROM if you have the necessary EAS kernel and sepolicies.

* **perfd** : (/system/vendor/bin)
    * Extracted from Marlin 7.1.2 (N2G47E)

* **libqti-perfd-client.so** : (/system/vendor/lib and /system/vendor/lib64)
    * Extracted from Marlin 7.1.2 (N2G47E)

* **libcutils.so** : (/system/lib and /system/lib64)
    * Compiled with ENABLE_SCHEDBOOST flag set 
    * Allows tasks to be assigned to different schedtune groups (foreground, background, top-app, etc)

* **power.msm8996.so** : (/system/lib/hw and /system/lib64/hw)
    * Vox Populi Power HAL

