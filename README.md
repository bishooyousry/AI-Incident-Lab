# Skills Bank — AI Incident Lab: The Point of No Return

A standalone bilingual EN/AR interactive incident-analysis training game grounded in three documented events:

1. **Mata v. Avianca** (2023): [U.S. District Court order](https://law.justia.com/cases/federal/district-courts/new-york/nysdce/1%3A2022cv01461/575368/54/)
2. **Moffatt v. Air Canada** (2024): [Tribunal decision summary and citation](https://www.burhandogusayparlar.com/ai-decisions/moffatt-v-air-canada/)
3. **NEDA Tessa** (2023): [WIRED report](https://www.wired.com/story/tessa-chatbot-suspended/). Tessa was **not a ChatGPT-style generative model**.

Case outlines are factual summaries; evidence card wording and learner choices are educational reconstructions, not direct quotations.

## GitHub Pages

Upload `index.html`, `skillsbank-logo.png`, `.nojekyll` and the rest of this kit to your repository root. In **Settings → Pages**, select **Deploy from a branch**, branch **main**, folder **/(root)**. Wait for the published URL.

## How to play

Enter one name field (participant or team), pick a case, inspect all three exhibits, identify root causes, choose safety controls, decide **STOP**, **restricted use**, or **unrestricted continuation**, justify the decision, and receive a scored debrief. Learners can play all three incidents.

## Trainer

Use the Trainer dashboard at the login screen with code `2026` to inspect attempts and export CSV. **Important:** this is only a UI gate, not authentication. Records are stored in **browser localStorage**. They do not sync across learners' devices or appear on a trainer's separate laptop. For live cross-device monitoring you need a secure shared backend with actual role-based authentication, which this static kit does not include.

## Scoring

The 100-point score is 30 for identifying risks, 30 for selecting proper safeguards, 30 for the go/no-go recommendation, and up to 10 based on the length of the written explanation. Length scoring is only a rough heuristic, not an intelligent review of substance. A safe alignment badge additionally requires strong risk/control selection and the expected verdict.

This is educational practice and not professional legal or health advice.
