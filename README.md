ZombieBrowserPack
=================

Firefox, Chrome, Safari browser extensions, Rails control server, meterpreter scripts, SET plugin, Zombie browsers

## Zombie browser pack
Copyright (C) 2012  Zoltan Balazs

This pack is a fully functional malicious browser extension pack, created for educational and testing purposes.
Please don't use them for malicious purposes or without proper permissions.

Against the dark side (a.k.a blach-hat usage), the extensions have been uploaded to antivirus vendors and virustotal, and contain scheduled pop-ups to inform the users about the extension.

What you can find in this pack:

## Full
The "full/client" directory contains the source code and build instructions to create the Firefox, Chrome and Safari browser extensions. 
The "full/server" directory contains the source code for the rails server side code, which can be used to control the clients. 

## Lite
The "lite/client" directory contains the source code and build instructions to create the Firefox, Chrome and Safari browser extensions, lite edition, which has limited instructions set and a lightweight server side protocol. 
The "lite/server" directory contains the source code for the rails server side code, which can be used to control the clients. The static files can be used to control the clients, and if you want to receive the passwords and cookies from the clients, you need PHP as well. 

## Meterpreter
The "meterpreter_autorun/firefox" direcotry contains the meterpreter autorun scripts to install the extensions into firefox.
The "meterpreter_autorun/chrome" direcotry contains the meterpreter autorun scripts to install the extensions into chrome.

## SET
The "set_plugin" directory contains the SET plugin to social engineered install the Firefox extension into the victim Firefox browser.

The setup_servername.sh purpose is to mass change the files which have the server name in it. 
### Usage
./setup_servername.sh <<Your server name or IP address here>> 
