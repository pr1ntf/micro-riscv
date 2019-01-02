# micro-riscv
_Collection of documentation and scripts for running a small RISC-V based OS_

 - Using FreeBSD as the basis for the OS as there is an active port. 
 - The host OS is OpenBSD, utilizing qemu and pf to facilitate building of the image and running the micro-riscv os itself. 
 - The basic idea is to get the smallest bootable image possible, containing at least a shell and compiler. 

Configuration to help with pf: http://brycv.com/blog/2013/notes-on-openbsd-in-qemu-on-openbsd/

Script to help with qemu: https://github.com/pr1ntf/YetAnotherQEMUScript

FreeBSD RISC-V wiki: https://wiki.freebsd.org/riscv
