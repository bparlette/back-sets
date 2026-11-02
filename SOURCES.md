# Source map (scout verdicts, Nov 1, 2026)

Every entry in the bank is download-verified (HTTP 200 + image signature + dimensions from bytes).

## Strongest veins
1. **The Screencaps network** (Movie-Screencaps + Animation Screencaps) — full films capped frame-by-frame; ASC lists 1,026 animated films. **Trap: the CDN is referer-gated — naked hotlinks 403.** Gallery pages must mirror these files or fetch with the site referer.
2. **Fandom wikis** — the TV-set backbone: curated room/set stills on static CDN URLs with an open API (Seinfeld's Apartment 4A article alone had 99 files). Hotlinkable.
3. **Frinkiac + Morbotron** — dialogue-search API → direct JPGs for every quotable Simpsons/Futurama frame. Trap: dialogue-indexed only; visual-only moments don't resolve.
- Runner-up: **TrekCore** — every Star Trek episode in HD as plain files.

## Feasibility of 1,000
- **Movies: YES, comfortably** — 150–250 famous films × 4–6 scenes clears it from Movie-Screencaps alone.
- **Cartoons: YES** — ASC's directory + Frinkiac/Morbotron's indexed TV animation.
- **TV sets, strict (famous rooms only): NO** — the iconic-room universe tops out ~200–250. It flips to YES if the category widens to iconic TV scenes/locations.
- Working split for 1,000 total: **~450 movies / ~350 cartoons / ~200 sets**.

## Dead ends / gated
- **FilmGrab** — 4,204-film catalog behind a hashcash JS bot challenge (browser-only harvesting). Note: filmgrab.com without the hyphen is a parked domain.
- **TMDB / Fanart.tv** — images are open CDN files, but path discovery needs a free API key.
- **MovieStillsDB** — no direct files exposed (membership/watermark tier).
- **Wikimedia Commons** — open and hotlinkable, but "stills" are often trailer frames or publicity photos (labeled as such in the sample).
