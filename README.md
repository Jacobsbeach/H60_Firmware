# H60_Firmware
Firmware for NAV_H60

In order for firmware to run properly connect device and download to Target through "Target" Menu or by pressing CTRL + T, L
Then build and run the solution while connected to device
In the run screen ensure the press run multiple times, it pauses through each compile option
once it runs for a few seconds it will pause again, at this point it is safe to stop the running

# Listener
In order to listen to all the tags a listener must be set up
After Listener Firmware is uploaded to device
  Connect device to Raspberry Pi via USB
  Connect to Raspberry Pi through SSH or use Raspberry Pi with monitor
  Open Terminal
  Enter Commands:
	  Minicom -D /dev/serial0
	  Press "Enter" Twice
	  lep 
	  Press "CTRL A"
	  Press "L"
    Type output name "Enter"
    
From here the output from the tags should be recorded in CSV format.
