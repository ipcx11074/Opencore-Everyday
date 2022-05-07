# Opencore-x1 Carbon Gen2 2014 (20A7)
EFI Hackintosh Thinkpad X1 Carbon Gen 2 2014 (20A7)

Spec:
Hasswell with intel HD 4400
Screen 1080p-1440p
Wifi AC7260 intel ( Only N )

-----------------------------------------------------------
            Wifi/Blu - OK
            HDMI/DP - OK
            Trackpad - OK
            iGPU - OK
            Jack 3.5 - OK
            Speaker - OK
            Mic - OK
            USB 3.0 - OK
-----------------------------------------------------------
Fix Audio
ALCPlugFIx is required to fix static noise on headphones, however Black-Dragon74 released a Swift version that doesn't require hda-verb, alc-verb or CodecCommander kext. the ALCPlugFix.zip is included in the Tools folder.

Installation:

Extract ALCPlugFix zip into desktop
Open terminal and type following commands one by one on the listed order:
sudo spctl --master-disable
sudo mkdir /usr/local/bin/
cd desktop/ALCPlugFix
sudo cp -R ALC3232.plist /usr/local/bin/
./install.sh
Now the installer will ask you to drop the ALC3232.plist into the terminal window.
Open a new finder window and press Shift + Cmd(Alt) + G to open a new go to folder: window
Now type: /usr/local/bin/
Drag the ALC3232.plist from the /usr/local/bin folder into the terminal window and press enter.
Done
--------------------------------------------------------------
