# Publishing checklist

## GitHub repository

1. Copy the contents of this folder into `tsarpl/ose-eveskyr-roll20-sheet`.
2. Make sure the `images/` folder is committed before testing, because the CSS uses raw GitHub image URLs.
3. Confirm that the raw links resolve after pushing to `main`.
4. Test the sheet in Roll20 as a custom sheet using `eveskyr-ose.html` and `eveskyr-ose.css`.

## Roll20 community sheet submission

1. Use the root folder contents as the sheet folder.
2. Confirm `sheet.json` points to:
   - `eveskyr-ose.html`
   - `eveskyr-ose.css`
   - `preview.png`
3. Confirm `translation.json` sits beside the HTML and CSS.
4. Add or update `roll20userid` in `sheet.json` if needed.
5. Replace `preview.png` with a final screenshot when you have the definitive presentation image.
