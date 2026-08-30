# THE DAILY WINNER — MAIN EDITION INSTRUCTION SHEET

**Status:** Permanent operating procedure  
**Rule:** READ THIS FILE FIRST before beginning every Main Edition.  
**Purpose:** Protect the established method from chat loss, forgotten rules, price contamination and retrospective tinkering.

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

## 10. PRICING — ODDsCHECKER URL METHOD

Only after the prediction freeze should current prices be introduced.

Use the **Oddschecker URL Method**:

- Construct/open the exact dated race URL: date + course + off-time + `/winner`.
- Read the actual bookmaker comparison grid.
- For the final Bet365 Selection Room, use the **Bet365 column**, not generic best-of-market prices.
- Check each-way terms and enhanced places.
- Do not rely on search snippets, cached prices or forecast prices.
- If flattened web extraction makes bookmaker columns ambiguous, use the visual grid/manual confirmation rather than guessing.

Never describe The Racing API's “best of X books” price as Bet365.

Record the price and EW terms beside every live Decision Room candidate.

---

## 11. SELECTION ROOM — TIPS VS VALUE

Now compare the frozen prediction with the available price.

### TOP 3 TIPS

These are the strongest underlying winning cases where the current Bet365 price remains acceptable.

### TOP 3 VALUE

These are horses already identified by the predictive process whose available Bet365 price appears materially bigger than the evidence warrants.

A huge price does not make a horse a stronger prediction. It may make the horse a better **value proposition**.

Each-way terms matter, especially where the place part is central to the value case.

**Maximum one headline bet per race.**

A horse may qualify conceptually for both Tip and Value; choose the category that best explains why we are betting it.

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

Keep the public explanation readable. The full technical reasoning belongs in the working state; the newspaper should communicate the decisive evidence rather than dump every calculation.

---

## 14. RESULTS / AUTOPSY

After racing, record results against the selections that were actually published/frozen.

Do not rewrite history.

Review:

- Winners.
- Top-3 strike rate.
- Tip/Value performance.
- UR1 challenge performance where tracked.
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
- [ ] EW terms checked.
- [ ] Deep dives completed where required.
- [ ] Top 3 Tips selected.
- [ ] Top 3 Value selected.
- [ ] Maximum one headline selection per race.
- [ ] Daily state file updated.
- [ ] No retrospective tinkering.

---

# DAILY OPENING INSTRUCTION

At the beginning of every Main Edition conversation:

> **Read `methodology/MAIN-EDITION-INSTRUCTIONS.md` first. Then read `state/CURRENT-WORKING-STATE.md` if it exists. Do not begin race analysis until both have been checked.**

This instruction overrides the temptation to reconstruct the method from conversational memory.
