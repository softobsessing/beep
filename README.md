# beep

A little 3D-printable robot in a pink hoodie, sitting cross-legged with a laptop. Its face is a
46 mm round Waveshare ESP32-S3 AMOLED display.

**Doom scroll website:** https://softobsessing.github.io/doomscroll-eyes/
Webcam-powered emotional eyes for the face display: it side-eyes you when you doom scroll.

## Files

| Path | What it is |
|---|---|
| `beep.blend` | The Blender model (assembled) |
| `print_ready/` | 14 STL files in mm, each already turned onto its best side for printing |
| `print_ready/orientation.json` | Print orientation, support area and bed contact for each part |
| `PRINT_GUIDE.md` | Slicer settings, colours per plate and assembly steps |

## Parts

- **Pink:** Hood_L, Hood_R, Body (hoodie top), Arm_L, Arm_R, Seam_Pins
- **White:** Hips, Leg_L, Leg_R, Hand_L, Hand_R
- **Head:** Face_Housing, Face_Rim (bezel)
- **Grey:** Laptop

Most parts press-fit together with ribbed pegs and keys (the hood seam pins take a drop of glue). Turn **supports on**
(tree, build plate only) and see [PRINT_GUIDE.md](PRINT_GUIDE.md) before slicing.

## Hardware

- Waveshare round ESP32-S3 AMOLED display (46 mm module, 466 x 466 px)
- 3 x M2 screws (display to head)
- USB-C cable (runs up through the body into the head)
