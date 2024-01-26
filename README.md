<h1>KEF Kube-1 (MK1) Power Supply PCB Replica project</h1>
<p>I was repairing a severely corrosion damaged KEF Kube-1 (MK1) power supply PCB and after I got the board
working I figured it would be much nicer to get a completely new board made, and then just transplant the
components over to that.</p>

<p>Eventually I ended up figuring out all the components and ordering mostly new parts from Mouser, just
keeping the transformer, heatsinks, and various other bits.</p>

<h1>Disclaimer</h1>
<p>Working with high voltage electronics can be fatal. Everything you do or don't do with this information
and files provided here is at your own risk. Don't attempt to do this if you don't know what you're doing.
</p>
<p>You are reponsible for any mistakes made during your efforts, also if this involves a mistake on my part
in any of the information provided here.</p>

<h1>What's provided here</h1>
<ul>
  <li>PCB Gerber files so you can order your own PCBs</li>
  <li>1200 DPI scans of the original PCB with all components removed</li>
  <li>Bill Of Materials (BOM) - In case you want to identify a part and/or make an order for repair or building a replica PCB</li>
</ul>

<h1>Differences</h1>
<p>Any difference between the original and replica is noted here.</p>
<h2>PCB differences</h2>
<p>The replica PCB is almost 100% identical to the original PCB, however two sections are slightly changed to improve the design</p>
<ul>
  <li>D3 and D4 are schottky diodes clamping the voltage output to the preamplifier PCB to 15V. To double the maximum amperage 
      for this circuit, KEF had tacked on a second set of 15V schottky diodes to the bottom. This was quite an ugly fix I
      think, so I made a second set of pads in the replica PCB to make soldering the bottom side schottky diodes easier.
      I named these D3a/D3b and D4a/D4b on the silkscreen.</li>
  <li>The original PCB had a mistake where there were no room to fit C8 on the top side of the PCB, and since the original
      PCB was a single-sided PCB you couldn't just insert it from the bottom and solder it that way. Instead KEF tacked it
      onto neighboring pins. Again, quite ugly. So on the replica PCB C8 and R11 is rearranged somewhat to aid soldering.
      C8 is still meant to be soldered on the bottom side.</li>
</ul>
<h2>Differences in my own replica build</h2>
<ul>
  <li>If you watch the photos of my completed replica PCB, you can see that I made a new, slightly longer power cable to
      the amplifier, to make it easier to reassemble the unit. I just used some pre-crimped JST-VH wires, and didn't
      really think about the wire colors. Compared to the original, the red and yellow wires are swapped. This can
      lead to some confusion, so when disassembling your Kube-1, make a note of the order of the pins, so you don't
      accidentally reverse the polarity.</li>
  <li>I only use this subwoofer with 230 volts AC, so I cut the leads on the 230V/110V panel mounted selector switch,
      and didn't fit the J2 wire connector on the board. The switch position on the 110V option will short the two
      leads on J2, and it does nothing when the switch is set to 230V. So for my case I didn't bother adding it.</li>
</ul>

<h1>Errata</h1>
<ul>
  <li>Two instances of JP6 on the silk screen. The rightmost one should really say JP5, but it's not really important. It's just a jumper wire, so you can't get it wrong.</li>
</ul>

<h1>Feedback / Questions</h1>
<p>Just open a new issue if you have something to comment or ask. I might not be very active here, so it could take some time before I reply.</p>
