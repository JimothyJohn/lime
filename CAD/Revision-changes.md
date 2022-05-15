# lime case

The lime case is made specifically for the Olimex [STMP157STMP157-OLinuXino-LIME2H-IND](https://www.olimex.com/Products/OLinuXino/STMP1/STMP157-OLinuXino-LIME2/open-source-hardware). The case is designed to be 3D printed by most 1.5mm platforms, quickly assembled, and easily modified.

<iframe src="https://app.vectary.com/p/4s6I8xO6cj6LG1TICkYBCu" frameborder="0" width="100%" height="480"></iframe>

## Guidelines

The following guidelines should be followed when improving on the design:

* Absolutely NO fastener features
* Maintain symmetry whenever possible
* Keep feature resolution >=0.5mm and as large as possible
* Maximize fillet radii on non-critical features
* Minimize air gaps along connectors and board
* Must be able to print with recyclabe filament

## Revision 1 - Develop prototype

Revision 1 provided a two-piece "snappable" enclosure that exposed most connectors and provided a way to hang on industrial DIN rail for ECAB mounting.

* Top "shell" and bottom "lid"
* Honeycomb "grill" for expedited printing
* DIN rail mounting feature on back
* Fastener-less, snapped design

## Revision 2 - Optimize form

Revision 2 improved on the initial design mostly by conforming to the actual dimensions and print quality.

* Add "wall" to connector sides of lid to reduce print cleanup
* Convert grill from hexagons to circles to simplify design
* Reduce case length to improve HDMI and USB connector exposure
* Reduce overall width to more snugly capture board
* Add top hole feature to expose CAN screw terminals
* Add standoffs to lid to more securely retain board
* Expose microSD slot to speed up swapping
* Add relief for power and reset buttons

## Revision 3 - Improve functionality

Revision 3 improved functionality by adding more functionality to existing features.

* Finalize grill design to add symmetry
* Convert DIN hanging to DIN snapping for more secure mounting
* Optimize snapping security by exploring various print methods

## Enclosure roadmap

* Identify professional-quality 3D printing manufacturer
* Finalize filament material and brand
    * Must be both recyclable and conform to -45C to +85C operating range
* Achieve IP54 environmental protection
* Identify features / techniques that could improve print time WITHOUT reducing quality
* Improve aesthetics and add branding in place of "grill"
* Add ESD protection
