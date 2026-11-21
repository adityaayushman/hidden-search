# Hidden Search

An expanding search bar in plain HTML, CSS and JavaScript. No frameworks, no build step.

## Behaviour

The search bar shows only a button. Clicking the button expands the input and focuses it. Clicking again collapses it.

## Run it

Open `index.html` in any modern browser, or serve the folder with a static server:

```bash
npx serve .
```

## Files

| File | Purpose |
|---|---|
| `index.html` | Markup, with Font Awesome icons loaded from a CDN |
| `style.css` | Layout and the expand/collapse transition |
| `script.js` | Toggles the `active` class and focuses the input |

## Notes

This is a UI component demo. The input does not run a search.
