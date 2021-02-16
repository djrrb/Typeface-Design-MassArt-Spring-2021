

# Glyphs Cheatsheet


## Preview

**`Space bar`**: Show active glyph in Preview mode (just black and white)

<img src="preview.png" style="margin-left: 2rem; max-width: 40rem; max-height: 15rem; border: 1px solid #ccc" />

**`T`**: Go into text mode, where you can type other glyphs

<img src="text-mode.png" style="margin-left: 2rem; max-width: 40rem; max-height: 15rem; border: 1px solid #ccc" />

**`Contextual menu > Add Guide`**: Right click to add guideline; double-click guide point to change orientation, and use preferences to lock guide and ruler button to show measurements. 

  Font-wide guides like Cap Height and x-height can be set in `Font Info` (the ***`i`*** button) under `Masters`.

<img src="guidelines.png" style="margin-left: 2rem; max-width: 40rem; max-height: 40rem; border: 1px solid #ccc" />

**Paths > Edit Background** or **`cmd`+`B`**: Every layer has a background where you can place items for reference. It is displayed with a light peach background.


## Components

**Contextual Menu > Decompose**: Convert selected component references into outlines

<img src="decompose2.png" style="margin-left: 2rem; max-width: 40rem; max-height: 15rem; border: 1px solid #ccc" />


## Adding points

**Add points to existing path**: Use Pen Tool, click on path

<img src="add-points.png" style="margin-left: 2rem; max-width: 40rem; max-height: 15rem; border: 1px solid #ccc" />


**Convert straight segment to curve**: `Option + Click` on segment, handles will appear

<img src="handles.png" style="margin-left: 2rem; max-width: 40rem; max-height: 15rem; border: 1px solid #ccc" />

**Toggle point smoothness**: `Double click` on a point to toggle smoothness. Green points are smooth; blue are unsmooth.

<img src="smooth-point.png" style="margin-left: 2rem; max-width: 40rem; max-height: 15rem; border: 1px solid #ccc" />

**Points on extremes**: `Paths > Add Extremes` will add points at the northmost, southmost, eastmost, and westmost parts of a curve.

With points on these extremes, most of your handles will be either totally vertical or totally horizontal, so you can constrain their movement with the `Shift` key.

<img src="points-on-extremes.png" style="margin-left: 2rem; max-width: 40rem; max-height: 15rem; border: 1px solid #ccc" />

**Contextual Menu > Open Corner**: Convert a point into two points with the contour overlapping itself. Helpful to change the contour in one dircetion but not the other.

<img src="open-corner.png" style="margin-left: 2rem; max-width: 40rem; max-height: 15rem; border: 1px solid #ccc" />

## Deleting points

**Remove points**: Select points, `Delete`. If you remove one at a time, it will try to keep the curve as best it can.

<img src="remove-points.png" style="margin-left: 2rem; max-width: 40rem;max-height: 15rem; border: 1px solid #ccc" />

**Delete segment and open path**: Select segment, `Option + Delete`

<img src="delete-segment.png" style="margin-left: 2rem; max-width: 40rem; max-height: 15rem; border: 1px solid #ccc" />

## Contour relationships

**`Paths > Remove Overlap`**: merge multiple contours into one

<img src="remove-overlap.png" style="margin-left: 2rem; max-width: 40rem; max-height: 15rem; border: 1px solid #ccc" />

**`Paths > Reverse Contours`**: Toggle between additive and subtractive contours

<img src="reverse-contour.png" style="margin-left: 2rem; max-width: 40rem; max-height: 15rem; border: 1px solid #ccc" />


## Spacing

Remember to **space as you draw**! Don’t wait to update sidebearings later. 

  Drawing within the context of control characters like `H`/`O` and `n`/`o` in a string like `HHXHOHOXOO` will help you consider how the shape affects color and rhythm. 

<img src="space-as-you-draw.png" style="margin-left: 2rem; max-width: 40rem; max-height: 15rem; border: 1px solid #ccc" />

You can also use key commands to change spacing in text mode (`T`):

* `cmd`+`shift`+`←`/`→`: Adjust right sidebearing +/- 10 units
* `ctrl`+`shift`+`←`/`→`: Adjust left sidebearing +/- 10 units

