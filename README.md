# GA-H61M-S2PV I7-3770k hackintosh  
Hackintosh efi for GIGABYTE GA-H61M-S2PV, i7-3770k, hd4000 and 8gb ddr3  
  
  
My hackintosh efi setup with OpenCore release 1.0.0, boots MacOS big sur without any problem.  
Parts:  
CPU: Intel core i7-3770k  
GPU: Intel HD4000  
Mobo: Gigabyte ga-h61m-s2pv rev2.2  
RAM: Adata XPG 4gb ddr3 1600mhz *2  
HDD: WD 1tb Black enterprise  
Audio: Realtek® ALC887  
Ethernet: Realtek RTL8111  
  
What's working:  
-Everything I've tested, even sleep works
  
What's not tested:  
-Apple DRM content  
-Apple iMessage etc.  
  
What's not working:  
-Audio (Will probably work with AppleALC.kext, but i do not have any option for audio output so i have not added kext for it.)  
  
Remember that if you want to use this config, you'll probably need to create new USBToolBox usb map for your setup if you are not using same parts as me, also look out for SSDT-PM as it was made for i7-3770k especially and eventually you should not be using it through installation.
