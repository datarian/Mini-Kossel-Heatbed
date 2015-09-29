Mini_Kossel_Heatbed
===================

Heatbed design for mini kossels. It is slightly elevated above the base extrusions in order to keep the motors underneath as cool as possible. For the same reason, there's a 3mm cork mat sandwiched between the heater and base aluminum plate.
Quick and dirty steady-state thermal simulations have shown that the bottom alu plate will be about 60°C with a bed heated to 110°C.

Experiences after 18 months or so of operation
-------------------------------------------------
- It works very well in general, heatup times are below 1 minute
- 1 mm aluminum is on the lower end in terms of stiffness. If I redid this, I'd increase the metal to a least 2 mm

Features
--------
- Fits kossel mini
- Solid construction using lasered 1mm aluminum sheets
- thermal isolation towards the frame using ptfe tubing and PE washers for minimized heat loss and faster heatup times.
- Cork isolation under the heater to protect motors underneath
 
Required materials
------------------
- Cut `alu_base`, `alu_fixture`, `alu_ring` from 1 mm aluminum sheet
- cork, circular, diameter around 180mm
- kapton bed heater, 160mm diameter
- 3 pieces of ptfe tubing 6mm od, ideally 3mm id, 6mm long
- 3x M3x20 and nuts to fix the whole thing to your kossel, as well as three compression springs, approx. 6-9mm in height.
- Your choice of build platform, i.e. boro, regular glass, carbon. Diameter 170 mm

Putting it all together
------------------------
Check the exploded view and the pics to get a better idea.

1. Align `alu_fixture` and `alu_ring`, mark the cutout of `alu_ring` on the fixture. It helps to stack `alu_fixture` and `alu_ring` using M6 screws in the holes while doing this.
2. Glue your kapton heater on the marked alu_fixture
3. Resolder the wires on the heater so that they point towards the heater's center. This way they'll go out nicely in the center hole of `alu_base`
4. Prepare cork circle, cut out a hole big enough to get the cables of the heater and thermistor through
5. Prepare the screws and ptfe-tubing (see pics for washer detail), put everything together.
  1. `alu_fixture` with glued-on kapton heater
  2. `alu_ring`
  3. cork circle
  4. `alu_base`
6. Screw setup from top to bottom:
  1. M3 washer
  2. Plastic washer
  3. Into ptfe tube and through heatbed sandwich
  4. Plastic washer
  5. Spring
  6. Plastic washer
  7. Nut in extrusion
