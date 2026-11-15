# Shellac — design notes

## Identity
The Delta, 1936: one bluesman, one guitar, a dirt road crossing. Painted after the
cover of Robert Johnson's *King of the Delta Blues Singers* (Columbia, 1961).

- Should feel: dry rust dust, late sun, long maroon shadows, quiet.
- Should not feel: neon, club lights, generic "retro orange".

## Palette (Crossroads)
Every colour is an exact main colour of the cover or the six walls (k-means in OKLab),
not lifted or invented. Every theme file uses only these colours. One warm hue family,
so slots separate by lightness, not hue. Slot names are schema labels:

- red #b8352c: the red of the record wall, also on the cover · orange #f67a3c: the sun orange of the walls
- yellow #e89d63: the window light in the room · green #9e7b5e: cover tan brown
- cyan #c98053: warm wall tan · blue #b25530: wall rust · magenta #a85e3e: cover light rust
- background #140605: cover maroon shadow, one step darker · text #dbc0a0: cover cream type · accent #c5693d: rust

Trade-off: the slots sit close in hue and differ by lightness, which is weaker for
colour-blind viewers. Red (3.4:1), blue (4.0:1) and magenta (4.1:1) sit below 4.5:1
on the ground; the art comes first.

## Surfaces
- Active border: one solid window light (the room's sun patch), 4.1:1 against the rust walls; rust stays the accent.
- Icons: Yaru-red, the closest stock icon set to rust.
- Bar: Delta dark, paper text, rust for the active workspace.
- Menu/launcher selection: rust wash with a solid rust edge.
- btop/cava: graphs rise from the maroon shadow through rust into window light.
- Discord: Midnight imported unchanged; only its colour variables are set.

## Wallpapers
Six painted walls seen from above, one light, one story:
1 the crossing, 2 the wait, 3 the deal, 4 the room, 5 the record, 6 coda (only his shadow is left).
Generated with Codex using the room as the style reference, then matched to one mean
lightness, chroma and hue across the set and upscaled to 4K. The crossing's shadow was
rebuilt from a side silhouette of the same pose so it matches the man.
