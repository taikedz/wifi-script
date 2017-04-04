# wifi for nmcli

Little script for managing wifi connections from the command line. Works especially well when your graphical tool doesn't seem to connect your wifi device to an access point you know is in range.

Usage:

	# Activate wifi
	wifi start

	# Stop wifi
	wifi stop
	
	# List access points in range
	wifi list

	# Connect to an access point. Password optional for previously connected access points.
	wifi connect AP_NAME [PASSWORD]

