# Grid Paper CSS Template

This project provides a simple and flexible **CSS grid background pattern** that can be used as a background element in your creative tech prototypes, generative visuals, or design experiments. The grid is built using pure CSS with customizable variables for easy adaptation.

## Usage

1. **Copy the file:**
   Copy `grid-paper.css` into your project directory.

2. **Import the stylesheet:**
   In your HTML file, or your React file, or however. Just on the page you want the grid to appear on.
   
3. **Customise values**
   Default values should be alright but you have the option to customise the grid using variables, as outlined below.

## Customisation

The grid is controlled via CSS variables defined in the :root of the grid-paper.css file.

You can override any of the following variables to customize the look:

```
:root {
  --grid-width: 40px;           /* Size of each grid square */
  --line-width: 1px;            /* Thickness of grid lines */
  --color-background: #fffee5;  /* Background color */
  --color-grid-lines: #bfbdaa;  /* Grid line color */
  --grid-offset: 20px;          /* Offset to center the grid */
}
```

Example (override in your own CSS file):

```
:root {
  --grid-width: 32px;
  --color-grid-lines: #a8a797;
}
``` 

## Notes
- The grid pattern is purely visual. It does not affect layout.
- Writing custom CSS in a different file that overrides the "body" element may impact this grid.
- Default colors are designed to be subtle so it doesn't distract from primary content.
- Best used as a background element for creative or experimental pages that need to look unique visually (e.g. for social media).
