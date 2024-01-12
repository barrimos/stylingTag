# Styling tags
- This code will find class `.taglists` then set color for text and background following your setting.
- Color will be use `hsl` because easily to read and select.
- Tag will `generate with comma (,)` when sepearate the word.
- Setting color separate each background and text into variable. e.g.

        sample: {
            background: 'hsl(38, 100%, 90%)',
            text: 'hsl(38, 100%, 30%)',
        }

- Use `contrast ratio system` for best color palette. https://www.w3.org/WAI/GL/wiki/Contrast_ratio
Contrast ratios can range from 1 to 21 (commonly written 1:1 to 21:1).
At least contrast ratio is 4.5:1