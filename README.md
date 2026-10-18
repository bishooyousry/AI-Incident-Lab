# AI INCIDENT LAB: THE POINT OF NO RETURN — Skills Bank | GitHub Pages

*Three real, documented AI failures. You are the person who could have prevented the next one.*

One file (`index.html`), no build, no keys, no backend. English / العربية (RTL). About 4–5 minutes per case file, three cases (≈ 13–15 minutes); a participant can also open just two.

## Publish (GitHub Pages)
1. Create a **public** repo. Upload `index.html` and `.nojekyll` to the root.
2. Settings → Pages → Deploy from branch `main` / root. Wait ~1 minute.
3. Open `https://<user>.github.io/<repo>/` → **Trainer** (top right) → PIN `2026`.
4. Always open the published link (not the file from your computer, not a preview window).

## What I kept from your kit — exactly
- The **three real cases** (Mata v. Avianca 2023 · Moffatt v. Air Canada 2024 · NEDA Tessa 2023), copied **programmatically and verbatim**: summaries, roles, exhibit titles and text, the four root-cause options and four safeguard options of each case, the expected decisions and explanations, and the **source link of every case** (shown on the case page, on the verdict page, on the front page and in the trainer module). English and Arabic case text were not edited. The tests compare what the game shows with the original kit data.
- **No fact was added.** The ticker and clipping headlines are rewritten from facts that are already in the kit and are labelled “written for this exercise”.
- The kit’s **scoring formulas**: root causes and safeguards = 30 × (correct found ÷ 3) − 10 per wrong selection (min 0); decision = 30 if it matches the expected one, 12 for the other cautious option, 0 for “continue unchanged”; **safe alignment** = the expected decision AND at least 20/30 on both root causes and safeguards.
- The kit’s warnings: case outlines are factual summaries while exhibit wording and choices are educational reconstructions, not direct quotations; this is educational practice, not professional legal or health advice; Tessa was not a ChatGPT-style generative chatbot.

## What is new
- **Look and feel — a press archive:** a newspaper front page on the landing page, a live news ticker, news-clipping cards, court-document exhibits that start **sealed behind redaction bars** and are unsealed by tapping, a red-pen checklist for root causes and safeguards, a decision memo, a stamped verdict (SAFE ALIGNMENT / RISK REMAINS) and, at the end, **your own front page** with a headline built from your results (a template — labelled “training edition, not a news report”).
- **Live multiplayer** (the kit’s trainer view only read the same browser’s localStorage): ntfy.sh relay + SSE, session codes, joined participants, per-case decisions and scores, **Reveal / Hide leaderboard**, CSV export, connection status, reconnection, history replay, duplicate protection.
- Arabic / English on every screen including the trainer (the kit’s Egyptian-dialect interface text was rewritten in Modern Standard Arabic; the case content is untouched), sound effects, coins and hints, progress, copy / download / print.
- **The 10-point “length of the written explanation” part of the kit’s score is replaced** (the kit itself called it a rough heuristic) by transparent criteria: your **first two actions** (2 each if effective) 4 · your **reasons** (2 each if sound, −2 if unsound) 4 · your **own words** (8+ words) 2 — a rough completion check, not an assessment of substance. Each case is out of 100; the session total is out of 300. Ranks: ≥250 Chief Incident Reviewer · ≥190 Senior · ≥120 Reviewer · else Trainee.

## How to play
Enter your name or team’s name, then for each of the three case files: **read the clipping** (headline, summary, role, source link) → **unseal the three exhibits** → **find the root causes** (tap to circle; wrong picks cost points; correctly ignored distractors are explained) → **choose safeguards** → **decide** STOP / continue only with strict safeguards / continue unchanged → **write the incident report** (two first actions, reasons, own words). Each case ends with a verdict page showing the score breakdown and **what actually happened** (the kit’s Exhibit C) with the source. Coins: 250 at start, hint = 50 (guidance only, one per step). Coins break ties.

## Trainer
5-character session code, **+ New session** (up to 6), **Reset**, **Close**, session name, copy EN/AR link, **Projector view**, live table (three case chips — teal = safe alignment, red = filed but risk remains, amber = in progress —, decisions S/R/C coloured against the expected one, root-cause and safeguard scores, safe alignment x/3, hints, coins, score, progress), expandable rows (each case’s choices with ✓/✗, first actions, reasons, sanitized explanation, sub-scores), a **Debrief panel** (decision distribution per case, most-chosen wrong root cause and unsafe safeguard, safe-alignment rate), a collapsible **CASE FILES, SOURCES & ANSWER KEY (trainer only)** module (every case with its source links, exhibits, options with distractors flagged, expected decisions, formulas), Reveal/Hide leaderboard, CSV export, backup import. About **6 messages per player**.

## Please check before presenting (honest limits)
- **I cannot browse the web, so I have not verified the real-case facts or the links.** Every fact comes from your kit; please open the three source links yourself. One observation: the Moffatt v. Air Canada source in your kit is a **third-party summary page**, not the tribunal’s own decision — if you have the official decision, swap the link (one line in the data).
- The scoring is rule-based coaching, not an expert assessment; exhibit wording and choices are reconstructions.
- The trainer PIN `2026` only hides the interface. The relay is public: only choices, scores and a short sanitized explanation are sent (emails, links and long digit strings are removed). Tell participants not to write confidential details.
- **Not yet tested on real ntfy.sh or across real devices.** Tested in a headless browser against a local relay that imitates ntfy (SSE, polling, storage blocked, Arabic, an emulated touch phone using taps, clipboard, downloads, message sizes under 4096 bytes; 68 checks). The print dialog cannot be automated: the print page is built and the print call is verified — try **Print my front page** once in a real browser. ntfy.sh free limits are per IP (~250 publishes/day): ~35 players on one network is a safe size.

## Two-device test checklist
1. Laptop: published link → Trainer → PIN 2026. Note the 5-character code and `● LIVE`.
2. Phone: open the player link (or type the code) → name or team on the press pass → **Open the archive**. Tap a column of the front page.
3. Laptop: the participant appears in seconds. Phone: open case 1, read the clipping, unseal the exhibits (compare the text with your kit).
4. Phone: circle root causes and safeguards (try a wrong one), decide, file the report. Laptop: the case chip, decision chip and scores appear; expand the row.
5. Phone: finish the other two cases (try leaving one halfway and coming back). Laptop: all three chips, safe alignment, debrief panel.
6. Phone: **your front page** appears; try Copy, Download and Print. Laptop: **Reveal leaderboard** → opens by itself on the phone; **Hide** closes it.
7. Switch language on both; check RTL and that nothing is cut off on the phone.
8. Refresh the phone mid-case → **Resume the investigation** continues. Laptop: **Reset session** → new code. Check Sound ON/OFF and “reduce motion”.
