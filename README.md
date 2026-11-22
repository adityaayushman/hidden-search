# Hidden Search

**Live demo:** https://adityaayushman.github.io/hidden-search/

An expanding search bar in plain HTML, CSS and JavaScript, built while following the course. No frameworks, no build step.

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

## Credits

This is an exercise from the [50 Projects in 50 Days](https://github.com/bradtraversy/50projects50days) course by Brad Traversy (original: `hidden-search`). The code is unchanged from the original. It is used under the MIT license in `LICENSE`.
