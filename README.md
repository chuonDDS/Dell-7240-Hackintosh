# Dell-7240-Hackintosh
this is the dell 7240 Hackintosh that I test and use as my HackbookAir
Please Note that I have replace wifi card to DW1550 From IntelWifi It work All Continuity and HandOff except Auto Unlock and Universal clipboard because the chipset of Bluetooth was not fully support like real Mac. If we need to use intelWifi Card go and check this website https://openintelwireless.github.io .
In order to use iMessage we can refer to the guide https://dortania.github.io/OpenCore-Post-Install/universal/iservices.html#using-gensmbios 
** Bios Setting Leave it to default only diable secure Boot and enable Legacy boot to remove Boot Glitch.Headphone Jack Fix : Only in Big Sur < We need to create a folder in /usr/local/ named ( bin ) at first > For Catalina we must diable csrutil on Recovery Boot Partition ( No need to create any folder) .
  the downsite is battery drain with my i7 CPU at performance we can config CPU type in config.plist to null or 0 for auto and 1537 value for core i5 version create a new cpufrienddataprovider.kext from this site https://dortania.github.io/OpenCore-Post-Install/universal/pm.html .



