# mouse-encoder-pcb
NOTE: The pcb has been ordered, but not tested yet.

Simple standalone mouse-wheel encoder pcb, including a noise filter, but incredibly, no LED.
Designed to be VIK-friendly, and fits ALPS and TTC (and Kailh) encoders (e.g. ALPS EC10E1260502).

## Noise filter
I'd initially struggled with the noise filter on the Ultrafalcon - still getting skipped readings, doubles - but some reading indicated that I needed to change up the resistor values to meet 3.3v spec.  This is the same Bourns-recommended pattern.  

Turns out there are three camps in the noise filter arena... 
1. Only do it in software.
2. Only do it in hardware.
3. Mix of both.
... and if you are in one camp you're 'wrong' to the others.  Anyways, let's give this a shot.

## In use
Note the direction of the modeled FFC cable here...

![Cutaway](/images/cutaway.png)

# PCB render
![Render-bottom](/images/render-bottom.png)
![Render-top](/images/render-top.png)

# Usage example
![Usage1](/images/usage-example.png)
![Usage2](/images/usage-example-top.png)

# PCB overview
![Schematic](/images/schematic.png)
![PCB Layout](/images/pcb-layout.png)