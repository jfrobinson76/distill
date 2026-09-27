# Distill by Stillbound

**Most whiskey apps are notebooks. They record what you drank. Distill lets you make the whiskey, then shows you why it tastes the way it does.**

![Distill by Stillbound](screenshot.jpg)

## Why I built it

Whiskey drinkers know what they like. Very few know why. The answer sits in decisions most people never see: the ferment, the still, the cut, the cask. Stillbound is building a flavour engine for the whiskey trade, and Distill is its public front door. Anyone can make a whiskey on their phone, wait for it, and learn what each choice did. It also puts the engine in front of real people, in the open, where it can be tested and argued with.

## What's under the hood

- **A production model, not a guess.** No outcome tables, no authored results. Grain bill (9 grains), ferment length and yeast, still type and still geometry, cut points, 11 cask types, char level, climate and warehouse position all feed seven flavour axes across 18 styles.
- **Real mechanisms.** Long ferments build lactic character on a curve. Still height, lyne arm and condenser resolve into a reflux index. Peat smoke is set in the spirit and holds with age. Char smoke drifts. Angel's share compounds by climate, and strength falls in cool damp warehouses and rises in hot dry ones.
- **It explains itself.** The engine re-runs your whiskey with each decision reset to a plain baseline and measures what moved. The ranked "why" is computed, never written by hand, so the explanation and the result cannot disagree.
- **A score that measures the right thing.** Each style has a conformance baseline derived from the rules at build time. Following the guidance lands you on it. The everyday score reads how true to style your whiskey is. The craft verdict is kept for decisions the app does not steer you toward.
- **Séamus.** A master distiller persona that voices the app and audits the engine. No change that moves a score ships without his ruling, and every ruling sits in a ledger the test suite enforces.
- **Real-time cask ageing.** One day in your life is one year in the barrel. A twelve year single malt takes twelve days. Poitín needs no cask, so you can bottle one tonight.
- **Checked, not asserted.** 53 test suites. Your whiskey is matched against 138 real expressions. If a screen states a number the engine contradicts, the build fails.

## Where it stands

Live on the App Store for iPhone: [Distill by Stillbound](https://apps.apple.com/us/app/distill-by-stillbound/id6790754014)

Source: private.

---

Built by John Robinson · [Stillbound.ai](https://stillbound.ai)
