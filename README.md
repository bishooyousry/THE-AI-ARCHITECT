# THE AI ARCHITECT: Design Your Assistant — Skills Bank | GitHub Pages

One file (`index.html`), no build, no keys, no backend. English / العربية (RTL). Target: 8–10 minutes, individual, with a reusable blueprint for the next activity.

## Publish (GitHub Pages)
1. Create a **public** repo. Upload `index.html` and `.nojekyll` to the root.
2. Settings → Pages → Deploy from branch `main` / root. Wait ~1 minute.
3. Open `https://<user>.github.io/<repo>/` → **Trainer** (top right) → PIN `2026`.
4. Always open the published link (not the file from your computer, not a preview window).

## About the source activity (please read)
- The deck's notes for this activity (slide 73, labelled “Activity 3” in the notes and “Activity 4” on the handout title) give: the goal — *define the Role, Scope, Inputs and Outputs of an AI assistant for your own job before building one for real*; 8 minutes, individual; the example name **“Meeting Notes Assistant”**; the tip that **Scope is the most important box because it teaches boundaries**; and two debrief questions (used verbatim in the facilitator guide).
- **The worksheet handout itself is not in the attached deck** (slide 73 only shows a decorative robot picture). So the Meeting Notes template, the scope cards, inputs, outputs and all feedback texts are **illustrative material written for this game**, not the original worksheet text. If you send the handout, the template can be aligned to it.
- Slides 76–77 (“Build Your Own Assistant”) say the next step needs a **name, description and system instructions**, plus knowledge files. The blueprint therefore exports a name, a role (description), generated assistant instructions, and an inputs list you can turn into knowledge files.

## The studio and the five phases
- **Landing = an AI Creation Studio** (not a hero page): a large wireframe assistant on a holographic floor, four inactive system nodes (Role · Scope · Inputs · Outputs), floating operator / status / template / blueprint-preview panels, a creation meter at 0% and a **CREATE YOUR ASSISTANT** ignition pad.
1. **Initialization** — name the assistant, pick a work purpose (meeting summaries, email drafting, task organization, research support, or a custom task — all optional scaffolds), pick one of six avatars, optionally start from the Meeting Notes template (fully editable). The assistant appears as an incomplete holographic model.
2. **Configure four systems** (any order, each powers up a part of the avatar):
   - **Role** — choose the job type, the intended user (with a warning for external customers) and write the job in one sentence.
   - **Scope** — place eight capability cards into *Within scope / Outside scope / Needs human approval*, then add at least one boundary of your own.
   - **Inputs** — for each possible input decide *Use it / Anonymize first / Never share*; add your own.
   - **Outputs** — format, length, quality expectations, human-review checkpoints and the deliverable in one sentence, with a live preview.
3. **Boundary test** — three requests generated **from your own design** (one from each of your zones; if a zone is empty, a request that exposes the gap is used and labelled). You decide: within scope / outside scope / needs human approval. The consequences of loose boundaries are explained.
4. **Blueprint assembly** — nine editable fields (name, purpose, user, role, scope, exclusions, inputs, outputs, human review checkpoints), a completeness meter, generated assistant instructions (editable), **Copy Blueprint, Download .json / .txt, Copy Instructions**.
5. **Activation** — the avatar powers on; completed systems, completeness, boundary-test result, hints, coins, score and the final blueprint, with a clear statement that **this is a design blueprint, not a deployed assistant**.

## Scoring (transparent, rule-based)
| Part | Points |
|---|---|
| Role (100) | job type fits the purpose 25 (10 otherwise) · user chosen 25 · sentence of 8+ words 30 · states the outcome (“so that…”) or 14+ words 20 |
| Scope (150) | 15 per card in the recommended zone (8 cards = 120) · −10 per must-NOT card placed as allowed · +30 for adding your own boundary |
| Inputs (100) | 15 per input handled as recommended (6) · +10 for adding your own input |
| Outputs (100) | format 20 (8 if unusual) · length 10 · quality up to 30 (−10 per trap) · human review 30 (10 if a trap is also chosen) · deliverable sentence 10 |
| Boundary test (60) | 20 per request answered consistently with your design |
| Blueprint (40) | 40 × completeness % (7 key fields) |
Max **550**. Coins: 250 at start, hint = 50 (role sentence suggestion · place one card · set one input · show the output recommendation · rule out an option in a boundary request). Coins break ties. Ranks: ≥470 Master Architect · ≥360 Senior Architect · ≥240 Architect · else Apprentice.

## Trainer
5-character session code, **+ New session** (up to 6), **Reset**, **Close**, session name, copy EN/AR link, **Projector view**, live table (phase, assistant name and purpose, four system lights + boundary-test score, blueprint completeness, hints, coins, score, progress), expandable rows with the full submitted blueprint, **Debrief panel** (systems completed, purposes chosen, boundary-test and completeness averages), Reveal/Hide leaderboard, CSV export (includes the blueprint fields), backup import. About **10 messages per player**.

## Honest limits
- **No AI model is called and no assistant is created.** The instructions are a *starting point* for ChatGPT, Copilot or Gemini; knowledge files, tools and sharing differ by platform and company policy.
- Recommended zones, inputs handling and quality rules are authored guidance; the keyword-free scoring is rule-based and shown to the player.
- **Not yet tested on real ntfy.sh or across real devices.** Tested in a headless browser against a local relay that imitates ntfy (SSE, polling, retries, storage blocked, Arabic, an emulated touch phone using taps; 68 checks). Run the two-device checklist before a live class.
- ntfy.sh free limits are per IP (~250 publishes/day, ~30 live streams): ~25 players on one network is the safe size; use `?relay=` with your own server for more. Keep backup/import as the safety net.
- The `2026` PIN only hides the interface. The relay is public: participants must use **made-up or approved, non-sensitive information only**; the blueprint text is sent to the trainer through it.

## Two-device test checklist
1. Laptop: published link → Trainer → PIN 2026. Note the 5-character code and `● LIVE`.
2. Phone (mobile data or another Wi-Fi): open the player link (or type the code) → enter a name → **Create your assistant**.
3. Laptop: the designer appears in seconds (toast + sound). Phone: name the assistant, pick a purpose and an avatar, **Begin design**.
4. Phone: configure Role, then Scope (place cards by tap, add your own boundary), Inputs, Outputs. Laptop: the system lights, assistant name/purpose and score update after each lock.
5. Phone: boundary test (answer one request wrongly on purpose to read the consequence), then the blueprint: edit a field, Copy, Download .json and .txt, Copy Instructions, Submit.
6. Laptop: expand the row — the full blueprint is there. **Reveal leaderboard** → opens by itself on the phone; **Hide** closes it. Projector view shows the same.
7. Switch language on both (العربية / English); check RTL and that the studio is not cut off on the phone.
8. Refresh the phone mid-design → **Resume design** continues where it stopped (including the sentence you were typing).
9. Laptop: **Reset session** → new code. Phone offline for one step: retry message; download the blueprint and the backup.
10. Check Sound ON/OFF and the page with “reduce motion” enabled on the device.
