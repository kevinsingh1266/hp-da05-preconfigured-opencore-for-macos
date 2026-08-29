This is a GUIDE on how to get macOS Ventura 13 on your HP-da05xxxx device.

Chapter 1: Retrieving Files

1. Go to my Github Repo of my profile, The Repo is titled "hp-da05-preconfigured-opencore-for-macos".
2. Look at the right side of the repo to the Releases tab. It should be titled "EFI folder & Recovery image for OpenCore ver 0.8.6 for HP-da05xxxx series" as of 29/08/26. 
3. Download each zipped file named OpenCore-HPda05xxx.zip and Ventura-Recovery.zip

Chapter 2: Building the recovery usb.

1. Once you have downloaded each file, unzip the compressed .zip files and you will see two folders, EFI and com.apple.recovery.boot.
2. Place each folder in your USB and it should have com.apple.recovery.boot as the first folder and EFI as the second one.
3. Once you have copied each folder, you can delete the .zips on your computer if you want, but leave the USB. 
4. Safely eject your USB and insert it into your laptop and or pc. 

Chapter 3: Booting

1. Power on your pc/laptop and spam repeat Esc key to see the menu that lists the shortcuts.
2. Press F10 and disable Secure boot normally under Boot Options. it might reenable itself but check again to be sure. 
3. Once it is disabled, boot into the USB by restarting your pc/laptop and spamming Esc again, then press F9 and select USB disk or anything with USB if it doesnt say USB drive. 
4. OpenCore should boot and you should press Space to view the items and boot into the one called "Recovery (dmg)" or something like that. 

Chapter 4: macOS

1. Once you get into macOS recovery menu, press the Disk Utility button and format your drive or partition as APFS (the apple partition format, apple version of NTFS.)
2. Once it formatted, click out of the menu and press "Install macOS Ventura" and agree to the terms and conditions and select your new APFS partition to install macOS. 
3. Agree to the ToCs again and press install. You might need a ethernet cable incase your pc does not have a supported wifi card. 
4. It will install but it will take a long time. 
5. Once it finally installs, continue with the setup. Dont sign in your apple id if prompted as it could put your apple account at jeopardy.

Thanks for reading my guide! good luck with installing macos.
