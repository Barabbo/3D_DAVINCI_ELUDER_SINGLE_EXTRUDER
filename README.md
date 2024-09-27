MKS TinyBee Marlin Firmware (Beta) - "Boba"


Welcome to the beta release of the MKS TinyBee Marlin firmware, codenamed "Boba". 
This firmware is designed to bring enhanced functionality and stability to your MKS TinyBee 3D printer controller.
This release includes a *precompiled binary file* for *easy* installation without the need for manual compilation.

What's Included?!:
Precompiled Binary: A ready-to-flash .bin file for quick and hassle-free installation.
Source Code: The latest source code for the Marlin firmware, customized for the MKS TinyBee board.
Configuration Files: Default configuration files optimized for various 3D printer setups.

Installation Guide:
Prerequisites:
MKS TinyBee Board: Ensure you have the MKS TinyBee 3D printer controller.
Firmware Update Tool: Use a tool like ESPflasher etc, or PIO to compile.
MicroSD Card: A formatted microSD card to transfer the firmware to the printer. (personally i got a 512MB sd card)

Flashing the Firmware:
Download the Firmware: Get the precompiled binary file from the Releases section.
Transfer the File: Copy the desire firmware .bin and flash it, or compile from source

Alternative method (untested)
Download the Firmware: Get the precompiled binary file  from the Releases section.
Transfer the File: Copy the desire *firmware.bin* put it on sd root
Insert the SD Card: Insert the microSD card into the MKS TinyBee board.
Power On the Printer: Turn on the printer. The firmware will automatically update.
Restart the Printer: Once the update is complete, restart the printer to apply the changes.
Remember to deleter the file from root

OTA (SOON)

Featuresthe MKS Firmware Tool or similar to flash the firmware.
Support: Preconfigured support for CoreXY setups.
Improved Z-axis Control: Enhanced precision and stability for the Z-axis.
Automatic Bed Leveling: Compatibility with various bed leveling sensors.
Advanced Temperature Control: Improved thermal management for hotend and heated bed.

Known Issues:
Beta Status: This is a beta release and may contain bugs. Use it with caution in a non-production environment.
Compatibility: Some features may not be fully supported on all printer setups. Verify configuration before use.
Feedback and Contributions
We value your feedback! 
Please report any issues or suggestions via the Issues section.
Contributions to the firmware and documentation are welcome.
See the Contributing guidelines for more information.

License
This project is licensed under the GPL-3.0 License - see the LICENSE file for details, but if you ean from this
i think i need to ean

Acknowledgements
A big thank you to the Marlin community and everyone involved in the development and testing of this firmware.

Bye
-BoBa-

