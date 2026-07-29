Corpse Party opening overlay PNG inputs
=======================================

Place any of these files in this directory:

  op0en_01.png
  op1en_01.png
  op2en_01.png
  op3en_01.png

The builder imports each PNG into the corresponding existing English-slot
Texture2D and keeps the overlay visible for its entire op0/op1/op2/op3 section.
All four overlays use the original English op0/06 Transform, so they appear in
the same screen location.

IMPORTANT
---------
Each PNG must use the exact dimensions of its original Texture2D. The builder
will stop with a clear error if a PNG has different dimensions. This protects
the existing Sprite geometry and avoids clipping or malformed mesh data.

Missing PNG files are allowed. The builder will report them and retain the
original English image for that section.
