# Hackintosh/macOS Mojave setup for Asus X555LB
Hackintosh efi for asus x555lb, it has dsdt patch and kexts and clover config.  
macOS 14.3 Mojave runs well with these configurations. I got some help on hackintosh forums and from great people.

I explained everything on a Turkish forum since Turkish is my main language:  [That thread can be found here](https://osxinfo.net/konu/basarili-kurulum-asus-k555lb-x555lb-macos-mojave.6197/)
It must be easy to understand that Turkish thread by just translating it through Google Translate. I updated some of the settings a few weeks ago. lilu and its addons are included on this GitHub version.
Stuff requiring ssdt patch works with whatevergreen kext and intel framebuffer patcher config now. Only 1 kext (weg) solves a lot of problem.  

Though it is outdated, I used rehabman's clover since it works well. All the kexts can be found inside /e/c/k/other folder. It is not necessary to install them to s/l/e or l/e.

#### System Properties (specs):
* Processor: intel core i5 5200u broadwell  
* Display Card: intel hd5500 + nvidia 940m  
* Display: 1366 * 768 lcd  
* Ram: 12 GB (8 + 4) 1600Mhz  
* Sound: Realtek Alc233  
* ssd1: windows 10, ssd2: mojave  
* Ethernet: Realtek RTL8168 / 8111 PCI-E Gigabit  
* Wifi: AzureWave AW-CE123H (14E4: 43B1) WIFI + BT card (replaced, the old mediatek card sucks)  
  
#### What works?
* Graphics HD5500 IGPU 
* Realtek alc233 sound  
    * Built-in speaker and microphone is working, there is static noise / squeal at headphone output  
* Hdmi image  
* HDMI audio  
* Ethernet  
* Wifi  
* Bluetooth  
* Keyboard and fn keys  
* Focaltech touchpad  
* Display brightness adjustment  
* Camera  
* Ac adapter  
* Battery management  
* App store  
* iCloud, Facetime, iMessege, iTunes  

#### What does not work?
* Nvidia 940M (disabled)  
* Realtek usb2.0 crw card reader  
   
   
##### Sources (search each title on Google):

ASUS X555LB-NS51 "HacBook Pro" - Show your Hackintosh - osx86.net  
[Guide] Patching LAPTOP DSDT/SSDTs | tonymacx86.com  
[Guide] Laptop backlight control using AppleBacklightFixup.kext | tonymacx86.com  
[Guide] Native Power Management for Laptops | tonymacx86.com  
AppleHDA Realtek Audio [Guide] | tonymacx86.com applealc-vit9696  
Quick Guide to Generate a SSDT for CPU Power Management | tonymacx86.com  
Intel Framebuffer patching using WhateverGreen - Lilu and plugins - InsanelyMac Forum  
An iDiot's Guide To Lilu and its Plug-ins | tonymacx86.com  
