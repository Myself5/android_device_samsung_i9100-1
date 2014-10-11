Roomservice
===========

```xml
<?xml version="1.0" encoding="UTF-8"?>
<!--Please do not manually edit this file-->
<manifest>
  <project name="Myself5/android_device_samsung_i9100-1" path="device/samsung/i9100" remote="github" revision="AOSP" />
  <project name="OmniRom/android_device_samsung_galaxys2-common" path="device/samsung/galaxys2-common" remote="github" revision="android-4.4" />
  <project name="omnirom/android_kernel_samsung_smdk4412" path="kernel/samsung/smdk4412" remote="github" revision="android-4.4" />
  <project name="TheMuppets/proprietary_vendor_samsung" path="vendor/samsung" remote="github" revision="cm-11.0" />
  <project name="OmniRom/android_hardware_samsung" path="hardware/samsung" remote="github" revision="android-4.4" />
  <project name="OmniRom/android_packages_apps_SamsungServiceMode" path="packages/apps/SamsungServiceMode" remote="github" revision="android-4.4" />
  <remove-project path="hardware/ril" name="platform/hardware/ril" groups="pdk" />
  <project path="hardware/ril" name="OmniRom/android_hardware_ril" remote="github" revision="android-4.4" />
  <remove-project path="prebuilts/gcc/linux-x86/arm/arm-eabi-4.8" name="platform/prebuilts/gcc/linux-x86/arm/arm-eabi-4.8" groups="pdk,linux,arm" />
  <project name="SaberMod/android_prebuilts_gcc_linux-x86_arm_sabermod-arm-eabi-4.7" path="prebuilts/gcc/linux-x86/arm/arm-eabi-4.8" remote="github" revision="master" />
</manifest>
```
