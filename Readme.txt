This repository contains firmware for download to Ciseco radio devices to configure the device for a specific function.
Please look in the folder for your device.

To download select the firmware you are interested to view the binary file and then (depending on your browser) press the RAW button (upper right hand of the text) or right click on the raw button and select 'save link as'.
You can download the files for all devices by clicking on the "Zip" link

For Raspberry Pi/ Linux users: the move to git hub has change the line endings so you will need to run (for example)
awk 'BEGIN {RS="\n";ORS="\r\n"} {print $0}' llapThermistor-V0.56-24MHz.bin > llapThermistor-V0.56-24MHz-ok.bin
before uploading - otherwise you will get errors when uploading.


Release notes can be found at the OpenMicros site
http://openmicros.org/index.php/articles/84-xrf-basics/224-firmware-release-notes

