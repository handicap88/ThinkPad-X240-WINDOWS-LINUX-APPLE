# ThinkPad-X240-WINDOWS-LINUX-APPLE
 
Updates:
- Looks that all works with new Clover, but you have to update manualy without specific drivers  
-Sinetek-rtsx.kext v2.2 (now SD card reader don't breaks transfer) 


What's needed:
- (old) Macbook or/and IPhone to verify (soon more screens)
- whitelist wifi (bios) configuration of Thinkpad
- three (separately) pandrives for installators 

MacOS Mojave Issues:
- touchPad (sometimes not loaded) 
- card reader stops working on second standby with card inserted (Jettison app doesn't help) 
- Audio (minijack) restarts on standby (look for alc_fix, will be updated soon) 
- only Wi-fi (on 3G) or Bluetooth at the same time (DW1820A) due to interferations (5G works fine) 
 
  <img src="http://brak.99e.pl/grafiki/60.jpg">
  <img src="http://brak.99e.pl/grafiki/61.jpg">
  <img src="http://brak.99e.pl/grafiki/62.jpg">
  <img src="http://brak.99e.pl/grafiki/63.jpg">

Steps:
1. Start with MacOS installer and format disk, create partitions (FAT for Windows or Linux, and HFS+ for MacOS)  // Dont't use APFS format
2. After reboot, check if Clover is run corectly (If no try install v.5099  and make sure that order is correct in UEFI) // Bios options as always 
3. Install Windows on specific partition, after format. 
4. Install Linux on specific partition, after format.  

Clover Configuration Based on:
https://github.com/jloisel/t440p
