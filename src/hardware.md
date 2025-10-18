## Hardware

* Camera 1 - Panasonic AW-UE40KEJ 4K PTZ
  - [manual](https://pro-av.panasonic.net/manual/pdf/AW-UE50_UE40P.PJ.E.EJ.ED_full(DVQP2618YA)_E.pdf)
* Cameras 2-4 - Panasonic AW-HE40SWEJ HD PTZ
  - [manual](https://pro-av.panasonic.net/manual/pdf/AW-HE40PE_Operations(SQW0456)_E.pdf)
* Cables ([SDI](https://en.wikipedia.org/wiki/Serial_digital_interface), Ethernet)
* Panasonic remote camera controller AW-RP50
  - [basic manual](https://pro-av.panasonic.net/manual/pdf/AW-RP50N(3TR006515FAA)_E.pdf)
  - [advanced manual](https://pro-av.panasonic.net/manual/pdf/AW-RP50N(3TR006602FAA)_E.pdf)
* Blackmagic ATEM TV Studio Pro 4K (video switcher)
  - [manual](https://documents.blackmagicdesign.com/uk/UserManuals/ATEM_Television_Studio_Switchers_Manual.pdf?_v=1594364410000)
  - [Blackmagic forum](https://forum.blackmagicdesign.com/)
* Datavideo NVS-34 streaming encoder
  - [manual](https://www.datavideo.com/us/file/download?id=3412)
* PC - for connecting to Facebook, etc.
* tp-link PoE+ switch TL-SL1218MP
  - [Overview of tp-link PoE](https://www.tp-link.com/uk/solution/poe/)
  - [TL-SL1218MP product description](https://www.tp-link.com/uk/business-networking/poe-switch/tl-sl1218mp/)
* Blackmagic video assist 7" 12G HDR (combined scope/monitor/recorder/viewfinder)
  - [Product description](https://www.blackmagicdesign.com/uk/products/blackmagicvideoassist)
  - [manual](https://documents.blackmagicdesign.com/UserManuals/BlackmagicVideoAssistManual.pdf)

### Schematic Diagram

The following diagram pre-dates the ABCDE refurbishment in 2025 and is now only an approximation of the set up.

[![](./images/schematic.png)](./images/schematic.png)
(click image to view full size)

Notes:
* (Not shown) Audio input from the sound system feeds via [XLR connectors](https://en.wikipedia.org/wiki/XLR_connector) to the video switcher.

### Blackmagic video assist 7" 12G HDR

The "scope" that's in the live streaming desk drawer can be used for setting the colour and white balance of cameras.

Disconnect the SDI cable connected to the aux output of the live streaming Blackmagic ATEM. Connect another SDI cable from aux output of the live streaming  ATEM to the SDI input of the scope, plug in and connect the power adapter, and power on.

To set the cameras up you need to select the vector scope on the Blackmagic Video Assist, and then black balance all the cameras first (close all the iris’s down) and then go through each camera ensuring that the dot on the vector scope is dead centre.

Then to white balance, put a white cloth on the stage and point all the cameras at that so nothing else is in shot (this is the only time it’s okay to use digital zoom!), and use the Auto White Balance (AWB) button on the camera controller. That should line up all the cameras and again, put the dot dead centre on the vector scope. If it doesn’t on some cameras that is where you’ll need to adjust the colour bias on each camera.

When you are done, please reconnect the original cable to the aux output of the ATEM.
