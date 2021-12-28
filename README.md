# Codename Spectrum
An open-source operating system that I'm making as a side project. The bootloading is currently handled by the -kernel flag in QEMU. 
This isn't meant for real hardware since it's so outdated, so I probably won't add a bootloader.

Keep in mind all this is subject to change, especially since I rarely update the readme.

IMPORTANT: The OS is 32 bit. It will not run on modern hardware. Use a VM, preferably QEMU.

# The 'main' branch is usually is a WIP, refer to Releases for stable versions.

Use ```bash build.sh``` to build the OS.

# To-Do:

Get RTC time

Add support for backspace & shift in keyboard.



This is under the GPL license now because this: https://github.com/arjun024/mkeykernel/blob/master/LICENSE

Most of the code is taken from the following repo: https://github.com/arjun024/mkeykernel
Changes made: expanding on the kernel, taking the code for the keyboard handler, adding more IDT entries and a kernel panic screen.


Also naming system: Pick a codeword and make up a better name closer to release.
