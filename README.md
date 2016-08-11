# cmoy-amplifier-build

After being a musician the majority of my life, I felt it was time to attempt my first audio electronics projects (I've made a lot of general electronics projects).

I needed to build a headphone amplifier, and thus I found the CMoy amplifier. (aka OPA2132/OPA2134 IC)

After a very brief google search, I found the brilliant [Tangentsoft's 'How to Build the CMoy Pocket Amplifier'](https://tangentsoft.net/audio/cmoy/), a brilliant wiki, packed with information.

They neatly state:

> Chu Moy designed a very popular headphone amplifier that’s easy to build, and it can be built small enough to fit in a pocket, power supply and all. It’s powerful enough to drive very inefficient headphones to thunderous volumes from even weak sources, and it sounds excellent considering that you can build a bare-bones CMoy amp for just US$20, and a pretty nice amp for under $50. Considering that the cheapest of the worthy commercial amps is $100 and most of them are in the $200+ range, this is a very worthwhile cost difference.

## Schematic

[![Schematic](./schematic.png)](https://tangentsoft.net/audio/cmoy/misc/cmoy-tangent-sch.pdf)

## Parts

Assuming you have resistors already, you need:

* 2 9v batteries or an isolated 18v power source
* 2x 220uF Capacitors
* 10k Logarithmic pot
* OPA2132PA or OPA2134PA
* 2x 0.1uF Capacitor

### OpAmp

<table>
	<tr>
		<td>
![](http://uk.farnell.com/productimages/standard/en_GB/42268235.jpg)
		</td>
		<td>
[TEXAS INSTRUMENTS  OPA2134PA.  Audio Power Amplifier, 2 Channel, ± 2.5V to ± 18V, DIP, 8 Pins](http://uk.farnell.com/texas-instruments/opa2134pa/op-amp-dual-audio-fet-i-p-2134/dp/1097574?ost=opa2134pa&selectedCategoryId=&categoryNameResp=All%2BCategories&searchView=table&iscrfnonsku=false)
		</td>
		<td>£2.47</td>
	</tr>
</table>

### 0.1uF Signal Capacitor (x2)

<table>
	<tr>
		<td>
![](http://uk.farnell.com/productimages/standard/en_GB/1005948-40.jpg)
		</td>
		<td>
[WIMA  MKS2D031001A00KSSD  Film Capacitor, MKS2 Series, 0.1 µF, ± 10%, PET (Polyester), 100 V](http://uk.farnell.com/wima/mks2d031001a00kssd/cap-film-pet-100nf-100v-rad/dp/1006031)
		</td>
		<td>£0.26</td>
	</tr>
</table>

### 220uF Power Supply Capacitor (x2)

<table>
	<tr>
		<td>
![](http://uk.farnell.com/productimages/standard/en_GB/1848467-40.jpg)
		</td>
		<td>
[PANASONIC ELECTRONIC COMPONENTS  EEU-FM1E221  Electrolytic Capacitor, FM Series, 220 µF, ± 20%, 25 V, 8 mm, Radial Leaded](http://uk.farnell.com/panasonic-electronic-components/eeufm1e221/cap-alu-elec-220uf-25v-rad/dp/1219468)
		</td>
		<td>£0.39</td>
	</tr>
</table>
