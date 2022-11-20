# PVS-69 Gen3 FOXTROT

## Changes from ECHO to FOXTROT

The PVS-69 Gen3 FOXTROT is currently in an unprinted BETA. Take that as a word of caution. Please read all the changes.

(unprinted BETA) FOXTROT changes:
Expanded inner bore for use with V780 display.

Condensed overall pod length but moved the display bore deeper in the pod.

Opened up the area where the cam connector goes to accommodate more cams.

Added area for the OSD cable to come out the front.

Added CS mount quick change system. Still usable with the classic caps (Called 'NE3 Stock Sensor Cap' in .step)

Added holes to screw the sensor down for the quick change.

New Gen4 Bridge (front load) does not require brass tubing however, should be able to accept it.

Both bridges now support the use of M3 bolts to individually adjust pod tightness.

Both bridges have a push-to overcome-latch to stow the tubes to the side.

Battery bridge has been slimmed down slightly more to accomadate narrower IPD, might need some tweaking.

As for the CS Mount Lens deal, basically, you can either use the NE3 Stock Lens (or XENOCAM Varifocus lens) *or* you can use the CS Mount Lens with the 'CS Mount Lens Assembly' (in the .step). [See this wiki page for links to the different lenses.](https://github.com/knack-69/PVS-69/wiki/Current-Lens-Comparison). If you aren't planning on using the CS mount lens, don't print the 'CS Mount Lens Assembly' items. ezpz

## (EVERYTHING BELOW THIS IS OUTDATED AS OF 11/19 10:44PM EST)

## Bill of Materials 

### This design requires the following printed components: 

1x [Dovetail](https://github.com/knack-69/PVS-69/blob/main/Gen3%20ECHO/STL/Dovetail.stl)

1x Bridge Body. In this design, there are 3 Bridge options:
1. [Gen3 Bridge](https://github.com/knack-69/PVS-69/blob/main/Gen3%20ECHO/STL/Gen3%20bridge%20body.stl) is the same bridge as older versions, with an internal battery compartment.
2. [Gen4 Bridge Front-Load](https://github.com/knack-69/PVS-69/blob/main/Gen3%20ECHO/STL/Gen4%20bridge%20front-load%20body.stl) is a newer, sleeker bridge that does *not* have an internal battery compartment. The front-loading version allows the user to more easily build the internals of the bridge and then load it into the front (away from your face).
3. [Gen4 Bridge Back-Load](https://github.com/knack-69/PVS-69/blob/main/Gen3%20ECHO/STL/Gen4%20bridge%20back-load%20body.stl) is the same as above, except it is accessed from the back (towards your face).

1x Bridge Backplate, which will depend on the Bridge body you choose

2x [Sensor Caps](https://github.com/knack-69/PVS-69/blob/main/Gen3%20ECHO/STL/RunCam%20sensor%20cap.stl)

2x TIPs (Tube Interface Pieces) - please note there are [+0°](https://github.com/knack-69/PVS-69/blob/main/Gen3%20ECHO/STL/%2B0%20TIP.stl) and [+2°](https://github.com/knack-69/PVS-69/tree/main/Gen3%20ECHO/STL) versions. 
    The +2° version gives a wider FOV

2x [Ambi Tubes](https://github.com/knack-69/PVS-69/blob/main/Gen3%20ECHO/STL/Ambi%20tube%20-%20ECHO%20.stl)

1x [Battery Cap](https://github.com/knack-69/PVS-69/blob/main/Gen3%20ECHO/STL/Battery%20cap.stl) (Only needed if using Gen3 Bridge)

2x [Collars](https://github.com/knack-69/PVS-69/blob/main/Gen3%20ECHO/STL/Collar.stl)


### This design requires the following physical components: (*This list is still under development*)

---

#### Gen3 Bridge (Internal and External Battery)

1x [3-Position Rotary Switch](https://amzn.to/3TspGUS).

11x [M5x8 Bolts](https://amzn.to/3EyraZz)

11x [M5x5.8 Heat-set Inserts](https://amzn.to/3E0fzRt)

2x [RunCam Night Eagle 3](https://amzn.to/3Epdyhh)

2x V760A-5 or V760A-3 displays. These can be found on Ebay or AliExpress, expect a month for shipping.

1x [300x8mm OD of Brass Tubing](https://amzn.to/3E3g5Oq) (you will only use 100mm to make 2x 45-46mm lengths)

1x [5.5x2.1mm DC Female Jack](https://amzn.to/3KLofNA)

1x [AA Spring Terminal](https://amzn.to/3EysOdH)

1x [Buck Converter](https://amzn.to/3KSzHHf) (if not using a [5V USB Power Bank](https://www.amazon.com/gp/product/B07QXV6N1B/), see [this writeup]() for more information)

2x [10x2mm Nitrile O-ring](https://amzn.to/37mEOko)

2x [13x3mm Nitrile O-ring](https://amzn.to/3KRAmsA)

5x [22x2mm Nitrile O-ring](https://amzn.to/3rrIp7N) (you can buy a [multipack](https://www.amazon.com/gp/product/B092MDGM110) that has all three sizes, thickness is not terribly important)

1X [2x8mm rare earth magnet](https://amzn.to/3Ostkga)

Approximately 24" of [20-24 AWG wire](https://amzn.to/3EoQ5yn)

3” section of 16AWG single strand wire (for internal battery positive connection)

---

#### Gen4 Bridge (External Battery Only)  

1x [Buck Converter](https://amzn.to/3KSzHHf) (if not using a 5V USB Power Bank, like [this one](https://www.amazon.com/gp/product/B07QXV6N1B/), see [this writeup]() for more information)

11x [M5x8 Bolts](https://amzn.to/3EyraZz)

11x [M5x5.8 Threaded Inserts](https://amzn.to/3E0fzRt)

1x [Push Button](https://amzn.to/3Txgdvg)

4x [Brass Washers](https://amzn.to/3WSWOI2)

1x [5.5x2.1mm DC Female Jack](https://amzn.to/3KLofNA)

2x [12mm Nitrile O-ring](https://amzn.to/3fV4qcD)

3X [22mm Nitrile O-ring](https://amzn.to/3V5NT4D)

2x [35mm Nitrile O-ring](https://amzn.to/3fVgjz8)

2x [45-46mm section of brass tubing](https://amzn.to/3E3g5Oq)

1x US nickel or other 19mm coin

Approximately 24" of [20-24 AWG wire](https://amzn.to/3EoQ5yn)
