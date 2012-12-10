# What to do if the Internet Doesn't Work

First, try to fix it based on this document.  If you can't, contact someone who can.  If you do manage to fix it or do anything to attempt to, please update pumping-station-one-operations@googlegroups.com with what you did and if it worked.

## I'm at the Space

* check https://space.pumpingstationone.org/.  If it responds, the router cluster is up.  Log in.  The dashboard should show whether the Atmosphere link is working - check the dashboard for AtmoCommL1.  If it shows as 'offline', handle via 'Atmosphere Gateway Down' section.

### Atmosphere Gateway Down

Go to the wiring closet.  It's upstairs near the side stairwell, with gray folding doors.  Locate the 2 port patch box in the closet with a port labelled 'atmosphere' on the left wall.  Trace the ethernet plugged into it to a PoE injector.  The injector is a small black box with a power cable and 2 ethernet ports.  If it is not powered (no green light) figure out how to get it power.  If it is powered, unplug it and plug it back in to restart the microwave radio.  Wait a minute or 2 and check of the Internet is up.

## I'm not at the Space

* TBD on documenting that.  Pretty much if the Internet at the space is down and you're not here, how exactly are you supposed to remote in and fix it? I suggest a car, personally.

## The Beeping, Oh God The Beeping

* That's probably the router cluster having a power outage. Go look at it. Are there orange lights on the UPSes at the bottom?  The router cluster is on the catwalk in the small rack.
* If you would, check if all the lights on the server rack are off (the other, larger rack).  They probably are.  That means that the circuit is out.
* I'm not sure why this is a bulleted list, this is really more of a narrative. If you don't like it, stop reading and do something more your speed like watching Survivor.
* Go to the back door. Open the breaker panel. Figure out which breaker is the right circuit and then untrip it.

## I Fixed a Thing (or didn't), Who Do I Tell?

* Kindly email pumping-station-one-operations@googlegroups.com with what you did.  If something is wrong with something electrical or computerized, and you couldn't fix it, please let us know so it can be handled.

## Can I Call for Help?

Yes, you can call.  Please don't if it's super late.  If you really need help, call the CTO, Eric Stein at 774-922-2866.

# More Info

This document lives at GitHub allowing it to be collaboratively edited, accessible offline on user's laptops, and tracked over time: https://github.com/pumpingstation1/operations-documentation
