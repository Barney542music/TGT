# The Buzzer Show

A phone-friendly, GitHub Pages-ready buzzer website.

## Features
- Two large touch-friendly buzzers; disable either one for single-host mode.
- First press locks both buzzers and announces who buzzed first.
- Animated red X overlay.
- Original synthesized buzzer and sad-style background melody using Web Audio (no external music file).
- Toggles for each buzzer, music, buzzer sound, and X effect.
- Reset round and fullscreen controls.
- Keyboard: `1`/`A` for buzzer 1, `2`/`L` for buzzer 2.

## Publish on GitHub Pages
1. Create a new GitHub repository.
2. Upload `index.html` to the repository's top level.
3. Open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select branch **main** and folder **/(root)**, then Save.
6. Wait for GitHub to publish the site; its Pages address will appear in Settings → Pages.

Audio starts only after a user taps/clicks, due to browser autoplay restrictions.
