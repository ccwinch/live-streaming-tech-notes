## Hardware

* Cameras - AW-HE40SWEJ
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

[![](./images/schematic.png)](./images/schematic.png)
(click image to view full size)

Notes:
* (Not shown) Audio input from the sound system feeds via [XLR connectors](https://en.wikipedia.org/wiki/XLR_connector) through the connection panel in the portable rack to the video switcher.
* (Not shown) The camera controller connects to the cameras over ethernet to camera IP addresses 192.168.0.181-184 (for cameras 1-4).
