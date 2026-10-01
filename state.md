# Working state for the next session (October 1, 2026, about 01:30)

Read CLAUDE.md first (all rules and decisions), then this file, then docs/journal.md. Talk to Denys in Russian, plain words.

## Where things are
- Project: /Users/denyskavaler/Desktop/fppplumbing-site, GitHub private repo request-fpp/fppplumbing-site (branch main). Commit small, plain messages, end with the Co-Authored-By line; stage files by name, never `git add -A` while a helper agent is working.
- GitHub CLI: ~/.local/bin/gh (logged in as request-fpp).
- Journal: docs/journal.md (Russian) published by `python3 tools/publish_journal.py` to https://fpp-journal.pages.dev and https://request-fpp.github.io/fpp-journal/ (public repo request-fpp/fpp-journal, clone in journal-site/, ignored). Every docs/*.md becomes a page (journal.md is index.html; this file is state.html; reviews-proposal.md is reviews-proposal.html). Publish after every finished block, without being asked. Robots allowed, no noindex.
- Local preview server for mockups: from the project root run `python3 -m http.server 8765 --bind 127.0.0.1`, then open http://localhost:8765/design/mockups/compare-f-f2-f3.html or f2-home.html, f2-slab.html, f2-emergency.html. Photo sheet: http://localhost:8765/photos/contact-sheet.html. Caption review: http://localhost:8765/photos/captions-review.html.
- Offscreen full size screenshots: the scratchpad has a compiled WebKit tool `snap3` (usage: snap3 url width height outprefix scroll1,scroll2,...; prints page info JSON with horizontal overflow and small tap targets). The browser pane is small; use snap3 for before and after images.

## Design (chosen: F2)
- Generators: design/build_mockups.py (all text constants, PHOTOS, ANNOT, captions loading), design/build_mockups_fg.py (shared parts: header, footer, creds_f, numbers row, socials, SVC service tiles, CSS), design/build_mockups_f.py (F, F2, F3 pages: home, slab, emergency). Rebuild with `python3 design/build_mockups_f.py` and `python3 design/build_mockups_fg.py` (and build_mockups.py / build_mockups_de.py if shared slots change).
- Speed check: `python3 tools/perf_budget.py design/mockups/f2-home.html design/mockups/f2-slab.html design/mockups/f2-emergency.html` (budget 1.6 s on phone; last: 1.34, 1.43, 1.20).
- Done today: numbers row 4,500+ / 450+ / 24/7 / 2 with light type; license line "Responsible Master Plumber, License M-44816" (footer, Denys block, credentials); BBB official seal linked; Yelp 5.0; footer rebuilt with the original logo; slab hero photo 42; slab tile and detection step photo 161 (Denys with the leak detector, from the old site); photo 112 in the Denys block; no marker marks on finished brazed joints 42 and 45; Liane W. added to leak detection.

## In progress when this file was written
A helper agent was redoing three things in build_mockups_fg.py and build_mockups_f.py, with before and after images in design/review/:
1. The house cutaway on the F2 homepage first screen (Denys: "the block with the foundation is crooked"): straight section drawing, same size unrotated photo tiles, one label per zone under its tile, one red point per zone, orthogonal copper pipes, each service once, chips deduplicated, phone readable.
2. The credentials row, final order from Denys: Responsible Master Plumber / License M-44816; Google 5.0 with Plano and Frisco links stacked; Thumbtack Top Pro with Yelp 5.0 stacked under it; Founded 2022 / Fully licensed and insured; the BBB seal at the end with A+ rating. Light band, one row of five cells.
3. Footer: light background with the original logo directly on it (no white plate), saturated logo red strip like the header, navy text, icon row possibly on a navy bar. Denys found the white plate on the dark footer sad.
If design/review/compare-*.png do not exist or the work is half done, check `git log` and the generated pages, finish it, and show Denys before and after.

## Waiting to be applied right after that agent finishes
- Service tiles (SVC in build_mockups_fg.py): Slab leak repair -> 162 (still from video 125: water spraying from a pinhole on copper under the slab); Emergency plumbing -> 112 (Denys stopping water spraying from the wall); Water heater -> 50 (instead of 43). Web files 162 and 50 are already in design/img; 112 exists.
- Spinning meter: replace the marked photo 79 (ANNOT circle) on the F pages with the real looping clip design/video/meter-spin.mp4 / .webm (poster design/video/meter-spin-poster.webp; 480x480, muted, loop, playsinline, autoplay only without prefers-reduced-motion; cut from video 72, sped up 2x, meter serial number cropped out). Caption should say it is the meter leak indicator turning, sped up.
- When Denys's uniform portrait appears in photos/, number it with tools/photo_contact_sheet.py, optimize with tools/optimize_photos.py, put it in the Denys block (PHOTOS["owner"]), and keep 112 only on the emergency tile.

## Waiting for Denys
- Approve the reviews proposal (docs/reviews-proposal.md, page reviews-proposal.html); he wants Claude to review it first. Local Guide levels for review signatures still need checking on each Google profile.
- Dictate: photos 13, 14, 21, 104, 131, 132, 149, 160; city for 8; pairs 9/10 and 29/30 (cities differ by location); what the roof pipe on 93/94 is.
- His portrait in uniform (he will drop it in photos/).
- Final look at the F2 fixes above.

## Files that changed today (main ones)
CLAUDE.md, docs/journal.md, docs/state.md, docs/reviews-proposal.md, tools/publish_journal.py, tools/build_all_reviews.py, tools/build_reviews_ledger.py, tools/parse_yelp_pdf.py, tools/photo_contact_sheet.py, tools/photo_city_guess.py, tools/optimize_photos.py, tools/perf_budget.py, design/build_mockups.py, design/build_mockups_fg.py, design/build_mockups_f.py, design/mockups/*, design/img/*, design/video/meter-spin.*, design/assets/fpp-logo-*.webp, photos/index.csv, photos/captions.csv, photos/captions-en.csv, photos/city-guess.csv, photos/thumbs/*, reviews/all-reviews.csv, reviews/ledger*.{csv,md}, reviews/proposed-placement.{csv,md}, reviews/raw/*.json, source/gbp-takeout/ (JSON only; the 1.9 GB Takeout zip in reviews/ is git ignored), source/approved-text-edits.md.

## Data sources ready
- Reviews: reviews/all-reviews.csv (Google 131 from Takeout with direct links, Thumbtack 249, Yelp 27 of 29). Old site use in reviews/ledger.md with decisions in reviews/ledger-decisions.csv.
- Search Console: source/gsc/ (UI exports and API page plus query); API key in secrets/ (git ignored), script tools/gsc_page_query_export.py.
- Keyword map and cannibalization: seo/.
- Photos: photos/originals (162 files, not in git), photos/index.csv numbers, photos/captions.csv (Denys's words, city_final), photos/captions-en.csv (English captions, alt, pages, pairs, flags).

## Not started yet (next big steps after design approval)
Astro project, page content build from the approved texts and the edits file, redirect map, schema, Cloudflare Pages preview with Access and noindex for the SITE (not the journal), forms to Telegram via a Worker, GA4 carry over.
