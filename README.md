# Butt Nugget Farm website

Static one-page site for **buttnuggetfarm.com**: hatching eggs and chicks, Gidgegannup, Perth Hills WA.
It's plain HTML and CSS with no build step, based on Direction A ("Knitted Keepsake") from the Claude Design canvas.

```
index.html     the whole page
styles.css     all styling (colours are CSS variables at the top)
images/        hero art, logo, apple-touch icon
CNAME          custom domain for GitHub Pages
docs/          design brief (not part of the site)
```

## Before going live, replace these placeholders

Search `index.html` for each of these:

| Find | Replace with |
|---|---|
| `61400000000` (appears 6 times) | your mobile in international format with no leading 0, e.g. `61412345678` |
| `0400 000 000` | your mobile as people read it |
| `[CASH / PAYID / BANK TRANSFER]` | how you take payment |
| `[YOUR NAMES]…` paragraph in About | 2–3 sentences about you |
| `[FAMILY PHOTO]` / `[FLOCK / FARM PHOTO]` | put photos in `images/` and swap each `<div class="photo-placeholder">…</div>` for `<img src="images/your-photo.jpg" alt="…">` |

If you set a Facebook username, replace `profile.php?id=61593547466551` everywhere with it.

## Updating
Nothing on the site lists stock or prices. Those live on Facebook, so the site only needs editing when your contact details or story change.
