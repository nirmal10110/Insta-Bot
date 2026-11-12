# Swipe file: running / sub-20 5K

Made with `/ig-viral` on 2026-11-12. Data comes from YouTube Shorts, read from public channel pages. Instagram was not scraped.

## How this was collected

- **What:** 578 running-related Shorts from 16 channels. Each Short is ranked against the middle view count of that channel's last 12 Shorts.
- **Channels:**
  - **Small, closest to you:** Ollie Drieu (2.5k), Samuel Stow (2k), Personal Runner Rafael Chaves (1.5k), Coach Jason (5k), Ultimaterunning (5.6k)
  - **Mid-size:** Pritam Chakravarty (12k), Jack Anstey (17k), Runna TV (53k), Lee Grantham (55k), JOG ON (71k), Nick Bester (72k)
  - **Big, used for format only:** Ben Is Running (159k), Shervin Shares (233k), Nicklas Rossner (239k), The Run Experience (675k), Keltie O'Connor (775k), The Running Channel (847k)
- **Caveat:** YouTube's bot check blocked most caption downloads. So for most rows the "hook" is the video **title**. For 8 rows it is the actual **spoken line** from the first 3 seconds. The formula classifier recognised only 114 of the 578, so the patterns below come from reading the outliers by hand.
- **Confidence:** moderate. 578 Shorts across 16 channels is enough to call a pattern, but YouTube is not Instagram.

## Outliers worth copying (running-related, above 3× the channel's middle)

| × channel middle | Channel (subs) | First line | Formula (hand-classified) |
|---|---|---|---|
| 10.0× | Ollie Drieu (2.5k) | "The 5K distance has been haunting me for the last 6 months." *(spoken)* | #15 Flop Record / journey |
| 7.5× | Runna TV | "ready for this workout to be over" | relatable suffering |
| 6.8× | Runna TV | "I crossed 5K at, I think, 20 minutes" *(spoken)* | #21 Mid-Sentence Start |
| 6.3× | Nick Bester | "I'm not sure what hurts more, a 5k or a marathon" | #17 Head To Head |
| 5.9× | Nicklas Rossner | "3 runs per week: how to double your speed" | #11 Numbered |
| 5.4× | Ben Is Running | "Hi, I'm Ben and this is me before a 15-minute 5K" *(spoken)* | #13 Before And After |
| 4.5× | Nicklas Rossner | "Give me 53 seconds and I'll teach you to run faster" | #10 If This, Then Watch |
| 4.2× | The Run Experience | "I Accidentally Signed Up for a 100 Mile Race" | self-own story |
| 3.9× | Nicklas Rossner | "What different 5K speeds actually look like" | #18 Cold Open Demo |

The biggest raw multiples overall were gear and tech reviews (a shoe review at 154×, a protein bar at 297×). That's not your page, so they're ignored here.

## What's working

1. **A personal 5K time goal, in numbers, from someone who isn't there yet.** This is the strongest signal. Ollie Drieu's sub-20 diary hit 10× on a channel your size. Ben Is Running's before/after hit 5.4×. *This is exactly your "chasing sub-20" series.*
2. **Comparing two distances or two efforts** (5k vs marathon) and **relatable suffering** ("ready for this workout to be over").
3. **Short hooks:** about 7 words for the top third versus 8 for the bottom third. A small gap. The visible pattern is that the top hooks put a number or a pain up front.

## Your own page agrees (8 reels, middle value ≈ 540 views)

| Reel | Views | vs. your middle |
|---|---|---|
| Day 1 of chasing sub-20 5k | 1,689 | 3.1× |
| Sinai → sub-2 half | 1,539 | 2.8× |
| Day 5 sub-20 | 1,401 | 2.6× |
| Diving / summit / day 3 / day 8 | 186 to 631 | 0.3× to 1.2× |

Goal-and-story running reels outperform. Scenery and plain workout logs don't.

## Your versions (scored with hookscore.py)

| Score | Formula | Hook |
|---|---|---|
| 84 STRONG | #3 Nobody Tells You | "Sub-20 means 4:00 a k. Nobody tells you. I'm at 5:28." → **written up in `reel-01-sub20-gap.md`** |
| 81 STRONG | #15 Flop Record | "Day 8 of chasing sub-20 and I'm still 88 seconds off." |
| 76 STRONG | #17 Head To Head | "Half marathon at 5:07, or a 5K at 4:00. Only one scares me." |
| 74 STRONG | #21 story | "I hiked Mount Sinai, slept 2 hours, then ran my first sub-2 half." (re-cut of your 2.8× reel) |
| 64 OK | #13 Before And After | "This was me at 5:28 a k. Still not sub-20, but this is day {{N}}." (save this for when you have a faster run to show) |
