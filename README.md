# Eywa Website

Marketing site for **Neytiri Eywafarm Agritech Private Limited** — [eywa.farm](https://eywa.farm).

A self-contained static site (no build step, no framework) covering the
company, its two products (RootsTalk and Cosh), legal pages, and contact.

## Pages

| File | Purpose |
| --- | --- |
| `index.html` | Homepage — company overview |
| `cosh.html` | Cosh product page |
| `rootstalk.html` | RootsTalk product page |
| `contact.html` | Contact form / details |
| `privacy.html` | Privacy Policy (12 sections) |
| `terms.html` | Terms and Conditions (21 sections) |
| `cancellations.html` | Cancellation & Refund Policy (12 sections) |

## Local preview

```bash
# Any static server works. Quickest:
python3 -m http.server 8000
# Then open http://localhost:8000
```

## Stack

- Hand-written HTML + inline CSS — earthy palette (soil, bark, moss, fern, leaf, shoot, amber, gold)
- Typography: Playfair Display (serif) + DM Sans (body) + DM Mono (technical)
- Only external dependency: Google Fonts

## Deployment

Will be hosted on the same self-managed server stack as
[cosh2.eywa.farm](https://cosh2.eywa.farm) — details TBD.

## Notes

- `cosh.html` will eventually embed Cosh's `/embed/explore` visualization
  via an `<iframe>`.
- The three legal pages were rebuilt from the canonical live-site source
  documents — verbatim, with structure preserved.
