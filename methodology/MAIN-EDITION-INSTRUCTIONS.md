# THE DAILY WINNER — MAIN EDITION INSTRUCTION SHEET

**Status:** Permanent operating procedure  
**Rule:** READ THIS FILE FIRST before beginning every Main Edition.  
**Purpose:** Protect the established method from chat loss, forgotten rules, price contamination, retrospective tinkering, and accidental publication of internal working machinery.

---

## 1. THE GOLDEN RULE

The job is to find the most likely winners using the supplied speed-figure evidence, then decide whether the available price represents value.

**Prediction first. Price second.**

Never change the underlying ranking because a horse is shorter or bigger than expected in the betting.

Never retrospectively alter the method because yesterday's winner came from outside our selections.

---

## 2. DAILY START — SOURCE CHECK

Before analysing races, establish today's evidence and conditions.

Required inputs where available:

- User-supplied / Andy H speed-figure data.
- Proform data, including **UR1**.
- Racing Post Edge / Signposts intelligence.
- Official going and non-runners.
- Weather/conditions where materially relevant.

Official-source hierarchy:

- **Britain:** BHA for going, non-runners and raceday information.
- **Ireland:** IHRB for going/raceday regulatory information; HRI is useful for programme/entries.
- The Racing API may be used as a cross-check, but must not silently replace official information or the user's supplied figures.

If an important daily source file is missing, STOP and identify the missing source before pretending the audit is complete.

---

## 3. CONDITIONS AUDIT

Decide whether today's conditions require any adjustment to the normal figure methodology **before ranking horses**.

Normal rule:

> Give greatest kudos to strong speed figures achieved on the **same surface within 50 days**.

This is a weighting, not an automatic exclusion rule.

If conditions have changed radically — especially unusually soft/heavy ground — older evidence on strongly comparable conditions may become more informative than a more recent figure achieved under irrelevant conditions.

Any such adjustment must be declared at the beginning of the day's analysis and then applied consistently across the card.

---

## 4. STAGE ONE — TOP 3 EVERY RACE

Build the predictive Top 3 for every relevant race **without looking at current prices**.

Primary evidence:

1. Supplied speed figures.
2. Same-surface relevance.
3. Normally ≤50-day recency.
4. Today's going/conditions.
5. Distance/course suitability where meaningful.
6. Broader evidence to separate close calls: OR/handicap mark, recent form, pace/draw, C&D evidence, weight changes and other material factors.

A horse being materially well-in — e.g. around **6 lb well in** — is significant and should be explicitly noted.

Do not use The Racing API's performance/speed ratings as substitutes for the supplied figures. If API ratings are quoted, label them clearly as an **independent cross-check**.

---

## 5. UR1 — INDEPENDENT CHALLENGE

**UR1 must appear every day. Do not forget this stage.**

UR1 is an independent Proform model/check. It is **not** part of the original Andy H/speed-figure ranking and must not be blended into the prediction engine invisibly.

After our Top 3 has been produced, compare it with UR1.

Classify the evidence:

- **Strong convergence:** our #1 is also UR1 #1 or highly ranked.
- **Useful agreement:** our selection is comfortably prominent in UR1.
- **Mild disagreement:** worth investigating, but not automatically negative.
- **Major disagreement:** our selection is poorly ranked by UR1; this requires an explicit challenge before it can become a headline bet.

Also identify **UR1 #1/#2 horses that are absent from our Top 3/Decision Room**. The point of an independent model is not merely to congratulate us when it agrees; it must be allowed to show us something we may have missed.

UR1 disagreement does **not** automatically eliminate a horse. A compelling speed/conditions/value case can override it, but the reason must be recorded.

---

## 6. RACING POST EDGE / INTELLIGENCE CHALLENGE

Use Edge/Signposts and other relevant intelligence as a challenge layer, not as a replacement prediction engine.

Ask:

- Does it reveal a conditions angle we missed?
- Is there a handicap/weight angle?
- Is there significant trainer/jockey/course information?
- Does it materially strengthen or weaken one of our close calls?

Do not force newspaper angles into selections simply because they are interesting.

---

## 7. DECISION ROOM

Create the **Decision Room shopping list** from the completed predictive work.

