# Shoresh (שֹׁרֶשׁ)

A phone-friendly app for relearning the Biblical Hebrew verb stems (binyanim) and core vocabulary.

- **Stems:** the strong-verb paradigm of ק־ט־ל laid out like the Logos "Hebrew Paradigms" chart: seven stems; perfect, imperfect, imperative, infinitives, participles, wayyiqtol, jussive and cohortative; every person, gender and number. Stem markers and person/number affixes are color-coded.
- **Cards:** flashcards for one stem at a time, recognizing forms (Hebrew → parse) or producing them (parse → Hebrew), with spaced review and per-stem progress.
- **Drill:** parse forms or match stems, with a focus control to isolate any stems and forms.
- **Vocab:** high-frequency words with flashcards; every gloss names the source it was checked against.

## Install on your phone

This is an installable web app (PWA) hosted with GitHub Pages at **https://stevenjetton.github.io/hebrew-app/**.

1. Open that address in Safari (iPhone) or Chrome (Android).
2. iPhone: tap **Share → Add to Home Screen**. Android: tap **⋮ → Install app**.
3. Open it from the new icon. It runs full-screen and works offline after the first visit.

Progress is saved on the phone. The same app also runs as a Claude artifact, where progress saves to your claude.ai account instead.

## Updating

`index.html` is the artifact page wrapped in a standalone document. When it changes, also change `VERSION` in `sw.js` so installed copies download the new version.
