#build 
* `$make i386_kmu_defconfig`
* `$make`

#build minimal rootfs
make rootfs

#Qemu
make qemu

#Qemu with debugging
make qemu-gdb