This is the shortlist of horses worthy of consideration for the newspaper's headline bets.

For each candidate record at minimum:

- Race / horse.
- Our predictive rank/reason.
- Key supplied speed-figure evidence.
- Conditions relevance.
- UR1 rank/challenge.
- Important positives.
- Important risks.

At this point **prices are still unknown/ignored**.

---

## 8. MORNING OFFICIAL AUDIT

Before freezing predictions, check official:

- Going.
- Non-runners.
- Material raceday changes.

Only reopen races where something material has changed.

A non-runner in a Decision Room race can improve or damage the case, but **do not automatically replace a withdrawn Decision Room horse with another selection**.

If a favourite/major rival is withdrawn, explicitly assess the effect on the remaining candidate.

---

## 9. PREDICTION FREEZE

Once the morning audit is complete, formally declare:

> **PREDICTION BOARD FROZEN.**

From this point:

- No changing rankings because of prices.
- No rediscovering convenient figures after seeing 20/1, 50/1, etc.
- No promoting a horse simply because the market likes it.
- No dropping a horse simply because the market dislikes it.

New factual information (e.g. late NR/going change) can trigger a clearly recorded re-examination. Price cannot.

---

## 10. PRICING — ODDSCHECKER URL METHOD

Only after the prediction freeze should current prices be introduced.

Use the **Oddschecker URL Method**:

- Construct/open the exact dated race URL: date + course + off-time + `/winner`.
- Read the actual bookmaker comparison grid.
- For the final Bet365 Selection Room, use the **Bet365 column**, not generic best-of-market prices.
- **All prices printed beside the final Top 3 Tips and Top 3 Value in the Main Edition must be confirmed Bet365 prices unless the newspaper explicitly labels a different bookmaker.**
- Check each-way terms and enhanced places.
- Do not rely on search snippets, cached prices or forecast prices.
- If flattened web extraction makes bookmaker columns ambiguous, use the visual grid/manual confirmation rather than guessing.

Never describe The Racing API's “best of X books” price as Bet365.

Record the price and EW terms beside every live Decision Room candidate.

For the permanent detailed EW/concessions policy, also read `methodology/EACH-WAY-CONCESSIONS-RULE.md`. Core rule: **bookmaker concessions can influence HOW we bet a selection, never WHICH horse we select.** Around 6/1+ triggers an EW review, not an automatic EW bet; extra-place concessions must be actively checked and the advised WIN/EW terms recorded before publication.

---

## 11. SELECTION ROOM — TIPS VS VALUE

Now compare the frozen prediction with the available price.

### TOP 3 TIPS — WINNER PREDICTIONS, NOT VALUE PICKS

The Top 3 Tips answer one question only:

> **Which three horses do we think are the strongest winning prospects today?**

**Every Top 3 Tip MUST be the published/frozen #1-ranked horse in its own race. A #2 or #3 is ineligible for the Top 3 Tips.**

This is an absolute eligibility rule. A secondary model preferring our #2, strong UR1 support for the #2, or a more attractive price on the #2 does **not** permit that horse to replace our #1 in the Top 3 Tips.

Secondary evidence may:

- strengthen or weaken confidence in our #1;
- cause us to leave that race out of the Top 3 Tips entirely; or
- if genuinely new racing evidence emerges before the prediction freeze, trigger a transparent re-examination of the underlying race ranking.

But once the final race ranking is frozen, a #2 cannot become a Top 3 Tip merely because the secondary evidence or market makes it more appealing.

**Price is not the purpose of the Top 3 Tips.** A short-priced #1 can still be a Top Tip if it is one of our three strongest winning predictions. Price can help decide whether we want to bet a #1 at all, but it cannot promote a lower-ranked horse into this section.

### TOP 3 VALUE — PRICE VERSUS PROBABILITY

The Value Desk answers a different question:

> **Which horses are priced materially bigger than the chance our evidence gives them?**

Value selections must already have been identified by the predictive process, but they may be our #1, #2 or #3 in the race when the available price compensates for the lower predictive rank.

A huge price does not make a horse a stronger prediction. It may make the horse a better **value proposition**.

Each-way terms matter, especially where the place part is central to the value case.

**Maximum one headline bet per race.**

