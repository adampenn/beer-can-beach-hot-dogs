# Freedom Isn't Free, But Our Hot Dogs Are

Single-page website for the annual free hot dog stand on Beer Can Beach,
Sacramento River, Chico CA. Open July 4th only, 11 AM – 5 PM. Eight years running.

Everything is static: `index.html` + `photos/`. No build step.

## Preview locally

```sh
python3 -m http.server 4747 --directory .
# open http://localhost:4747
```

## Deploy (pick one)

**Netlify Drop (easiest, free, no account needed to start):**
drag this folder onto https://app.netlify.com/drop — done. Free subdomain like
`beercanbeachhotdogs.netlify.app`; add a custom domain later if he buys one.

**GitHub Pages:** push this folder to a repo, Settings → Pages → deploy from
`main` branch root.

**Render:** New → Static Site, point at the repo, publish directory `.`.

A fun cheap domain if he wants one: `freedomisntfreebutourhotdogsare.com`,
`beercanbeachdogs.com`, or a `.us` variant (very on-brand).

## Google Business Profile setup

Do this from HIS Google account at https://business.google.com → "Add business".

| Field | Value |
|---|---|
| Business name | Freedom Isn't Free, But Our Hot Dogs Are |
| Category | Hot dog stand |
| Location | Do NOT add a street address. Choose "I deliver goods and services to my customers" → service area: Chico, CA (it's a sandbar; no address exists) |
| Service area | Chico, CA 95928 |
| Hours | Set regular hours to **Closed** for all seven days, then use **Special hours**: add July 4 each year, 11:00 AM – 5:00 PM |
| Phone / website | His phone (optional) + the deployed site URL |
| Description | Free hot dogs on Beer Can Beach every July 4th, 11 AM to 5 PM — eight years running. One grill, one beach, one day a year. Hot dogs, buns, condiments, and seconds: all free. Float in, paddle over to the stars-and-stripes canopy, and grab lunch on America's birthday. Closed the other 364 days. |
| Photos | Upload the shots in `photos/` — set `tent-river.jpg` as the cover |

Press: the Enterprise-Record covered the stand — ["Hot dogs attract river riders
to Beer Can Beach"](https://www.chicoer.com/2025/07/08/hot-dogs-attract-river-riders-to-beer-can-beach/)
by Michael Weber, July 8, 2025. It names Brendan Close (Chico State University
Farm) as the host, ~300 hot dogs, and says the tradition goes back **about 10
years** as of 2025 — worth confirming the real start year with Brendan before
locking "Est. 2019" on the site.

Notes:
- Verification: with no storefront, Google usually offers video or phone
  verification. Video verification on the beach isn't practical — do it from
  home; showing the banner/tent/grill equipment satisfies "proof of business."
- After it's live, make a **Google Post** each late June announcing the date
  ("Open July 4th, 11–5, Beer Can Beach") — posts show up right in the profile.
- Mark it "Temporarily closed" is NOT needed — closed regular hours + special
  hours on July 4 is the correct pattern for a once-a-year business.
