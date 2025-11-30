---
title: Extras
---

# Extras
Some miscellaneous extra information about Tensy, such as hidden features and configuration options.

## Troubleshooting: Use Direct3D on Windows
By default Tensy uses SDL's OpenGL renderer on Windows. However, if the OpenGL renderer does not work (e.g. you have broken graphics drivers, or are on a virtual machine without GPU acceleration) it should show a warning dialog and fall back to the Direct3D renderer.

You can also force Tensy to use the Direct3D renderer by passing `-d3d` as a command line argument when launching Tensy. You can do this by creating a shortcut to `tensy.exe`, right-clicking the shortcut, selecting "Properties", and adding `-d3d` to the end of the "Target" field.

## Opening the user data directory
On platforms and devices with a keyboard, you can press Ctrl + U when on the settings dialog to open the user data directory in some kind of file explorer. This can be useful for backing up your data or transferring it to another device.

## "Hyuge!" board size
If you hold down Shift at the configure game dialog a fourth board size option called "Hyuge!" appears. It is four times as big as the Big board size and the numbers end up being quite small.

## Customising number colours
You can specify custom colours for the coloured numbers by creating a `number_colors.txt` (note the American spelling) file in the user data directory. The format consists of nine hex colour codes for each number from 1 to 9, separated by a colon. For example this is how the default colours look like in the format:

```
FF988F:FFB169:FFF069:A0FF69:69FF73:69FFD2:69BBFF:9D7DFF:FF7DE7
```

## Easter eggs
There are some hidden easter eggs in Tensy. They won't be documented in detail here to avoid spoiling them, but here are some hints:

- Something in the about menu can be clicked to reveal a secret (1.0.1+).
- A secret game mode can be activated through the settings menu. There are two methods of activating it: either with a keyboard (1.0+) or by being on the settings menu during a special time (1.0.1+).
