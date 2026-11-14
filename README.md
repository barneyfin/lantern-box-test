# Lantern Box tests

Test builds of **Gloam Hallow** and the Lantern Box kit's test page, for trying on any device. Not finished, and not for sharing.

Open https://barneyfin.github.io/lantern-box-test/ and choose:

- **Gloam Hallow** (`gloam-hallow.html`): the game, with its Testing screen in Settings. Since kit 0.21.0 a run is saved at each lantern: close the tab mid-run and Continue is on the title (Testing's "Pause closes the page" does the same as closing it). Since kit 0.24.0: a life for each boss up to five (Testing's "Lives at the start" helps reach five), The Moor Mother closing in, and the lightning bolt drawn wider. Since kit 0.25.0: graves and other props meet the ground on slopes, and the boss's name plaque grows to fit on a phone. Since kit 0.28.0: the game starts before its soundtrack has arrived, which comes at the end of the file and fades in; since 0.28.1 it is unpacked a track at a time, so play doesn't stutter as it arrives. Since kit 0.27.0: the climb (each place from Blood Red Rain on lighter before its halfway lantern and busier after it) and, on a phone, pull the stick down to the side to roll (design system 21). Since kit 0.31.0: The Endless Rot, a new mode of waves in arenas (design system 23), opened by beating The Veiled Ghost or from Testing's "The Endless Rot" switch, and a Personal bests tab in High scores. Since kit 0.32.0, from wave 4 some crawlers and ghouls rise up through cracked ember warnings inside the arena.
- **Play check** (`gloam-hallow.html?check`): Start game plays by itself for about two minutes, through all four places and their bosses, and gives a result to copy.
- **Play check: The Endless Rot** (`gloam-hallow.html?check=rot`, since 0.31.0-r1): the same for the new mode, in its four arenas at their busiest waves, the first time round and again, harder. Since 0.31.0-r2 the picture settles while the first wave fills Night's arena, as play begins.
- **Trials for slow devices** (kit 0.20.2): the play check with one look trade-off switched on from the address (`gloam-hallow.html?check&trial=cloud`, `boss12`, `lines540`, `lines432`, `few`, `nohud`, `hero` (kit 0.20.4), `mon` (kit 0.20.5), or several joined by commas), to time each on a slow device before anything is decided.
- **Test page** (`lb-sampler.html`): every drawing part and screen, and the speed check (tap Speed check, or press T).

On an iPhone, for full screen: open Gloam Hallow, then Share, then Add to Home Screen, and play it from its icon.

Both files are built single-file pages (made by `python lantern-box/kit/build.py` in Barney's arcade). The fonts embedded in them, IM Fell English and Alegreya Sans, are under the SIL Open Font License 1.1; their licences are in `licences/`. The music was made with Google Gemini.
