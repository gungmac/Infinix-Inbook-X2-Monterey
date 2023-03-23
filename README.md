# Infinix-Inbook-X2-Monterey
![Screen Shot 2023-03-21 at 08 53 05](https://user-images.githubusercontent.com/79616570/227265049-d3c4b6a7-cb7a-4728-9bf5-2e00d89a23fc.png)</br>
</br>
Spec :</br>
intel core i7 1065G7</br>
Intel Iris Plus Graphics</br>
RAM 8 GB</br>
SSD 512 GB</br>
Resolution 1920x1080 IPS Panel</br>
Audio & Mic Intel SST (Smart Sound Technology)</br>
</br>
What's work ?</br>
QE/CI Intel Iris Plus Graphics</br>
Brightness key (Fn + Pause & Fn + Scr Lk)</br>
USB Type A 2.0/3.0</br>
USB Type C 3.0</br>
Wifi & Bluetooth intel </br>
SYNA3602 Trackpad (need edit info.plist of VoodooI2CHID.kext)</br>
Internal Camera</br>
Batterey</br>
</br>
Not working :</br>
HDMI out </br>
USB type C to HDMI Out</br>
Audio & Mic Intel SST (solution use headphone/speaker bluetooth)</br>
</br>
Note for trackpad:</br>
under IOKITPersonalities</br>

    - rename VoodooI2CHIDSYNA3602Device to VoodooI2CHIDSYNA3602&Col2Device
    - rename IOClass from VoodooI2CHIDSYNA3602Device to VoodooI2CHIDSYNA3602&Col2Device

![336888707_925197885349654_7070543224991319842_n](https://user-images.githubusercontent.com/79616570/227270338-249a9ef1-2867-450e-89da-b1ad25f6725b.jpg)</br>

Thanks to </br>
Dortania Guide https://dortania.github.io/OpenCore-Install-Guide/ </br>
Olarila https://www.olarila.com/ </br>
Trackpad fix source https://www.tonymacx86.com/threads/voodooi2c-issues-syna3602.304029/page-2?fbclid=IwAR2FMLHH9iGUnz0gM5gzaM8xoxBfPFloVfFwfCD5JqL8ftWXUqvc7UI7_sY
