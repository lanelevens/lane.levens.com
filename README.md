# lane.levens.com

Portfolio site for Lane Levens — fine woodworking & creative fabrication.

## Stack

Plain HTML / CSS, hosted on GitHub Pages.

```
lane.levens.com/
├─ index.html         Single scrolling page
├─ css/style.css      All styles (brand tokens at top)
├─ images/            Photos
└─ CNAME              Custom domain
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
| `--ink`      | `#111111` | Black for body, dark sections           |
| `--display`  | Anton     | Bold condensed sans for headlines       |
| `--body`     | Inter     | Body type                               |

## Outstanding (`TODO` markers in HTML)

- Second scholarship name (currently placeholder).
