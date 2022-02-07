# Clock Face

This is the local Klipper display configuration used for the [Clock 3](https://github.com/jon-harper/clock-3) project.

## Changes

Currently, it displays the chamber temperature where the part cooling fan speed is normally on 12864-sized (16x4) displays. 2004 (20x4) displays are not yet supported.

Additional changes will likely include a cleaner, more intuitive menu layout.

## Example Usage

From a shell on your Raspberry Pi:

```
cd ~/klipper_config
git clone https://github.com/jon-harper/clock-face clock-face
```

Add the line:

    [include clock-face/main.cfg]
	
to your `main.cfg` file somewhere.