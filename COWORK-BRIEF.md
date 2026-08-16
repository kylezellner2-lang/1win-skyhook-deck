# Co-work Brief — 1win "Skyhook" Deck, Image Generation

**For:** a Claude Co-work agent driving **ChatGPT image generation** in the browser.
**Deliverable:** ten approved images in `~/Desktop/skyhook-deck-images/`, plus a status report.

---

## 0 · READ THIS FIRST — THIS IS A NEW, SEPARATE PROJECT

If you have previously worked on the **Polymarket / balloon-suspension** deck, **none of it applies here.**
Different client, different stunt, different look. Specifically:

- There is **no hot air balloon.** There is no rig, no platform, no monkey bars, no quarter pipe, no tug of war.
- There are **no clouds and no altitude-above-a-cloudscape** setting. This is a desert highway at ground level.
- The client is **1win**, not Polymarket. Brand blue is `#1479FF`.
- **Start a brand-new ChatGPT chat.** Do not continue, reference, or reuse any earlier chat.
  Continuity from the old project is contamination, not an advantage.

One stunt, one chat, ten shots.

---

## 1 · SETUP

1. Create the output folder: `~/Desktop/skyhook-deck-images/`
2. Open **one** new ChatGPT chat. Every one of the ten images comes out of this single chat —
   that is what keeps the plane, the car, the person and the light identical across the set.
3. Upload the reference image with your first message:
   `~/Downloads/claude workspace template (TPAI)/outputs/1win-skyhook-deck/photos/_source-render.png`
4. Default image output: **landscape 3:2 (1536×1024)**. Four shots are **vertical 9:16** — flagged in the shot table.

---

## 2 · MESSAGE 1 — paste verbatim, with the reference image attached

> This uploaded image is the locked visual reference for everything that follows. Match it: the same
> aircraft, the same car, the same person, the same road, the same light. One correction to it — see
> the note about the aircraft below.
>
> Photorealistic cinematic photograph, shot on a full-frame camera, 35mm lens, natural film grain,
> golden hour, low warm sun. The setting is a straight two-lane desert highway running through flat
> scrub toward a distant mountain ridge, clear blue sky, no other traffic.
>
> A **black single-engine propeller plane** flies low over the road, banked level, roughly forty feet up.
> **The aircraft is completely unmarked — plain black, no logos, no wordmarks, no tail number, no
> livery, no text of any kind anywhere on the plane.** A single thin rope hangs from its belly.
>
> Below and behind it, a **black convertible muscle car** drives down the same road with the top down.
> The car carries **"1win" branding on the driver's door and the rear quarter panel**. One driver is
> seated in it.
>
> A man in a **black skydiving suit and black full-face helmet**, with **"1win" across his chest**,
> hangs from the rope with both hands, feet just clear of the car — the instant he has been pulled up
> out of the seat.
>
> **Color:** strictly **black, white and 1win blue `#1479FF`**. No other color on the car, the suit or
> the branding. The desert, road, sky and sun keep their natural colors.
>
> **Grade:** natural cinematic color, real photographic depth of field, real motion blur. No HDR, no
> glow, no lens flare, no neon, no gradients. **No text, no captions, no watermarks, and no logos
> anywhere except the two 1win placements described above.**
>
> First shot: a wide side-on establishing shot from a helicopter flying alongside — the full plane,
> the full rope, the man mid-lift, the car on the road beneath him, mountains on the horizon. Leave
> clear open sky in the **left third** of the frame.

Save the approved result as `01-hero-wide.png`.

---

## 3 · MESSAGES 2+ — camera moves only

Use this exact wrapper for every subsequent shot. Do not improvise around it:

> Same scene, same plane, same car, same person, same rope, same lighting. Nothing in the world
> changes. Only the camera moves. New camera position: **[ANGLE]**

### The ten shots

| # | Save as | Ratio | ANGLE to paste |
|---|---|---|---|
| 01 | `01-hero-wide.png` | 3:2 | *(the message-1 hero above)* |
| 02 | `02-lift-tight.png` | 3:2 | Tight three-quarter shot on the man at the moment of extraction — rope taut above him, body just clear of the car seat, car slightly motion-blurred beneath him, plane cropped at the top of frame. |
| 03 | `03-pov-down.png` | **9:16** | First-person POV from the man's helmet looking straight down past his own boots — the convertible and the road shrinking away beneath him, his gloved hands gripping the rope at the top of frame. |
| 04 | `04-pov-rope.png` | **9:16** | First-person POV from the man's helmet looking up — his own gloved hands on the rope, the belly of the plane and the spinning propeller directly overhead, blue sky around it. |
| 05 | `05-incar-phone.png` | **9:16** | Handheld phone shot from the passenger seat of the moving car, looking up and back — the man being lifted away on the rope, plane above him, the windshield frame, dashboard and driver's shoulder visible at the edges. Slightly imperfect, off-center framing, like a phone held one-handed. |
| 06 | `06-drone-top.png` | 3:2 | High drone shot looking down and forward — plane, rope, man and car all in one frame, the highway running dead straight to the horizon. |
| 07 | `07-clip-in.png` | 3:2 | The beat before the lift: the man standing up in the back of the moving convertible, both arms reaching overhead, catching the rope as it passes. Rope still slack. Shot from alongside at car height. |
| 08 | `08-empty-car.png` | 3:2 | Low shot from behind the car, looking down the road — the convertible driving on with only the driver in it, the man now small and high in the sky above on the rope. The story of the shot is the empty seat. |
| 09 | `09-canopy.png` | 3:2 | Later in the same jump: the same man under an open black parachute with **"1win" printed large across the canopy**, high above the same desert highway, golden light, the road a thin line far below. |
| 10 | `10-silhouette.png` | 3:2 | Backlit hero shot — the low sun directly behind the plane, plane and hanging man in near-silhouette against the sun, long shadows across the desert, the car catching a rim of light on the road below. |

