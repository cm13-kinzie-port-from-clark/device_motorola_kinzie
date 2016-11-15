How to build - 
 Install repo from google and follow the http://source.android.com/source/initializing.html to install required package.
 
$ mkdir ~/android/system/

$ repo init -u https://github.com/CyanogenMod/android.git -b cm-13.0

$ git clone https://github.com/cm13-kinzie-port-from-clark/vendor_motorola_kinzie.git

$ git clone https://github.com/cm13-kinzie-port-from-clark/kernel_motorola_msm8992.git

$ git clone https://github.com/cm13-kinzie-port-from-clark/device_motorola_kinzie

put the repo in the right folder, go into ~/android/system/cm-13.0

$ . build/envsetup.sh

$ brunch kinzie
