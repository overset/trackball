## Trackball Mezzanine PCBs

These are the mezzanine (daughter) PCBs that connect the <a href="https://www.adafruit.com/product/4600">Adafruit QT Py</a> (SAMD21) MCU, <a href="https://github.com/mrjohnk/PMW3389DM">MrJohnK PMW3389</a> optical sensor breakout (<a href="https://www.tindie.com/products/jkicklighter/pmw3389-motion-sensor/">available on Tindie as of 2022</a>), simple components for the haptic feedback motor and pads for capacitive pickup wiring. This PCB allows for easy mounting inside the case for most components as well as a ground plane to help with the capacitive pickup interference. These are simple 2-layer PCBs that made with KiCad6 and includes a few custom footprints/symbols for the haptic motor. These can easily be printed through OSHPark, JLCPCB, etc.

### Single Optical Sensor PCB

This mezzanine PCB supports a single optical sensor breakout and is good for a dedicated trackball or dedicated scrollball. This allows for a smaller case design, but made with using a 50mm or larger ball.

<table style="padding: 10px">
	<tr>
		<td width="33%"><img width="100%" src="./pictures/20221216-PCB-editor-v01-front.jpg"></td>
		<td width="33%"><img width="100%" src="./pictures/20221216-PCB-3D-v01-front.jpg"></td>
		<td width="33%"><img width="100%" src="./pictures/20221216-PCB-3D-v01-back.jpg"></td>
	</tr>
</table>

<table style="padding: 10px">
	<tr>
		<td width="33%"><img width="100%" src="./pictures/20221216-PCB-build-v01-front.jpg"></td>
		<td width="33%"><img width="100%" src="./pictures/20221216-PCB-build-v01-back.jpg"></td>
		<td width="33%"><img width="100%" src="./pictures/20221216-PCB-build-v01-side.jpg"></td>
	</tr>
</table>

### Dual Optical Sensor PCB

Currently working on another mezzanine PCB supporting dual optical sensor breakouts to support twist-to-scroll as well as normal tracking features. This will include slight increase in case size and complexity in assembly.

## Credits, Attribution and Inspiration

* <a href="https://github.com/monroewilliams/trackball">MonroeWilliams' Trackball</a> project
* <a href="https://github.com/jfedor2">jfedor2's multiple trackball</a> projects