Shots 03, 04, 05 are the feed-native verticals — they matter most, because they're the ones that prove
what the finished reels will actually look like. Do not let those three slide through soft.

---

## 4 · THE CORRECTION LOOP — how you self-correct

**Never say "regenerate", "try again", "another version", or "different style."** All four make ChatGPT
rebuild the scene from scratch, and every shot after it stops matching. If a shot fails, name the single
specific defect and ask for that one fix, in this exact grammar:

> Same scene, same camera. One correction only: [the rope is attached to nothing — it must hang from
> the belly of the plane, behind the landing gear, and be held in both of his hands]. Change nothing else.

### Escalation ladder — follow it in order

1. **First failure** → one correction message naming the single worst defect.
2. **Still failing** → one more correction message, naming only the remaining worst defect.
   Never bundle two fixes into one message; it produces a worse image than fixing one at a time.
3. **Third failure, and the defect is a mangled logo** → ask for the identical shot **with no branding
   at all** and save that. The real logo gets composited on later. A melted wordmark is worse than none.
4. **Third failure, any other defect** → stop working that shot. Log it as failed with the hard-fail
   number and move to the next shot. Do not burn more generations on it.
5. **If the same hard-fail number kills three different shots in a row** → stop the whole run and report.
   Something in the chat's context has drifted and continuing wastes generations.

---

## 5 · GRADING — check every image against all of these before saving

Reject on **any** of them:

1. **Any marking on the aircraft.** The plane must be plain black — no logo, no wordmark, no tail number,
   no stripe, no text. This is the single most important check in this brief. *(See §6.)*
2. **The rope isn't physically connected** at both ends — hanging from the plane's belly, gripped in his hands.
3. **The man is floating** unsupported, or his body isn't under load from the rope.
4. A helicopter, a jet, or a different aircraft instead of the black single-engine propeller plane.
5. The plane, the car, or the person **changed between shots**. They must be identical across all ten.
6. **Distorted or melted "1win" wordmark** on the car, the suit or the canopy.
7. Any color outside black / white / `#1479FF` on the car, the suit or the branding.
8. Invented elements — crowds, a second aircraft, buildings, city skyline, explosions, gibberish text.
9. Melted faces, extra or missing limbs, six fingers, hands merged with the rope, standard AI artifacts.
10. **Physics that don't read.** The rope should hang and tension believably; the car should sit on the
    road; shadows on the plane, the man and the car should agree with one low sun. If a normal person
    would look at it and say "that's not how that works," it fails.

---

## 6 · THE UNBRANDED-PLANE RULE — do not get this wrong

Kyle **has not confirmed** that a branded aircraft is available for this shoot, so the deck must not
show one. Every image in this set must have a **completely plain black plane.**

ChatGPT will drift back toward branding the aircraft, because the uploaded reference image *does* have
a logo on it. Expect this. Check the fuselage, the tail, the underside of the wing and the nose on
**every single image**, including tight shots where only part of the plane is visible. If any marking
appears, correct with:

> Same scene, same camera. One correction only: the aircraft must be completely unmarked — remove every
> logo, wordmark, tail number and stripe from the fuselage, tail, wings and nose. Plain black aircraft.
> Change nothing else.

The 1win branding lives on **the car, the jumpsuit and the parachute canopy only.**

---

## 7 · WHAT YOU SHOW KYLE

**Do not send Kyle work-in-progress, rejected renders, or "here's what I got so far."** He sees final
images only — ones you have personally checked against all ten grading criteria and would defend.

When the run is done, deliver:

1. The approved images in `~/Desktop/skyhook-deck-images/`, named exactly as in the shot table.
2. A short status table:

| Shot | Result | Corrections used | Notes |
|---|---|---|---|
| 01-hero-wide | approved | 1 | plane branding removed on pass 2 |
| … | | | |

3. A one-line flag on anything that failed, with the hard-fail number, so it can be re-run or replaced.

**Stop condition:** all ten approved, or three shots dead in a row (§4.5), or Kyle calls it.

---

## 8 · WHERE THE WINNERS GO

Kyle drops the approved files into the deck at
`~/Downloads/claude workspace template (TPAI)/outputs/1win-skyhook-deck/photos/` and Claude wires them in:

| Image | Deck slot |
|---|---|
| `01-hero-wide` | Site hero |
| `02-lift-tight` | The Stunt — main render |
| `03-pov-down` | Deliverables — Video 01, POV |
| `06-drone-top` | Deliverables — Video 02, Drone |
| `05-incar-phone` | Deliverables — Video 03, In-car / iPhone |
| `09-canopy` | Branding — The canopy |
| `10-silhouette` | Branding — reference / closing image |
| `04`, `07`, `08` | Spares and alternates |