A #1 may qualify conceptually for both Tip and Value; choose the category that best explains why we are betting it. A #2/#3 can only appear on the Value Desk, never in Top 3 Tips.

**Simple newspaper distinction: TOP 3 TIPS = WINNERS. VALUE DESK = PRICES.**

---

## 12. DEEP-DIVE / STRESS TEST

Before finalising a contentious headline selection, especially a large-priced Value horse, ask:

- Why is the market this price?
- Is there a class/OR gap we have underweighted?
- Does today's going genuinely suit?
- Is the key figure repeatable or an outlier?
- What do the strongest rivals bring?
- Does UR1 agree or strongly disagree?
- Has a NR materially altered the race?
- Are headgear, draw, weight or stable/jockey factors relevant?

The purpose is to **try to disprove our selection**, not find extra reasons to justify it.

If it survives, keep it. If new factual evidence exposes a genuine flaw, record it openly.

---

## 13. FINAL MAIN EDITION OUTPUT

The Main Edition should normally contain:

- **Top 3 Tips**.
- **Top 3 Value**.
- **Top 3 Every Race**.
- Relevant course/conditions watch and editorial intelligence.
- **Cheerful Autopsy** of the previous edition where selections existed.

Do not write an autopsy where there were no selections to assess.

### PUBLIC-FACING EDITORIAL RULE — KEEP THE MACHINERY BACKSTAGE

**The Main Edition is a newspaper, not the working notebook.**

The internal process is for us. The reader should see the conclusion, the strongest racing evidence and a clean editorial explanation — **not the architecture of the model**.

Do **not** expose internal process language in public copy, including:

- UR1 or UR1 rank numbers.
- “Stage 1 / Stage 2 / Stage 3”.
- “Decision Room” or “Selection Room”.
- “price-blind”, “prediction freeze”, “frozen board”.
- “model convergence”, “independent model agreement”, “conditions #1”, “UR1 #1”, or similar shorthand.
- Internal grades such as A+, A-, B+ unless deliberately converted into a reader-friendly confidence presentation.
- References to our internal files, methodology sheets, state files, APIs, spreadsheets or technical workflow.
- **Raw supplied speed-figure numbers (for example, “a 77 figure”) in ordinary public selection copy. The figures drive the analysis backstage; translate them into natural phrases such as “strong recent form on soft ground”, “a leading recent performance” or “proven under these conditions”. Only print raw speed-figure numbers when we deliberately choose to run a reader-facing feature explaining the figures themselves.**

Instead, translate the evidence into natural racing language.

Examples:

- Internal: **“Conditions #1 + UR1 #1.”**  
  Public: **“Everything we looked at points the same way, and today's conditions look firmly in his favour.”**

- Internal: **“UR1 #13 major disagreement.”**  
  Public: **“There are enough questions elsewhere in the evidence to keep this as a speculative value play rather than a confident win selection.”**

- Internal: **“Rebuilt because of Heavy ground.”**  
  Public: **“The overnight rain changed the complexion of the card, so horses with proven form in testing conditions move sharply up the pecking order.”**

- Internal: **“Price-blind selection.”**  
  Public: **“We liked the horse before the market entered the conversation; the available price simply makes the case more appealing.”**

The public explanation should focus on the decisive racing reasons: recent speed, proven going, course/distance suitability, handicap position, current form, race shape and price/value where appropriate.

**Never publish the machinery simply because it exists in the working state.**

### DRAFT-BEFORE-PUBLISH RULE

Unless the user explicitly asks to publish immediately, **build or update a draft first and let the user inspect it before replacing the live `index.html`.**

Publishing to the live homepage is a separate step from building the Main Edition.

### PERMANENT EDITION ARCHIVE

GitHub is also the permanent historical archive of what readers actually saw.

Use:

- `archive/main/YYYY/MM/YYYY-MM-DD.html` for Main Editions.
- `archive/evening/YYYY/MM/YYYY-MM-DD.html` for Evening Editions.
- `archive/tipster-tracker/YYYY/MM/YYYY-MM-DD.html` for Tipster Tracker editions.

