# Shellac — design notes

## Identity
The Delta, 1936: one bluesman, one guitar, a dirt road crossing. Painted after the
cover of Robert Johnson's *King of the Delta Blues Singers* (Columbia, 1961).

- Should feel: dry rust dust, late sun, long maroon shadows, quiet.
- Should not feel: neon, club lights, generic "retro orange".

## Palette (Crossroads)
Every colour is measured from the cover or the six walls; text colours are only lifted
in lightness. One warm hue family, so slots separate by lightness, not hue.
Slot names are schema labels:

- red: wall rust ground · orange: wall orange highlights · yellow: window light
- green: cover tan · cyan: sunlit road dust · blue: dim dust tan · magenta: cover maroon
- background: cover near-black maroon · text: cover paper cream · accent: rust

Trade-off: red/orange/cyan sit close in hue; they differ by lightness, which is weaker
for colour-blind viewers.

## Surfaces
- Active border: one solid rust (no gradient).
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
