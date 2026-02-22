<img src="https://github.com/voltcraftmakes/td-m11/blob/main/Programming/SWD/J-link%20connect%20to%20HBM32G003%20SWD.jpg" width=200>
To connect SWD To the Honor MCU a segger J-link is used.

[SWD breakout board on Amazon (treedix) $10 for 2](https://www.amazon.com/Treedix-Breakout-Converter-Connector-Flexible/dp/B09DKDG7XN)  
[Segger J-link edu Mini $70](https://www.segger.com/products/debug-probes/j-link/models/j-link-edu-mini/)  

two flash images saved from the MCU per the memory map  
SaveBin c:\temp\flash0x41000000.bin 0x41000000 0xffff  //is 65535 bytes  
SaveBin c:\temp\flash0x41010000.bin 0x41010000 0xcfff //is 53247 bytes  



