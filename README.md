# BradOS
Note: The .iso files are acting a little weird compared to the straight bin file.
I'd recommend using the bin file, however the ISO still works. It just has display issues.

The ISO and bin file that's in the root directory is the most current version. All old versions are in /OldVersions.

# How to use the bin and ISO file?

I use qemu, so go ahead and use/install qemu.

If you're using the kernel.bin type:

`qemu-system-i386 -kernel kernel.bin`

If you're using the ISO type:

`qemu-system-i386 -cdrom BradOS V X.X.X.iso`

If you use VMWARE Player or Virtual Box, follow these steps:

Create a new virtual machine. Select "other" for type of operating system, and choose the ISO file I provided as your main boot device.

*The OS doesn't require more than 1 core, and can probably run with the minimalist of setups. (1mb RAM, 0GB HDD & 1MB VRAM).

\* I haven't tested it fully, but 1MB RAM and 0GB HDD works fine.

# How do I use the operating system?

The "help" command is quite useful. As is the Changelog file. 

## What's the password?

"password"
