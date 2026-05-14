# lane.levens.com

Portfolio site for Lane Levens — fine woodworking & creative fabrication.

## Stack

Plain HTML / CSS, hosted on GitHub Pages with the custom domain `lane.levens.com`.

```
lane.levens.com/
├─ index.html         Home / hero
├─ work.html          Portfolio
├─ about.html         Bio, experience, education, awards
├─ contact.html       Contact + commission info
├─ css/style.css      All styles (brand tokens at top)
├─ images/            Project photos (web-optimized)
└─ CNAME              Custom domain for GitHub Pages
```

## Local preview

```sh
cd lane.levens.com
python3 -m http.server 8000
# then open http://localhost:8000
```

## Brand tokens

Defined as CSS custom properties at the top of `css/style.css`:

| Token        | Value     | Notes                                   |
|--------------|-----------|-----------------------------------------|
| `--red`      | `#E5392B` | Vermilion — display headlines, accents  |
| `--cream`    | `#E8E5DA` | Warm off-white ground                   |
| `--ink`      | `#111111` | Black for stars, body, dark sections    |
| `--display`  | Anton     | Bold condensed sans for headlines       |
| `--body`     | Inter     | Body type                               |

## Deploy

1. Push to GitHub.
2. In repo Settings → Pages, set source to `main` branch, root.
3. Point `lane.levens.com` DNS at GitHub Pages:
   - `A` records for the apex → `185.199.108.153`, `185.199.109.153`, `185.199.110.153`, `185.199.111.153`
   - `CNAME` for `www` → `lanelevens.github.io`
4. Enable "Enforce HTTPS" once the cert provisions.

## Outstanding work (`TODO` markers in HTML)

- Confirm whether **LACMA** experience should be included (mentioned in `info.txt` but not on resume).
- Confirm the second scholarship from `info.txt` (placeholder name there).
- Write copy for each portfolio project (description, technique, year).
- Add photos for: Princess Desk, Aleksandar Inc. millwork, Coffeeshop Refurbishment, theater set work.
- Optional: add the brand logo asset and headshot when ready.
