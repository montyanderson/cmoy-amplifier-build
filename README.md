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
		<td><img src="http://uk.farnell.com/productimages/standard/en_GB/42268235.jpg">
		</td>
		<td><a href="http://uk.farnell.com/texas-instruments/opa2134pa/op-amp-dual-audio-fet-i-p-2134/dp/1097574?ost=opa2134pa&selectedCategoryId=&categoryNameResp=All%2BCategories&searchView=table&iscrfnonsku=false">TEXAS INSTRUMENTS  OPA2134PA.  Audio Power Amplifier, 2 Channel, ± 2.5V to ± 18V, DIP, 8 Pins</a>
		</td>
		<td>£2.47</td>
	</tr>
</table>

### 0.1uF Signal Capacitor (x2)

<table>
	<tr>
		<td><img src="http://uk.farnell.com/productimages/standard/en_GB/1005948-40.jpg"></td>
		<td><a href="http://uk.farnell.com/wima/mks2d031001a00kssd/cap-film-pet-100nf-100v-rad/dp/1006031">WIMA  MKS2D031001A00KSSD  Film Capacitor, MKS2 Series, 0.1 µF, ± 10%, PET (Polyester), 100 V</a></td>
		<td>£0.26</td>
	</tr>
</table>

### 220uF Power Supply Capacitor (x2)

<!---<table>
	<tr>
		<td><img src="http://uk.farnell.com/productimages/standard/en_GB/1848467-40.jpg"></td>
		<td><a href="http://uk.farnell.com/panasonic-electronic-components/eeufm1e221/cap-alu-elec-220uf-25v-rad/dp/1219468">PANASONIC ELECTRONIC COMPONENTS  EEU-FM1E221  Electrolytic Capacitor, FM Series, 220 µF, ± 20%, 25 V, 8 mm, Radial Leaded</a></td>
		<td>£0.39</td>
	</tr>
</table>-->

<table>
	<tr>
		<td><img src="http://uk.farnell.com/productimages/standard/en_GB/1848467-40.jpg"></td>
		<td><a href="http://uk.farnell.com/panasonic-electronic-components/eeufr1e681b/cap-alu-elec-680uf-25v-rad/dp/1800652">PANASONIC ELECTRONIC COMPONENTS  EEUFR1E681B  Electrolytic Capacitor, FR Series, 680 µF, ± 20%, 25 V, 10 mm, Radial Leaded</a></td>
		<td>£0.35</td>
	</tr>
</table>

Note that this is a **680uF cap, not a 220uF**. The higher capacitance (680uF vs 220uF) should allow for better bass handling, apparently.

The ['tweaks' part of the wiki](https://tangentsoft.net/audio/cmoy/tweaks.html), says:

> The caps’ values will change the way the amp performs. For the power caps, 220 µF is adequate, but bigger ones will provide a bigger current reserve, which can be useful in handling high instantaneous loads, like big drum hits. I’ve tried 470 µF caps in my CMoy amps before, and it does improve the bass handling significantly and they’re not all that much bigger than 220s.
