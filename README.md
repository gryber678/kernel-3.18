# kernel-3.18


# ONLY TO BUILD 64BIT KERNEL
# Doogee x5 max pro

make O=/kernel-3.18/out/OBJ64 ARCH=arm64 CROSS_COMPILE=~/Source/kernel-3.18/toolchains/aarch64-linux-android-4.9/bin/aarch64-linux-android- n370b_defconfig

make O=/kernel-3.18/out/OBJ64 ARCH=arm64 CROSS_COMPILE=~/Source/kernel-3.18/toolchains/aarch64-linux-android-4.9/bin/aarch64-linux-android- -j5
 
 _________________________________________________________________________________________________________________________________
 You will find kernel in OBJ64/arch/arch64/boot/Image.gz-dtb
 _________________________________________________________________________________________________________________________________
 *after O= Write ~ 

