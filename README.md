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
  - **From-above dial** with hip turn, shoulder turn and the lead arm, plus the ball.
  - **Angle-of-attack zoom:** a close-up circle at the ball showing the clubhead path and its angle at contact: about 4° down with irons, 5° down with wedges, 3° up with the driver.
- **Kinematic sequence** (next to the Start button): rotation speed of pelvis, chest, lead arm and club through the downswing, with a playhead. They peak in that order, each faster than the last.
- Driver, 7-iron and wedge setups. Full, 10:30, 9:00 and 7:30 swing lengths at the same tempo.
- Optional guide lines: the spine extended to the ground and a vertical line through the ball.
- **Wedge ladder:** enter your full carry with PW, GW, SW and LW, and the grid estimates the carry at 7:30, 9:00 and 10:30. Tap a cell to see that swing. "Find a shot" gives the closest wedge and length for a distance, in metres or yards. A partial-swing feel adjustment tunes the estimates to you.
- Slow motion at ½× and ¼×, a scrubber, and jump buttons for the ten swing positions (P1–P10).

The positions model a typical good swing. They are not a measurement of yours. Partial carries assume clubhead speed scales with how far the club travels from the top to impact in the same downswing time.

It is a single `index.html` with no build step. Open it in a browser, or use GitHub Pages to run it on your phone: set Settings → Pages → Source to **GitHub Actions**, and `.github/workflows/pages.yml` publishes `main` on every push.

On iPhone the beats play even with the silent switch on; the volume buttons still need to be up.

After an update, GitHub Pages can serve the old page for up to 10 minutes. Reload without the cache (Ctrl/Cmd+Shift+R), or on a phone close and reopen the tab or home-screen app.
