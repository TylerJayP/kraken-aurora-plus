# Aurora for Kraken Plus (240×240)

A version of the **Fluid Dynamics – Aurora** NZXT CAM web integration by
[najibra](https://github.com/najibra/nzxtv2), resized for the 1.54" 240×240 LCD
on the NZXT Kraken / Kraken Plus. The original was built for the Kraken Elite's
640×640 screen, so on the smaller LCD its text ended up about 4 px tall.

This version keeps the cyan/magenta aurora beams but shows fewer, larger readouts:

- CPU temperature (large, center)
- GPU temperature and liquid (coolant) temperature
- RAM usage

It also fixes the gauge arcs, which didn't draw in the original because a CSS rule
overrode the `stroke-dasharray` attribute.

## Use it

In NZXT CAM: **Lighting → LCD Display → Web Integration → Custom (Settings)**, then
paste:

```
https://tylerjayp.github.io/kraken-aurora-plus/
```

Opening the link in a normal browser shows a preview running on simulated data.
