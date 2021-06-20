I'm not trained to design this stuff, so use it at your own risk.
It works for me, it may not work for you.  73 de w8tam

Build notes for Loop Amplifier:

If you're not concerned about the front end of the GALI-74s, you
can skip placing the relays and just short the loop connection
through.

The values for R2/R3 are adjustable. I'm using 53.6ohm, but 51ohm
is close enough. Look at the GALI-74 datasheet to figure out what
resistor you need, for what voltage your U1 regulator is. I went
with 9v, which means 50'ish ohms to get the voltage right.

My goal is to use 75 ohm feedline, so I put in the 1.5:1 balun T1
using a Fair-Rite 2873000202 turns are marked on the board. Short
past it if you want to use 50ohms. I haven't tried that.

All capacitors should be rated higher than max voltage. I went with
25v and 35v to have plenty of headroom.

Match R1 & R5 and R6 & R7. Values aren't critical, but matching is.
Pick two that are very close in value.

Physical contruction of the loop:

I designed this board to fit into a Carlon E983FR-CAR Type T Conduit
Body.

I used 10' of 3/4" Pex-Al-Pex, and used some heatshrink to fill the
gap between the OD of the 3/4" Pex-Al-Pex and the ID of a 1" stub
of PVC water pipe. The 1" PVC fits into the Carlon box end. I froze
the Pex-Al-Pex with heatshrink on it, and hit the PVC with a heat
gun and they slid together nicely, then have a pressure fit. I don't
trust this to be water tight, so I am going to weather seal it. The
whole thing will get painted with UV protectant paint.

Bias Tee with PTT bypass:

I'm still working on this circuit, but I'm pretty close.

The idea will be that when powered up, it will use 6v PTT signal
(from my W2IHY) to keep the relay closed providing 13.8v bias voltage
on the feedline to the loop. When I trip PTT, it will remove the
bias voltage, causing the loop to ground itsself when I transmit.

This bias tee board will be designed to fit many needs, 50 or 75
ohms input/output, and can have a PTT connection or not. I'm
designing it to fit into a Hammond 1455C801.


I'm not trained to design this stuff, so use it at your own risk.
73 de w8tam
