# Eveskyr OSE Roll20 Sheet

Custom Roll20 character sheet for **Old School Essentials**, built for the Eveskyr / Highforge campaign.

Current release: **3.8**

## Main files

For Roll20 custom sheet testing, use:

- `eveskyr-ose.html`
- `eveskyr-ose.css`
- `translation.json`

For a Roll20 community sheet submission, keep these files together with:

- `sheet.json`
- `preview.png`
- `images/`

## Directory structure

```text
eveskyr-ose-roll20-sheet/
├─ README.md
├─ CHANGELOG.md
├─ sheet.json
├─ eveskyr-ose.html
├─ eveskyr-ose.css
├─ translation.json
├─ preview.png
├─ images/
│  ├─ back_royalblue_satin.jpg
│  ├─ back_lightcream_paper.jpg
│  ├─ back_header_granit.jpg
│  └─ back_lightcream_money.jpg
├─ docs/
│  ├─ CHANGELOG-v3.8.md
│  ├─ TRANSLATION-NOTES.md
│  └─ mapa-atrybutow-ose.txt
└─ releases/
   └─ v3.8/
      ├─ eveskyr-ose-v3.8.html
      ├─ eveskyr-ose-v3.8.css
      ├─ translation-v3.8.json
      └─ CHANGELOG-v3.8.md
```

## Notes

- `eveskyr-ose.html`, `eveskyr-ose.css`, and `translation.json` are the current publication names for version 3.8.
- The `releases/v3.8/` folder preserves the versioned source files.
- The CSS references the GitHub raw image URLs for the `tsarpl/ose-eveskyr-roll20-sheet` repository. Keep the `images/` folder in the repository so those URLs remain valid.
- `roll20userid` in `sheet.json` is intentionally empty. Fill it before submitting to the public Roll20 character sheet repository, if required.
