# argonpi-40-case-fan-control

# What is this ?
	This script controls the fan speed in argon-one case for raspberry pi 4.
	For case info refer : https://www.argon40.com/argon-one-raspberry-pi-4-case.html

# Disclaimer:
	The script is downloaded from https://download.argon40.com/argon1.sh
	
# Installation
	To install argon-one case control do, 
	./argon1.sh

	Then, reboot device for the installation to take effect.

# To configure use command argonone-config
	
	* Make sure you have restarted the device once after installation *
	
	** example output **
	--------------------------------------
	Argon One Fan Speed Configuration Tool
	--------------------------------------
	WARNING: This will remove existing configuration.
	Press Y to continue:Y
	Thank you.

	Select fan mode:
  	1. Always on
  	2. Adjust to temperatures (55C, 60C, and 65C)
  	3. Customize behavior
  	4. Cancel
	NOTE: You can also edit /etc/argononed.conf directly
	Enter Number (1-4):1

	Fan always on.

# To uninstall utility use command argonone-uninstall
