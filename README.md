# Scorpio 2

ZMK firmware for the Scorpio 2 keyboard — an Eyelash Corne split keyboard
with a 5-column ynot-style keymap.

## Hardware
- **Board:** Eyelash Corne (nRF52840-based, from AliExpress)
- **Display:** nice!view (e-ink)
- **Layout:** 5-column (outer columns and joystick/encoder positions unbound)

## Keymap
Based on the [ynot-keyboard](https://github.com/egradman/ynot-keyboard) layout:
- Homerow mods on bottom row
- Tri-layer (LOWER + RAISE = ADJUST)
- Combos for numpad, hyper, caps word, return, ctrl-b
- No trackpoint, no scroll wheels

## Building
Push to GitHub and let GitHub Actions build the firmware, or build locally with
the ZMK toolchain.

## Flashing
1. Connect keyboard half via USB
2. Double-tap reset button to enter bootloader
3. Copy the `.uf2` file to the `NICENANO` drive
4. Repeat for the other half
