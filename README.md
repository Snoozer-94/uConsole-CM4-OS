# uConsole CM4 OS
 Community made OS's compatible for ClockworkPi uConsole CM4

All OS's are in Releases >>>>>>>>>

uConsole-2024-03-15-raspios-bookworm-arm64.img.7z - Still crooked (90 degrees) like the previous one but has gparted to expand storage to your sd card size, the screen can be rotated in Applications>Preferences>Screen Configeration. Also no 4G im afraid, had issues installing the right packages for it (probably an error in spelling) and also don't have 4G on mine to test. Please let me know if you get it working on here:  https://forum.clockworkpi.com/t/rpi-os-bookworm-cm4-i-think-i-have-cracked-getting-new-custom-os-recipe/12738

CrookedNeck-2024-03-15-raspios-bookworm-arm64.img.7z - [Not available] Basically the first workin OS with minor issues, screen rotated 90 degrees (easily changed in 'Screen Configeration') and storage is at around 5gb max so you will need to 'sudo apt install gparted' and use gparted to expaned your storage to sd cards limit.


Setup your own OS for uConsole:

Using both links bellow supplied by clockworkpi, it's a rough step by step instructions on chroot in on your chosen OS to create all needed installs before burning image onto an sd. My recommendation is to follow the uConsole guide for the chroot in and out, and for the install use Devterm guide first then uConsole, this will install everything then get rid of all files assosiated with Devterm. Yes there are some steps that you can skip because of deleting stuff that you just put on there with the Devterm instructions, hopefully i will go through and make my own guide once i get to know the process and also get stuff like 4G packages and other small issues sorted.

https://github.com/clockworkpi/uConsole/wiki/How-uConsole-CM4-OS-image-made

https://github.com/clockworkpi/DevTerm/wiki/Create-DevTerm-CM4-OS-image-from-scratch