**Before replacing a live edition, preserve the edition being replaced under its dated archive path.** Once a published edition is archived, treat it as immutable historical evidence: do not silently rewrite selections, prices, EW terms, rankings, editorial or results because later information or methodology changes make the old edition look untidy.

Where the exact published HTML already exists immutably in Git history, an archive record may point to the exact publication commit/blob rather than reconstructing the edition. Historical searchability and verifiability are the priorities.

If a genuine correction is required, preserve the original and document the correction rather than rewriting history.

Keep the public explanation readable. The full technical reasoning belongs in the working state; the newspaper should communicate the decisive evidence rather than dump every calculation.

---

## 14. RESULTS / AUTOPSY

After racing, record results against the selections that were actually published/frozen.

Do not rewrite history.

**The Cheerful Autopsy has two required scoreboards whenever the previous edition contained both headline bets and Top 3 Every Race predictions:**

1. **Headline selections:** review the published Top 3 Tips and Top 3 Value — winners, places, non-runners and notable price/value results.
2. **Prediction performance:** audit every completed race from the previous edition's published Top 3 Every Race and report:
   - **NO. 1 WINNERS — X/Y**: races won by our published first choice.
   - **WINNER IN TOP 3 — X/Y**: races where the actual winner appeared anywhere in our published three.
   - Exclude abandoned/uncompleted races from Y and explain any material exclusions.

The public Autopsy should normally show these prediction statistics clearly in the scoreboard, not leave them buried in internal notes. The purpose is to keep an honest running measure of the core prediction method as well as the headline betting selections.

Also review where useful:

- Tip/Value performance.
- Significant value capture versus SP.
- UR1 challenge performance internally where tracked — **do not expose UR1 in public copy**.
- Whether losses reveal a repeatable methodological issue or ordinary racing variance.

One result is not sufficient evidence to change the model.

---

## 15. DAILY STATE / CHAT CONTINUITY

GitHub is the permanent filing cabinet. Chat is the working room.

Maintain a daily state file such as:

`state/CURRENT-WORKING-STATE.md`

It should contain:

- Date.
- Current stage.
- Today's methodology/conditions adjustment.
- Completed work.
- Frozen Top 3 / Decision Room candidates.
- UR1 findings.
- Official going/NR audit.
- Confirmed Bet365 prices/EW terms.
- Final selections when reached.
- Exact next action.
- **DO NOT REDO** section.

Store/refer to daily source data under a dated structure where practical, e.g.:

`data/YYYY-MM-DD/`

At major milestones — Top 3 complete, Decision Room complete, prediction freeze, prices complete, final selections — update the state file.

If a chat becomes long, **update the state file before moving to a new conversation**.

---

## 16. DAILY PRE-FLIGHT CHECKLIST

Before publishing, confirm every box:

- [ ] Main Edition instruction sheet read first.
- [ ] Required source files present.
- [ ] Official going checked.
- [ ] Conditions/recency policy declared.
- [ ] Top 3 every race built without current prices.
- [ ] **UR1 challenge completed.**
- [ ] Edge/intelligence challenge completed.
- [ ] Decision Room completed.
- [ ] Official NR/going recheck completed.
- [ ] Prediction board frozen.
- [ ] Bet365 prices obtained only after freeze.
- [ ] **Every public headline price checked as Bet365 unless explicitly labelled otherwise.**
- [ ] EW terms and extra-place concessions checked; advised WIN/EW terms recorded before publication.
- [ ] Deep dives completed where required.
- [ ] **Every Top 3 Tip is the frozen #1-ranked horse in its race — no #2/#3 Tip is permitted.**
- [ ] Top 3 Tips selected from the strongest eligible #1s.
- [ ] Top 3 Value selected.
- [ ] Maximum one headline selection per race.
- [ ] Daily state file updated.
- [ ] If there was a previous edition, Cheerful Autopsy includes headline selections **and the Top 3 Every Race prediction scoreboard (No. 1 winners + winner in Top 3)**.
- [ ] Public copy contains **no exposed internal machinery or raw speed-figure numbers**.
- [ ] Public reasons are written in natural racing/editorial language.
- [ ] Draft inspected before replacing live edition unless explicit immediate publication was requested.
- [ ] **Edition being replaced has been preserved in the permanent archive / exact immutable Git publication record exists.**
