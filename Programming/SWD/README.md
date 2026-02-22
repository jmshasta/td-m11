<img src="https://github.com/voltcraftmakes/td-m11/blob/main/Programming/SWD/J-link%20connect%20to%20HBM32G003%20SWD.jpg" width=200>
To connect SWD To the Honor MCU a segger J-link is used. Startingn the radio in 'programming mode' seems to be the most reliable way to get the SWD to connect - to do so hold [+] and [-] keys on the side of the raidio while turning it on, thena green LED is turned on. It may time out after 10 seconds if no connection is established.

[SWD breakout board on Amazon (treedix) $10 for 2](https://www.amazon.com/Treedix-Breakout-Converter-Connector-Flexible/dp/B09DKDG7XN)  
[Segger J-link edu Mini $70](https://www.segger.com/products/debug-probes/j-link/models/j-link-edu-mini/)  

two flash images saved from the MCU per the memory map  
SaveBin c:\temp\flash0x41000000.bin 0x41000000 0xffff  //is 65535 bytes  
SaveBin c:\temp\flash0x41010000.bin 0x41010000 0x2cfff //is 184319 bytes
