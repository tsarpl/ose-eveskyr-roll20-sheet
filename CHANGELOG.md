# Eveskyr OSE Roll20 Sheet

## 3.8

Internationalization pass for Roll20 publication.

### Changes

- Added `data-i18n` attributes to visible labels, headings, buttons, options, and roll template labels.
- Added `data-i18n-placeholder`, `data-i18n-title`, and `data-i18n-aria-label` where appropriate.
- Updated and saved the English translation file as `translation-v3.8.json`.
- Preserved all layout, roll formulas, sheet workers, PC/NPC mode behavior, and v3.7 functionality.

### Notes

- The existing visible Polish text remains in the HTML as fallback text for Roll20.
- Some dynamic roll output still comes from roll button formulas and character-entered values; this pass prepares the sheet UI and template labels for Roll20 translation.
