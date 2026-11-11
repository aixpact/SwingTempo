# SwingTempo

A full golf swing tempo trainer, and the companion to TicTocPutter. Every club gets the same rhythm: the backswing takes three times as long as the downswing, and only the length of the swing changes.

- Three beats: **1** at takeaway, **2** at the top, **3** at impact.
- 3:1 rhythm for full swings, 2:1 for the short game. Takeaway-to-impact time from 0.70 to 1.40 s, with presets.
- An animated face-on golfer:
  - **Wrist hinge and lag:** the angle between the lead arm and the shaft, shown live as it sets, holds into the downswing and releases.
  - **Hip and shoulder turn:** a pelvis line on the figure, plus a top-down dial with the gap between the two.
  - **Weight shift:** a trail/lead pressure bar under the feet.
  - **Leg action:** lead knee moves in, lead leg posts at impact, trail heel lifts.
  - **Clubhead path** with a speed trail.
- Driver, 7-iron and wedge setups. Full, ¾ and ½ swing lengths at the same tempo.
- Slow motion at ½× and ¼×, a scrubber, and jump buttons for the ten swing positions (P1–P10).

The positions model a typical good swing. They are not a measurement of yours.

It is a single `index.html` with no build step. Open it in a browser, or turn on GitHub Pages (Settings → Pages → Deploy from branch `main`, folder `/`) to use it on your phone.

On iPhone the beats play even with the silent switch on; the volume buttons still need to be up.
