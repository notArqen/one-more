# One More: the saga

The story bible for **story mode**. Endless mode uses Acts I–II only, then loops the void (see the end of this file).

**Premise:** the button is a test. The test is a machine. The machine is a bunker. The bunker launches you into orbit. Orbit turns out to be an arcade cabinet, and the arcade is running *One More*.

**Status key:** ✅ built · 🚧 next · 📝 planned, needs approval

---

## Rules

| | Story mode | Endless mode |
| --- | --- | --- |
| Where | Side menu → Story mode switch | Default (story switch off) |
| Multiplayer | Not allowed (locks while in a room) | Yes |
| Odds | Risk climbs at 40% speed; **half of all fatal presses are forgiven** | Normal |
| Checkpoints | Entering an act halves the hidden risk; acts become restart points in the Story panel; the game-over card defaults to "one more from checkpoint" (space too) | None |
| Content | Every act, in order | Acts I–II, then loops event horizon → the other side, wilder each lap |
| Saves | Own best, tiers, drift, history, furthest act | Own best, tiers, drift, history |

Both modes: risk eases as a run gets longer (the climb slows to 30% speed by about press 70). Fixed milestones drift 3–7 presses further out after every new record. A fatal press is followed by a short pause before death, and the next press cuts the pause short.

Writing rules: no random effects that aren't tied to progress. Undiscovered tiers are never hinted at (no "???"). Friends' sounds are never played. The talking stage is deadpan.

---

## Act I: The Button ✅ (0–150)

| Milestone | At | What changes |
| --- | --- | --- |
| (passing your best) | your best + 1 | "new territory" banner, major-chord lift, particle burst, vignette surge |
| warming up | 15 | Number heat, first particles |
| heating up | 30 | Heat haze on the number, zoom blur, embers |
| on fire | 45 | Light leaks fade in and orbit (faster with count), hit-stop, shockwaves, sparkle sounds |
| unhinged | 63 | Projector gate weave, motion-blur streaks, drone |
| absurd | 83 | God rays behind the button |
| mythical | 102 | Depth of field (labels go soft), bloom, confetti |
| reality bends | 123 | RGB split on the number, invert flash every 4th press, trailer heartbeat that builds toward 150 |

## Act II: The Void ✅ (150–255) · checkpoint

| Milestone | At | What changes |
| --- | --- | --- |
| event horizon | 150 | Background cracks and flies apart; black hole behind the counter; black number with a white bloom outline; flat black-and-white button; low rumble |
| singularity | 168 | Stage warp, particles sucked in, full RGB split, heavy grain, 3D camera tilt |
| heat death | 185 | CRT scanlines, screen-wide shockwaves every press |
| the other side | 205 | White hole: everything inverts, gravity reverses, past scores float up |
| rewind | 228 | Counter runs backwards (real count kept), reversed clicks, particles fly into the button, VHS tracking band |

## Act III: The Machine ✅ (255+) · checkpoint

1. **it notices you (255):** hard cut to OLED black, deadpan grey button, heartbeat on every press. It talks: opening lines every ~10 presses, then rotating lines every 30–45 (at least 8s apart, so spam can't speed it up). The tab title copies each line, and the cursor becomes a crosshair.
2. **It breaks:** nine stages of the stylesheet "failing": serif fallback font, square button, misaligned ring, browser-default labels, red debug outline, monospace, and a counter that sometimes shows `undefined`.
3. **The echo:** after "i'll just watch.", Act I's effects creep back one tier every 12 presses.
4. **The drain:** then the colour drains to black and white over 100 presses.
5. **signal lost:** CRT power-off (white line, then a dot), 3s of silence with input locked, then a clunk.

## Act IV: The Bunker ✅ · checkpoint

Pixel scene drawn at 1/5 resolution. Concrete walls, stencilled red paint (ЕЩЁ ОДИН "one more", НЕ НАЖИМАТЬ "do not press"), a steel control panel with a red cylinder button, orange Nixie counter, and РЕКОРД (record) on the panel. A bare bulb swings, so shadows and dust move with it. 50Hz hum, mechanical clunk per press, drip on a fixed beat.

| Milestone | At (from bunker start) | What changes |
| --- | --- | --- |
| the bunker | +0 | Arrival |
| radiation | +30 | Green CRT on the wall shows the count; Geiger clicks per press, building to ambient crackle |
| alarm | +65 | Red beacon sweeps the room, ТРЕВОГА (alarm) painted on, klaxon every 10 presses |
| launch | +100 | Wall reads ПУСК (launch); Nixies count 10 → 0; rumble, shake, whiteout |

Death here: the bulb pops and the room goes black.
After launch: 3.4s of white with a faint ПУСК afterimage, then Act V.

## Act V: Orbit ✅ · checkpoint

A pixel-art Earth turns below; you're looking out a capsule window with the button on the dash. Zero gravity: particles drift and tumble. All audio is muffled, with slow breathing. The screen edges curve like thick glass.

Built as: 3.4s after the launch whiteout, it fades in to a pixel Earth (rotating, clouds, ice caps, blue atmosphere rim) through a rounded capsule window with rivets and a glass glint. The count is a green HUD on the glass. Dash: ВОСТОК label, two gauges whose needles follow the count, РЕКОРД, red button. Presses throw weightless debris that drifts and never falls. All game audio goes through a low-pass "muffle"; helmet breathing (every 4.2s) and the radio bypass it.

| Milestone | At (from orbit start) | What changes |
| --- | --- | --- |
| low orbit | +0 | Arrival out of the launch whiteout |
| satellite | +40 | Radio crackle; Morse beeps tap out your past run scores every 9s; a satellite crosses the window with a blinking light |
| dark side | +85 | The moon slides across and swallows the view; everything goes dark except the stars, button and HUD |

Death here: the window glass cracks and the sound sinks to almost nothing.

## Act VI: The Arcade 🚧 next

The camera pulls back out of the window and keeps going. It was all on a CRT inside a dim 1980s arcade cabinet. Clicks become chiptune blips; "INSERT COIN" blinks; the count becomes a pixel-font SCORE; neon from the cabinets around it.

| Milestone | Idea |
| --- | --- |
| arcade | The reveal |
| high score table | Top-10 initials table: multiplayer friends' names, plus initials echoing the talking stage (ITS, WCH, YOU) |
| continue? | "CONTINUE? 9… 8…" countdown that presses reset; letting it hit 0 doesn't kill you, the arcade just goes dark (transition) |

## Act VII: The Loop 📝

Fade in on "One More / Press your luck." It looks like a new game, but the counter keeps its 650-something count. Subtly wrong: mirrored title, off-centre button, clicks a semitone flat. The only line is "again?". The saga may or may not continue past here.

---

## Endless mode

Acts I–II up to **the other side**, then it laps: event horizon → singularity → heat death → the other side → event horizon… Each lap multiplies particles, shake, RGB split, warp strength and star speed by about 45%. The banner reads "event horizon ×2", "×3" and so on. No rewind, Machine, or later acts.

## Debug console

`onemore.help()`: `incognito()`, `immortal()`, `to(name|number)`, `skip(n)`, `watch()`, `risk(p)`, `die()`. Any run touched by these never saves.
