# Tirinyi Safaris website

A one-page tours and travel site. Open `index.html` in a browser to preview it.

## Structure

```
tirinyi-safaris/
  index.html      All the HTML, CSS and JavaScript
  photos/         Every photo used on the site
  logo/           Logo files
    tirinyi-safaris-logo.png           Transparent logo used in the header and footer
    tirinyi-safaris-icon.png           Antelope icon used as the browser tab icon
    tirinyi-safaris-logo-original.jpg  The original logo on its green background
  README.md
```

Keep `index.html`, `photos/` and `logo/` together, or the images won't load.

## Common edits

- **Colours and fonts:** the `:root` block at the top of the `<style>` section.
- **Section text:** look for the comments `<!-- HOME -->`, `<!-- ABOUT -->`, `<!-- DESTINATIONS -->`, `<!-- EXPERIENCES -->`, `<!-- GALLERY -->` and `<!-- CONTACT -->`.
- **Logo size:** `.logo img` (header) and `.logo-foot img` (footer) in the `<style>` section.
- **Swap a photo:** put the new file in `photos/` and change the matching `src="photos/..."`.
- **Add a gallery photo:** add the file to `photos/`, then add a line to the `PHOTOS` list in the script, for example
  `{f:'rwenzori-trek.jpg', c:'Climbing in the Rwenzori Mountains', t:['hiking']},`
  The `t` tags decide which gallery filters show it: `gorilla`, `chimp`, `game`, `boat`, `birding`, `walks`, `hiking`, `adventure`.
- **Gallery filters:** the `CATS` list in the script.
