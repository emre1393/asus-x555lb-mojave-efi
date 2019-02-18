# Asus X555LB hackintosh setup for mac os mojave
hackintosh efi for asus x555lb, it has dsdt patch and kexts and clover config.  
mac os 14.3 mojave works nice with this files. i got help from hackintosh forums and great peoples.  

english is not my native language, i explained everything at a turkish forum https://osxinfo.net/konu/basarili-kurulum-asus-k555lb-x555lb-macos-mojave.6197/
you can read that with google translate, you will understand the article. i updated something of setup in few weeks later. lilu and its addons are used in this github version.  
ie: the things that needs ssdt patch are working with whatevergreen kext and intel framebuffer patcher config now. just 1 kext (weg) solves a lot of problem.  

i have used rehabman's clover fork. it is outdated but works fine. all kexts are in /e/c/k/other folder, installing them to s/l/e or l/e is not required.  

System Properties (specs):  
Processor: intel core i5 5200u broadwell  
Display Card: intel hd5500 + nvidia 940m  
Display: 1366 * 768 lcd  
Ram: 12 GB (8 + 4) 1600Mhz  
Sound: Realtek Alc233  
ssd1: windows 10, ssd2: mojave  
Ethernet: Realtek RTL8168 / 8111 PCI-E Gigabit  
Wifi: AzureWave AW-CE123H (14E4: 43B1) WIFI + BT card (replaced, the old mediatek card is sucks)  
  
Working things:  
Graphics HD5500 IGPU  
Realtek alc233 sound  
--- Built-in speaker and microphone is working, there is static noise / squeal at headphone output  
Hdmi image  
HDMI audio  
Ethernet  
Wifi  
Bluetooth  
Keyboard and fn keys  
Focaltech touchpad  
Display brightness adjustment  
Camera  
Ac adapter  
Battery management  
App store  
iCloud, Facetime, iMessege, iTunes  

Non-working (not working):  
Nvidia 940M (disabled)  
Realtek usb2.0 crw card reader  
   
   
sources (google it):  
ASUS X555LB-NS51 "HacBook Pro" - Show your Hackintosh - osx86.net  
[Guide] Patching LAPTOP DSDT/SSDTs | tonymacx86.com  
[Guide] Laptop backlight control using AppleBacklightFixup.kext | tonymacx86.com  
[Guide] Native Power Management for Laptops | tonymacx86.com  
AppleHDA Realtek Audio [Guide] | tonymacx86.com applealc-vit9696  
Quick Guide to Generate a SSDT for CPU Power Management | tonymacx86.com  
Intel Framebuffer patching using WhateverGreen - Lilu and plugins - InsanelyMac Forum  
An iDiot's Guide To Lilu and its Plug-ins | tonymacx86.com  
