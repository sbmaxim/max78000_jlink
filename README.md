# J-Link Flash Driver for MAX78000 (Cortex-M4)
Provides J-Link and Ozone support for the MAX78000
# Installation
1. Find your J-Link (typically C:\Program Files (x86)\SEGGER\JLink) or Ozone (C:\Program Files\SEGGER\Ozone) installation directory.
2. Edit JLinkDevices.xml on your computer and add the contents of [this file](JLinkDevices.xml) within the <Database> node.
3. Copy [MAX78000.FLM](cs/MAX78000%20Release/MAX78000.FLM) to Devices\Maxim\MAX78000 which is a sub-directory that you will need to create beneath the JLink/Ozone directory.
 
