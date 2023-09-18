# AIO-Standard-Hammond-Faceplate
A faceplate that fits the AgOpenGPS All-in-One (AIO) Standard and Hammond 1455Q2201 plastic bezel. This faceplate contains no traces, its FR4 cut to the right dimensions with silkscreen.

This faceplate does not fit the AIO Micro, it only fits the AIO Standard.


# Pictures

The real life pictures shown are of v1.0, the gerber files are of v1.1. Between versions the silkscreen changed slightly. The title moved to the top of the faceplate where it is more visible. The AOG logo was incorporated into the title. The gerber previews are of v1.1.


<img src="https://github.com/WildBuckwheat/AIO-Standard-Hammond-Faceplate/blob/main/Images/Front_Mounted.jpg" width="550">
<img src="https://github.com/WildBuckwheat/AIO-Standard-Hammond-Faceplate/blob/main/Images/Front_Mounted2.jpg" width="550">
<img src="https://github.com/WildBuckwheat/AIO-Standard-Hammond-Faceplate/blob/main/Images/Front_Mounted3.jpg" width="550">
<img src="https://github.com/WildBuckwheat/AIO-Standard-Hammond-Faceplate/blob/main/Images/Back_Mounted.jpg" width="550">
<img src="https://github.com/WildBuckwheat/AIO-Standard-Hammond-Faceplate/blob/main/Images/Faceplate_Top_Gerber.JPG" width="550">
<img src="https://github.com/WildBuckwheat/AIO-Standard-Hammond-Faceplate/blob/main/Images/Faceplate_Bottom_Gerber.JPG" width="550">


# Features

The faceplate offers cutouts for the Ampseal housing, the RJ45 jack, and a GPS receiver. If you are using dual and/or radio you will need additional holes. The locations for the additional holes are marked with silkscreen and with a via. The via is intended to act as a drill guide, similar to a center-punch mark.

The LED areas of the board have oval windows. These windows are devoid of silkscreen and soldermask, leaving the bare FR4 fiberglass, which is translucent. The LEDs are able to shine through these windows, albeit dimly. The LEDs are well visible in low light conditions, and are visible in daylight if you shade them with your hand. The LEDs may or may not be visible in bright daylight conditions.

The back of the faceplate offers a small area to write your firmware version or other notes in permanent marker.

The faceplate works with all versions of the AIO Standard to date (latest version to date is v4.2). The faceplate may work with later versions as well.


# Screws

The ampseal connector uses 4x M2.5 x 8mm self tapping screws. Aliexpress is a good source of button head cap self tapping screws with these dimensions.

The hammond box uses 4x #6-3/8" screws to attach the faceplate. Countersunk screws are provided with the Hammond box. Sadly it is not possible for a gerber file to contain a countersunk hole, and most PCB manufacturers do not offer countersinking capability. You can use the provided screws without modification, you can countersink the hole yourself, or you can use screws with a different head.


# Ordering

Upload the gerber files to your board manufacturer and double check that the selected PCB is 1.6mm thickness. 1.6mm is the default thickness of most board manufacturers. If ordering from JLCPCB, you should set "Remove Order Number" to "Specify a Location." That will place the order number on the JLCJLCJLCJLC placeholder.

# Special Thanks

Special thanks to Andy Fahnestock for ordering the first batch and for providing the images and feedback. I do not have an AIO Standard to test with, Andy took all the risk and ordered the first ever batch of v1.0. Another special thanks for Vili for providing the logo and font used in the silkscreen. And of course a special thanks to Brian Tee and everyone else involved for creating AgOpenGPS and the All-in-One boards.

# License

This project is licensed CERN-OHL-S V2.0. View the LICENSE.MD for further details.