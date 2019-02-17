# asus-x555lb-mojave-efi
hackintosh efi for asus x555lb, it have dsdt patch and kexts and clover config.
mac os 14.3 mojave works nice with this files. i got help from hackintosh forums and great peoples. 

english is not my native language, i explained everything at a turkish forum https://osxinfo.net/konu/basarili-kurulum-asus-k555lb-x555lb-macos-mojave.6197/
you can read that with google translate, you will understand the article. i updated something of setup in few weeks later. lilu and its addons are used in this github version.
ie: the things that needs ssdt patch are working with whatevergreen kext and intel framebuffer patcher config now. just 1 kext (weg) solves a lot of problem.

i have used rehabman's clover fork. it is outdated but works fine.

Sistem Özellikleri (specs) :
İşlemci: intel core i5 5200u broadwell
Ekran Kartı : intel hd5500 + nvidia 940m
Ekran: 1366*768 lcd
Ram: 12 GB (8+4) 1600Mhz
Ses: Realtek Alc233
ssd1: windows 10, ssd2: mojave
Ethernet: Realtek RTL8168/8111 PCI-E Gigabit
Wifi: azurewave aw-ce123h (14e4:43b1) wifi+bt card (replaced, the old mediatek card is sucks)

Çalışanlar(working things): 
Grafik hd5500 igpu,
Realtek alc233 ses,
---dahili hoparlör ve mikrofon çalışıyor, kulaklık çıkışında statik gürültü/cızırtı var.
Hdmi görüntü,
Hdmi ses,
Ethernet,
Wifi,
Bluetooth,
Klavye ve fn tuşları,
Focaltech touchpad,
Ekran parlaklık ayarı,
Kamera,
Ac adaptör,
Pil yönetimi,
App store,
iCloud, Facetime, iMessege, iTunes

Çalışmayanlar(not working):
Nvidia 940M (devre dışı-disabled)
Realtek usb2.0 crw kart okuyucu
 
 
sources (google it):
ASUS X555LB-NS51 "HacBook Pro" - Show your Hackintosh - osx86.net
[Guide] Patching LAPTOP DSDT/SSDTs | tonymacx86.com
[Guide] Laptop backlight control using AppleBacklightFixup.kext | tonymacx86.com
[Guide] Native Power Management for Laptops | tonymacx86.com
AppleHDA Realtek Audio [Guide] | tonymacx86.com applealc-vit9696
Quick Guide to Generate a SSDT for CPU Power Management | tonymacx86.com
Intel Framebuffer patching using WhateverGreen - Lilu and plugins - InsanelyMac Forum
An iDiot's Guide To Lilu and its Plug-ins | tonymacx86.com
