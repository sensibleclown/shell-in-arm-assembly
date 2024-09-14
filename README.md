
### Run in x86 with Qemu

Compile With:
arm-linux-gnueabihf-gcc -o shell shell.s -static -nostdlib

Run With:
qemu-arm ./shell