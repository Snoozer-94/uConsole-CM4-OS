# uConsole CM4 OS
 Community made OS's compatible for ClockworkPi uConsole CM4

 HOOOOOLDD UUUPP!!! This project is pretty much dead but if you want a nice selection (arch as well as debian based) of os's then I would recommend clicking this link>>> https://forum.clockworkpi.com/t/bookworm-6-6-y-for-the-uconsole-and-devterm/13235 <<<

All OS's are in Releases >>>>>>>>>

CPi CM4 OS Bookworm - Using the image ClockworkPi supplies, i've updated it from bullseye to bookworm with all the content CPi supplies. Kernel is 5.10.17-v8+ but if you want a more up to date one try this one:
https://mega.nz/folder/LSInGD6J#0YezWX8xC4PkbyForgl1Hw
Creators github is here:
https://github.com/ak-rex/ClockworkPi-linux

uConsole-LITE-2024-03-15-raspios-bookworm-arm64.img.7z - Pretty much a cli version of bookworm. You can use it how it is or you can use this guide to install your own desktop. https://raspberrytips.com/upgrade-raspbian-lite-to-desktop/

uConsole-2024-03-15-raspios-bookworm-arm64.img.7z DO NOT USE!! - Still crooked (90 degrees) like the previous one but has gparted to expand storage to your sd card size, the screen can be rotated in Applications>Preferences>Screen Configeration. Also screen brightness doesn't work (don't know why yet) and no 4G im afraid, had issues installing the right packages for it (probably an error in spelling) and also don't have 4G on mine to test. Please let me know if you get it working on here:  https://forum.clockworkpi.com/t/rpi-os-bookworm-cm4-i-think-i-have-cracked-getting-new-custom-os-recipe/12738

CrookedNeck-2024-03-15-raspios-bookworm-arm64.img.7z - [Not available] Basically the first workin OS with minor issues, screen rotated 90 degrees (easily changed in 'Screen Configeration') and storage is at around 5gb max so you will need to 'sudo apt install gparted' and use gparted to expaned your storage to sd cards limit.


Setup your own OS for uConsole:

Help yourself to the https://github.com/Snoozer-94/uConsole-CM4-OS/blob/main/uConsole-config-guide to have nice and easy copy/paste commands to put in the terminal with most of the Devterm stuff taken out. 

or

Using both links bellow supplied by clockworkpi, it's a rough step by step instructions on chroot in on your chosen OS to create all needed installs before burning image onto an sd. My recommendation is to follow the uConsole guide for the chroot in and out, and for the install use Devterm guide first then uConsole, this will install everything then get rid of all files assosiated with Devterm. Yes there are some steps that you can skip because of deleting stuff that you just put on there with the Devterm instructions, hopefully i will go through and make my own guide once i get to know the process and also get stuff like 4G packages and other small issues sorted.

https://github.com/clockworkpi/uConsole/wiki/How-uConsole-CM4-OS-image-made

https://github.com/clockworkpi/DevTerm/wiki/Create-DevTerm-CM4-OS-image-from-scratch
