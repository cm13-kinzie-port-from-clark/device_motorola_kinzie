How to build - 
 Install repo from google and follow the http://source.android.com/source/initializing.html to install required package.
 
$ mkdir ~/android/system/

$ repo init -u https://github.com/CyanogenMod/android.git -b cm-13.0

$ repo sync

$ git clone https://github.com/cm13-kinzie-port-from-clark/vendor_motorola_kinzie.git

put this repo in ~/android/system/cm-13.0/vendor/motorola/kinzie/

$ git clone https://github.com/cm13-kinzie-port-from-clark/kernel_motorola_msm8992.git

put this repo in ~/android/system/cm-13.0/kernel/msm8992/

$ git clone https://github.com/cm13-kinzie-port-from-clark/device_motorola_kinzie

put this repo in ~/android/system/cm-13.0/device/motorola/kinzie

$ . build/envsetup.sh

$ brunch kinzie
