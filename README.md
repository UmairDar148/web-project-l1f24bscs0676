# Plashoe – Web Technologies Project 1 (Assignment 1)

**Theme:** Plashoe, a sustainable shoe store (Route A: recreate a WordPress demo store, "Recycled Shoe Store 04").
**Approval record:** _(link your signed sheet / email screenshot here)_

## Pages in Assignment 1 (HTML only, CSS comes later)

| # | File | What it contains |
|---|------|------------------|
| 1 | `index.html` | Headings, paragraphs, block elements (`div`, `section`), inline elements (`span`, `strong`, `em`, `a`), images, links to all 6 pages |
| 2 | `media.html` | Image, video, audio, ordered list, unordered (nested) list, one data table |
| 3 | `register.html` | Form with all required input types and validation attributes |

Pages 4 to 6 (`services.html`, `portfolio.html`, `contact.html`) are Assignment 2. The nav already links to them, so those links stay dead until then.

## Where CSS will plug in later
Each page has a commented-out `<link rel="stylesheet" href="....css">` in `<head>` and meaningful `id` / `class` names, so Assignment 2 / CSS needs no HTML rewrite.

## Quick revision notes (viva)
- `<!DOCTYPE html>` tells the browser this is HTML5. `lang="en"` helps screen readers.
- `<label for="x">` + `<input id="x">` link a label to its field (clicking the label focuses the input).
- `required` = cannot submit empty. `readonly` = visible and submitted, cannot edit. `disabled` = greyed out and NOT submitted.
- `min` / `max` limit numbers, dates, time and range. `minlength` / `maxlength` limit text length.
- `checked` pre-selects radio/checkbox. `selected` pre-selects an `<option>`.
- Block elements start a new line (`div`, `p`, `section`). Inline elements stay in the line (`span`, `strong`, `a`).
- `<ol>` = numbered list, `<ul>` = bullets. Table: `thead` / `tbody` / `tfoot`, `th scope="col"`.

## Media and image sources
- Photos: Unsplash (free licence), hot-linked by URL.
- Video and audio samples: MDN Web Docs `interactive-examples` (CC0).
- If any link stops loading, replace the `src` with another Unsplash/Pexels URL; the `alt` text keeps the page readable.

## AI usage log (fill this in honestly)
| Tool | What I asked | What I changed |
|------|--------------|----------------|
| _(e.g. Claude)_ | _(e.g. generated first draft of the 3 HTML pages)_ | _(e.g. rewrote text, edited form fields, ...)_ |

## Git plan (needs 8+ commits over 4+ days)
Suggested messages: "Add home page structure", "Add hero and about sections", "Add best sellers cards",
"Add media page with video and audio", "Add lists and size table", "Add register form fields",
"Add validation attributes", "Add README and tag assignment-1".
Then: `git tag assignment-1` and push the tag.
