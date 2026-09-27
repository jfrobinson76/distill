# Distill by Stillbound

**Most whiskey apps are notebooks. They record what you drank. Distill lets you make the whiskey, then shows you why it tastes the way it does.**

![Distill by Stillbound](screenshot.jpg)

## Why I built it

Whiskey drinkers know what they like. Very few know why. The answer sits in decisions most people never see: the ferment, the still, the cut, the cask. Stillbound is building a flavour engine for the whiskey trade, and Distill is its public front door. Anyone can make a whiskey, wait for it, and learn what each choice did. And the engine gets tested in the open, by real people.

## What's under the hood

- **A production model, not a guess.** No outcome tables. Grain bill, ferment, still geometry, cut, 11 cask types, char, climate and warehouse position all feed seven flavour axes across 18 styles.
- **Real mechanisms.** Still height, lyne arm and condenser resolve into a reflux index. Peat smoke is set in the spirit and holds with age. Char smoke drifts. Strength falls in cool damp warehouses and rises in hot dry ones.
- **It explains itself.** The engine re-runs your whiskey with each decision reset to a plain baseline and measures what moved. The ranked "why" is computed, never written by hand, so the explanation and the result cannot disagree.
- **A score that measures the right thing.** Each style has a conformance baseline derived from the rules. Following the guidance lands you on it. The everyday score reads style fit. Craft is judged on the decisions the app does not steer you toward.
- **Séamus.** A master distiller persona that voices the app and calibrates the engine. Every ruling he makes sits in a ledger the test suite enforces.
- **Real-time cask ageing.** One day in your life is one year in the barrel. A twelve year single malt takes twelve days. Poitín needs no cask, so you can bottle one tonight.
- **Checked, not asserted.** 53 test suites. Every build is checked against real whiskeys on the shelf. If the app's copy states a number the engine contradicts, the build fails.

## Where it stands

Live on the App Store for iPhone: [Distill by Stillbound](https://apps.apple.com/us/app/distill-by-stillbound/id6790754014)

Source: private.

---

Built by John Robinson · [Stillbound.ai](https://stillbound.ai)
