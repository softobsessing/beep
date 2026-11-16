# Printing the hoodie robot (pink hoodie, white robot)

**Before slicing (Bambu Studio):**
1. Support tab → turn on **Enable support**, type **tree(auto)**. Only the bezel and pins need none.
2. **Dry the PLA** (about 6 h at 50 °C) and print at **205–210 °C**. Damp filament at 220 °C is what made the hair-like strings.
3. **Use one plate per colour, not 1 big plate**, so the nozzle travels less between parts and strings less:
   - Plate 1, pink: Hood_L, Hood_R
   - Plate 2, pink: Body (hoodie top), Arm_L, Arm_R, Seam_Pins
   - Plate 3, white: Hips, Leg_L, Leg_R, Hand_L, Hand_R
   - Plate 4: Face_Housing + Face_Rim (blue-grey), Laptop (grey)
4. Brim: set **Outer brim only** (not "auto") on the arms, hands, legs and pins.

Load the files in `print_ready/`. Each one is already turned onto its best side and sits flat at Z = 0, in mm.
Don't rotate them in the slicer; just place them on the bed.
(`beep.blend` has the parts in their assembled pose.)

| File | Colour | Lies on | Supports | Size (mm, W x D x H) |
|---|---|---|---|---|
| Hood_L, Hood_R | pink | flat seam face | yes, inside the dome (tree supports) | 77.5 x 73.9 x 49.9 |
| Face_Housing (head) | blue-grey | open front face down (the 47 mm board bore prints perfectly round) | yes: under the sideways neck post, plus inside the bowl under the flat top of the back dome (about 20 cm² total) | 51.9 x 66.1 x 20.4 |
| Face_Rim (bezel) | blue-grey | front face (3 keys point up) | none | 55.9 x 55.9 x 4.2 |
| Body (hoodie top) | pink | its flat bottom (the seam) | light (arm sockets, neck); none inside the cable channel | 49.3 x 40.7 x 48.6 |
| Hips | white | flat bottom, two pegs pointing up | light (leg sockets, back opening) | 45.0 x 31.0 x 27.9 |
| Arm_L, Arm_R | pink | elbow side (0.8 cm² on the bed: use a brim) | tree supports | 36.6 x 32.0 x 36.1 |
| Hand_L, Hand_R | white (or any colour) | back of the hand (0.35 cm² on the bed: brim + tree supports) | a little, under the fingers | 16.9 x 15.2 x 24.2 |
| Leg_L, Leg_R | white | underside | tree supports under the rounded sides | 23.1 x 63.5 x 27.0 |
| Laptop | grey | back of the screen (17 cm² flat on the bed; the pegs under the base stick out sideways) | a little, under the two pegs | 46.0 x 50.4 x 29.0 |
| Seam_Pins (3 pins) | any | lying on their flat side | none | 3 mm x 6.4 mm each |

Settings (PLA): 0.2 mm layers (0.12 mm for the head and bezel), 3 walls, ~15% infill, brim on the arms, hands, legs and pins.
Every part is one colour now, so no colour changes are needed.

Test first: print the head + bezel, check the board (46 mm into a 47 mm bore), and check one 3 mm arm peg in its socket
(0.3 mm clearance). Leg and laptop pegs are 4 mm with crush ribs: they should need a firm push. If one won't go in, run a
4 mm drill bit through the hole by hand (that also removes stray support); if one is loose, add a drop of glue.

## Assembly (every step was simulated as clear)
1. Board into the head front (USB-C at 6 o'clock, over the 14 x 12.5 mm opening), 3 x M2 screws from behind. Press the bezel on: line its 3 keys up with the 3 slots inside the head's front edge (12, 4 and 8 o'clock) and push straight in. The narrow ribs on the keys are made slightly bigger than the slots, so it always presses in snugly (a firm push, the rib tips squash a little); to take it off again (to swap the board) pry gently at the edge with a fingernail. If it is too tight, sand the outer face of the keys a little; if loose, a dot of glue on one key.
2. Body: press the pink hoodie straight down onto the white hips (two ribbed pegs; the seam sits right under the waistband).
3. Legs: push straight back into the hips, two ribbed 4 mm pegs each. The small ribs are meant to squash: press firmly until the leg seats.
4. Laptop: its two ribbed pegs hang under the base; press it straight down into the holes in the thighs.
5. Hands: push each hand's D-shaped wrist plug into its cuff (flat side toward the palm, so it only goes in one way). A drop of glue is optional.
6. Arms (with their hands): push straight in from the sides (one peg each).
7. Cable: push the USB-C plug in through the opening low on the back (it crosses the pink/white seam; the pink side is funnelled so it won't catch), out of the neck socket on top; plug it into the board.
8. Head: lower it straight down the neck line into the socket (the post slides over the cable).
9. Hood: put the 3 pins in one half's seam sockets, slide each half in from its side (slightly downward), press together. Glue optional.
