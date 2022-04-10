# Thinkpad-T480s-OpenCore
The state of this project is stable. I have been daily-driving it for more than a year, with only small issues.

Laptop specs:
  - Processor: i5 8350u
  - 24GB ram
  - 512GB + 128GB ssd(for dualbooting windows; I use sepparate SSD's, as it is easier to manage)
  - Windows Hello webcam(usb mapping differs from classic camera)
  - X1Y3 touchpad(as it is glass, and feels way better)
  - Low Power IPS panel from T490(can't recall its model number, if anyone needs it pm me and I'll look for it)
  - Modded bios(unlocked cfgLock, bios-level undervolt)


Known issues: 
  - camera will sometimes stop working; usually happens once every 20-30 sleep-wake cycles(no clue what causes it, however I am satisfied with it as it is, as a reboot fixes it, so there probably won't be a fix for it);
  - performance mode(the equivalent of power profiles on windows) don't work with YogaSMC;
  - USB C hotplug is sketchy(it may take a few tries to get it to connect; once it connects, it works flawlessly);
  - thunderbolt has not been tested(and is, by default, disabled);

Other than the issues above, I have not experienced any issues worth noting.
Idle power draw varies from 3 to 5 watts. CPU goes down to 0.8 watts consumption, so the battery life is pretty much identical to Windows 10.



# Credits
This repo is based on the following projects(without which this wouldn't have been possible). Thank you guys for your hard work!
- [@tylernguyen](https://github.com/tylernguyen)
- [@benbender](https://github.com/benbender)
