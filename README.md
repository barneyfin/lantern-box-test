# Lantern Box tests

Test builds of **Gloam Hallow** and the Lantern Box kit's test page, for trying on any device. Not finished, and not for sharing.

Open https://barneyfin.github.io/lantern-box-test/ and choose:

- **Gloam Hallow** (`gloam-hallow.html`): the game, with its Testing screen in Settings.
- **Play check** (`gloam-hallow.html?check`): Start game plays by itself for about two minutes, through all four places and their bosses, and gives a result to copy.
- **Trials for slow devices** (kit 0.20.2): the play check with one look trade-off switched on from the address (`gloam-hallow.html?check&trial=cloud`, `boss12`, `lines540`, `lines432`, `few`, `nohud`, `hero` (kit 0.20.4), `mon` (kit 0.20.5), `tree` (kit 0.20.6), `branch` (kit 0.20.10), or several joined by commas), to time each on a slow device before anything is decided.
- **Test page** (`lb-sampler.html`): every drawing part and screen, and the speed check (tap Speed check, or press T).

On an iPhone, for full screen: open Gloam Hallow, then Share, then Add to Home Screen, and play it from its icon.

Both files are built single-file pages (made by `python lantern-box/kit/build.py` in Barney's arcade). The fonts embedded in them, IM Fell English and Alegreya Sans, are under the SIL Open Font License 1.1; their licences are in `licences/`. The music was made with Google Gemini.
