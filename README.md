# cap-fun

I made this to try out KiCad, see [blog post](https://hunsley.io/posts/2025/electronics-kicad-pcb-fabrication-cap-fun) and [follow-up](https://hunsley.io/posts/2025/electronics-cap-fun-pcb-fabrication-result-jlcpcb/).

This is a small educational circuit for demonstrating how capacitors work:

* insert an electrolytic capacitor (I suggest `1000uF`) into the cap header (longer leg goes next to the `+` symbol)
* insert a 3mm red LED into the LED header (longer leg goes next to the `+` symbol)

Now hold down the `discharge` push button. If the cap has charge, the LED should light and fade as the cap discharges.

If you want to be able to charge the cap, connect the `+V` and `GND` pads to a DC power source (5V suggested), and the `charge` push button will charge the cap while it is held down.

More info at [blog post](https://hunsley.io/posts/2025/electronics-kicad-pcb-fabrication-cap-fun).

## Footnotes

* the cap voltage rating doesn't matter much because it can only charge up to the voltage the power supply provides

