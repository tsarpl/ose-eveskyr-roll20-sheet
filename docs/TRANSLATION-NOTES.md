# Eveskyr OSE translation notes

This `translation.json` is an English translation dictionary prepared for the Eveskyr OSE Roll20 sheet.

Important: the current sheet HTML still needs `data-i18n` / `data-i18n-placeholder` / `data-i18n-title` / `data-i18n-aria-label` attributes added to the visible labels and attributes before Roll20 can use these keys.

Recommended next step:

1. Add `data-i18n="key"` to visible text elements.
2. Add `data-i18n-placeholder="key"` to translated placeholders.
3. Add `data-i18n-title="key"` and `data-i18n-aria-label="key"` where needed.
4. Keep the Polish text in the HTML as fallback while testing.
5. Upload `translation.json` in the Translation tab of the Custom Sheet editor or place it in the root folder for GitHub/Roll20 submission.

The current dictionary includes labels, tabs, NPC/monster labels, roll template terms, reaction attitude descriptions, placeholders, and Eveskyr/Highforge rank names.
