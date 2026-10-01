# Working state for the next session (October 1, 2026, morning)

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

## Current state (October 1, 2026, morning)
- F2 homepage = the copper pipe concept (design/wow_pipe.py, built by design/build_wow_pipe.py, which design/build_mockups_f.py now calls at the end, so `python3 design/build_mockups_f.py` writes f2-home.html with the pipe). Phone LCP 1.29 s. Not yet tested on a real iPhone (Safari needed tiling workarounds).
- Other concepts kept for history: f2-home-wow-xray.html, f2-home-wow-blueprint.html, f2-home-house-3d.html, f2-home-house-photo.html (Pexels photo, license in design/assets/house-photo-SOURCE.md). The flat drawing house_illustration.py is still used by F, F3 and the slab and emergency pages' imports.
- Request Service button in header and footer opens the form (fields as on the old site, email required). Footer option C (red band). The van footer D was rejected.
- Real reviews in the mockups (bm.REVIEW_PICKS, build_mockups.py); signatures without office name; Local Guide levels still missing.
- Spinning meter clip replaces photo 79 (fg.meter_fig), caption city Plano (Denys).
- Service tiles: slab 162, emergency 112, water heater 50. Photo 112 is Denys's approved photo for the Denys block (no separate portrait needed).

## Next steps
- Extend the pipe look to the slab and emergency pages if Denys wants it; check the pipe animation on a real iPhone.
- Then: Astro project start (see "Not started yet").

## Waiting for Denys
- Approve the reviews proposal (docs/reviews-proposal.md, page reviews-proposal.html); he wants Claude to review it first. Local Guide levels for review signatures still need checking on each Google profile.
- Dictate: photos 13, 14, 21, 104, 131, 132, 149, 160; city for 8; pairs 9/10 and 29/30 (cities differ by location); what the roof pipe on 93/94 is.
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
