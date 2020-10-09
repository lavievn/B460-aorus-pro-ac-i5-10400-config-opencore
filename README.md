# B460proac
hackintosh B460 Aorus pro ac 
i5 10400
Gigabyte Aourus nvme 256Gb
Intel DC SSD sata 4500S 480Gb
WD black 1Tb HDD
Intel ethernet V225-v Gbe
onboard iGPU Intel HD630
___________________________________
worked iServices as iMusic, Apple store 
reset macOS so it can build the interfaces fresh, open terminal and run the following
"
sudo rm /Library/Preferences/SystemConfiguration/NetworkInterfaces.plist
sudo rm /Library/Preferences/SystemConfiguration/preferences.plist
"
and make sure got "one" enthernet with "en0" for iMessage and facetime.
change audio device for front/back audio
