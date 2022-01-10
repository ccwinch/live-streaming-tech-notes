## Problem Solving

In general, try to narrow down and eventually isolate the cause of the problem. If there is a problem with one or two cameras and you can't fix it before the service starts, you may be able to make do with the remaining cameras.

Remember the all-important line from "The IT Crowd" TV series: "Have you tried turning it off and back on again?".

If you get stuck, try asking on the "CCW Stream Team" WhatsApp group or see if there's someone around in church who can help.

The following problems are organised by problem symptoms, each with possible explanations and fixes. If you find a problem not listed here, please tell others about it so it can be added.

## ATEM switcher is powered off ("no lights")

This is often caused by the power cable coming loose when the switcher is slid out of the rack for operation. Reach over the back of the switcher and plug the power cable back in on the right hand side.

## The multiview monitor is black

Check the monitor power and display cables are securely plugged in at both ends.

## The camera controller is powered off ("no lights")

Check the power cable hasn't come loose.

## The streaming PC display is black

Check the display power and display cables are securely plugged in at both ends.

## The encoder is powered off ("no lights")

The encoder (the topmost unit in the streaming rack) is powered by a lead inside the back of the streaming rack which may become disconnected. Ensure the mains lead is plugged in at both ends.

## The video of a camera does not appear on the multiview display

This may be because the camera has not been powered on. Use the camera controller to power all the cameras off and back on.

To see if the camera is powered on, double click the relevant camera icon on the streaming PC desktop. If you see a picture from the camera, it is powered on and the problem may be that the SDI (video) cable is not properly connected to the camera (or to the back of the rack or to the back of the ATEM switcher). Disconnect and reconnect each plug in turn to ensure it is properly connected.

## A camera cannot be controlled by the camera controller

This may be because the power-over-ethernet (PoE) cable has been plugged into the wrong socket on the affected camera. Make sure the cable is plugged into the left-hand socket. When re-plugging PoE cables, it is best to power all the cameras down first and power them back up afterwards.

## The camera controller fails to operate the cameras

The camera controller may still be in menu mode, in which case the "menu" button will be lit. Press the menu button to exit menu mode.

Alternatively, the controller may be operating a group of cameras other than group 1. You need to select group 1, thus:

* Press "menu" and then "8"
* Select "group" by turning then pressing the F1 dial
* Select "group select" by turning then pressing the F2 dial
* (I presume) Press "1" to select group 1.

Alternatively, it has been known for the camera controller to reset itself to factory defaults.
Try power-cycling the camera controller to see if this fixes the problem. If not, you may need to go to the setup menu and re-enter the IP address of each of the cameras: 192.168.0.181-184 (for cameras 1-4). The cameras also need to be set to "network" connection rather than "serial" (_find out how to do this_). When entering an IP address, press F2 to select each "dotted decimal" number of the IP address in turn and turn F2 to change the current number. Refer to "Changing the camera numbers" on page 34 of the *basic* manual for the camera controller (available under [Hardware](../hardware.md)) for how to set camera IP addresses.

## The "go live" icon is greyed out on YouTube

This may be due to the stream in question having already been used, even if only briefly. You
need to create a fresh stream. See [Scheduling services](./scheduling.md) for instructions.

## The live stream does not appear in the preview on YouTube

This may be because the video encoder in the rack is not yet in streaming mode (the "streaming" button needs to be lit in red). Press the streaming button on the video encoder to start streaming. Note: this isn't usually necessary, so be patient while YouTube connects to the stream as this can take up to 20-30 seconds.

## The live stream does not appear on Online Church even though it is visible on YouTube

This may be because the current service on Online Church has the wrong link to YouTube. Use the admin area of the Online Church web site, click on "services" on the left hand side, then edit the content of the current service to check the YouTube link. On the YouTube window, click "preview" to see the YouTube link for the stream. If the link is wrong on Online Church, copy the correct link in place and click "save".

## The internet is not accessible from the live streaming PC

Ensure the AV desk PC is switched on (it doesn't need to be logged in). Also ensure that the
network router mains switch is turned on - this is next to the AV desk mains switch (on the wall, low down, at the right hand side of the sound desk).

Alternatively, the antivirus/firewall software on the streaming PC may be out of date. Temporarily disable the antivirus/firewall from the network settings to work around this.

## Poor sound quality on the live stream

Sometimes the host or a member of the online congregation will point out that the sound is
poor or that there is a specific problem with the sound. Check the sound level on the "live" panel of the multiview monitor. If it seems too low, check with the sound desk operator that the sound desk is correctly set up. If it's still too low, you can boost the volume by using
the ATEM switcher software on the live streaming PC. In the audio tab there is a master volume slider and a xlr slider which can be increased.

## Incorrect title and/or bible reference showing on Online Church

Edit the current service on Church Online (see [Scheduling Services](./scheduling.md)) to correct the mistake. The bible reference is probably on the service notes which are sent out ahead of time and which are usually made available in printed form on the live streaming desk.