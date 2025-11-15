# RSPSi

A RuneScape Private Server map editor with multiple editing modes and tools.

## Mode Selection

The editor supports seven different modes for map editing:

```
S-T = Select Tile Mode
S-O = Select Object Mode
D-O = Delete Object Mode
M-H = Modify Height Mode
P-O = Paint OverLays Mode
P-U = Paint UnderLays Mode
S-F = Set Tile Flags Mode
```

![Mode Selection](https://i.imgur.com/bnbM2s1.png)

## Controls

### Camera Movement (All Modes)

```
W / S                Move forward / backward relative to view angle
A / D                Strafe left / right
Page Up / Page Down  Move vertically on the Z-axis
Up / Down Arrows     Move forward without changing Z
Left / Right Arrows  Rotate camera left / right
```

### Select Tile Mode (S-T)

```
Click & Drag                    Select tiles
CTRL + Click                    Select or deselect a single tile
CTRL + SHIFT + Click & Drag     Deselect tiles (draggable)
SHIFT + Click & Drag            Add tiles to current selection
```

### Object Editing Modes (S-O and D-O)

```
Q   Rotate left
E   Rotate right
```

### Modify Height Mode (M-H)

```
Click           Increase height
SHIFT + Click   Decrease height
CTRL + Click    Smooth heights
ALT + Click     Set heights
```

### Paint Overlays Mode (P-O)

```
Click & Drag   Regular paint overlays to tile when clicked functionality
ALT + Click    Remove overlay from tile
SHIFT + Click  Recolor existing overlays and keep original overlay's shape
```

### Paint UnderLays Mode (P-U)

```
Click & Drag   Paint underlays to tiles
```

### Set Tile Flags Mode (S-F)

```
Click & Drag   Set flags to tiles
ALT + Click    Inverse/toggle flags on tiles
```