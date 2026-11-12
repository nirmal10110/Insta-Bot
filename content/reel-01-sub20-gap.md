# Reel 01: the sub-20 gap

Made with `/ig-reel` on 2026-11-12. Fits the "chasing sub-20 5k" series (the format your page and the swipe file say works).

## Opening lines (scored)

| Score | Formula | Spoken | On screen |
|---|---|---|---|
| **84 STRONG** ✅ | #3 Nobody Tells You | "Sub-20 means 4:00 a k. Nobody tells you. I'm at 5:28." | **4:00 vs 5:28** |
| 81 STRONG | #15 Flop Record | "Day 8 of chasing sub-20 and I'm still 88 seconds off." | **88 SECONDS OFF** |
| 75 STRONG | #17 Head To Head | "My half marathon pace is 5:07. Sub-20 needs 4:00. I'm not close." | **5:07 vs 4:00** |

The first one is the pick. The gap is a real number from your own Strava, and it reads at a glance.

## Script (voiceover, ~29s)

```
Sub-20 means 4:00 a k.
Nobody tells you that. I'm at 5:28.
That's 88 seconds too slow.
Every k. For five of them.
Seven minutes to find.
I ran my first sub-2 half at 5:07 a k, on two hours of sleep.
This is a different sport.
Day 8 was intervals. 4.36 k of them.
The plan: {{your plan in one line}}.
Race day: {{date}}.
Follow along.
I either hit 4:00, or find out why not.
```

## Beat sheet and on-screen text

The cards sit between y=230 and y=1440, with the right 230px kept clear. Burn in captions for the body.

| Time | Spoken | On-screen card | Shot |
|---|---|---|---|
| 0:00 | Sub-20 means 4:00 a k. | **4:00 /km** | you already running, track, moving camera, from frame 1 |
| 0:02 | Nobody tells you that. I'm at 5:28. | **ME: 5:28** | Strava screenshot (day 5: 5.26 km, 5:28/km) |
| 0:05 | That's 88 seconds too slow. | **-88s /km** | close-up of watch or legs |
| 0:07 | Every k. For five of them. | **x5** | lap marker / track lines |
| 0:09 | Seven minutes to find. | **7 MINUTES** | you, out of breath |
| 0:11 | I ran my first sub-2 half... | **HALF: 5:07 /km** | half-marathon finish clip; **cut to the Sinai clip halfway** (this beat is 5.8s, so it needs the cut) |
| 0:16 | This is a different sport. | **DIFFERENT SPORT** | you on the track |
| 0:18 | Day 8 was intervals. 4.36 k of them. | **DAY 8: INTERVALS** | day 8 sunset clip |
| 0:21 | The plan: {{...}} | {{plan in ≤6 words}} | |
| 0:24 | Race day: {{date}} | **{{DATE}}** | |
| 0:25 | Follow along. I either hit 4:00, or find out why not. | **4:00 OR BUST** | you running away from camera (the last line echoes "4:00", so the replay loops) |

## Checks

```
REEL READY (pending 2 placeholders)
hook:       #3 Nobody Tells You, scored 84 STRONG
length:     29.4s across 12 beats at 165 wpm (target 30s)
on-screen:  11 cards
humanizer:  0 artefacts, human score 85.7 PASS
flags:      beat 6 is 5.8s, so cut inside it; beats 9-10 need your real plan and date
caption:    run /ig-caption next
```

## Fill in before shooting

- `{{your plan in one line}}`: e.g. how many runs a week, and what kind.
- `{{date}}`: a parkrun or race date.
- Check **88 s/km** and **7 min**. They're worked out from your day-5 run (5:28/km). If your current best 5K is faster, swap in that pace.
