# THE DAILY WINNER — DAILY DATA STORAGE & AUDIT TRAIL

**Status:** Permanent operating procedure  
**Applies to:** Main Edition and any Daily Winner analysis using Andy H / supplied speed figures, Proform, RPR or other independent challenge data.  
**Purpose:** Preserve the original daily evidence in a form that can be reliably reopened, checked and scored later without requiring the user to repeatedly re-upload source files.

---

## 1. WORKING FILES

At the start of each day's analysis, the current:

- **Andy H / supplied speed-figure workbook**; and
- **Proform workbook**

should be uploaded directly to the active Winners conversation/project where possible.

These directly uploaded spreadsheets are the **working copies** used for that day's analysis.

Do not rely on a GitHub-hosted XLSX as the primary working copy when the same workbook is available directly. GitHub is the permanent archive; the directly uploaded workbook is the preferred analysis copy.

However, if a directly uploaded workbook is announced as available but cannot actually be opened by the analysis environment, do not get trapped in repeated re-uploads of the same data. Move immediately to the preserved machine-readable GitHub companion where available.

A source-access failure is an infrastructure problem, not permission to infer missing fields or reconstruct the racecard from memory.

---

## 2. GITHUB PERMANENT DATA ARCHIVE

Once received, preserve the original daily source files in the Daily Winner GitHub repository.

Use the recommended structure:

```text
data/
  YYYY-MM-DD/
    andy-h-original.xlsx
    proform-original.xlsx
    andy-h.csv
    proform.csv
    tdw-frozen-board.csv
    rp-selection-box.csv
    results.csv
```

The XLSX files are the **unaltered originals** and must not be overwritten with processed or reconstructed data.

If source filenames need to be retained for provenance, record the original filename in the daily working state or archive metadata.

---

## 3. MACHINE-READABLE COPIES ARE MANDATORY

For every archived XLSX workbook, also create a **CSV version containing the data required for future analysis and audit**.

This is essential because GitHub can preserve XLSX files reliably while later access to their internal spreadsheet structure may not always be available. CSV is plain text and therefore provides a dependable long-term audit source.

Column names from the original source must be preserved wherever possible.

In particular, Proform fields such as **UR1 / Power Rating rankings must be identified from the actual column heading**, never inferred from column position, neighbouring fields or apparently plausible values.

For Proform Top-3 extraction, positively identify the actual header **`UR1_Rank`** and use:

- `UR1_Rank = 1` → Proform #1
- `UR1_Rank = 2` → Proform #2
- `UR1_Rank = 3` → Proform #3

Never reconstruct a Proform Top 3 from another nearby rating field because the values happen to look plausible.

The CSV copy is an audit companion to the original XLSX, not a replacement for it.

---

## 4. SPREADSHEET FIELD VERIFICATION RULE

**Never infer the meaning of an unidentified spreadsheet column.**

Before using a spreadsheet field in analysis, positively identify it from its header or other unambiguous source metadata.

A value that merely appears plausible is not sufficient evidence of what a column represents.

This applies especially to:

- UR1 / Power Ratings;
- draw;
- official ratings;
- prices;
- finishing positions;
- speed/rating fields; and
- any ranking field used in comparative analysis.

If a field cannot be positively identified, STOP and verify it before using it.

If verification is impossible, report the statistic as **unverified** rather than estimate, infer or manufacture it.

---

## 5. FROZEN TDW BOARD

Immediately after the price-blind Daily Winner rankings are finalised and the declaration:

> **PREDICTION BOARD FROZEN.**

save a machine-readable copy of the frozen board.

It should contain at minimum:

```text
Date
Course
Race Time
Horse #1
Horse #2
Horse #3
Confidence Stars
Headline Candidate
Final Headline Status
```

Where practical also preserve race type, field size, surface and other pre-race descriptors useful for later analysis.

Later information must never silently rewrite the original frozen rankings.

Any legitimate post-freeze change caused by new factual racing information must be separately recorded with the reason and time of change.

---

## 6. INDEPENDENT CHALLENGERS

RPR, Proform/UR1 and any future external ratings remain **independent challengers**.

They must not be consulted in a way that contaminates the initial TDW speed-figure ranking.

The order is:

> **TDW analysis → Top 3 → prediction freeze → independent comparison.**

After the TDW board is frozen, independent selections/rankings can be attached to the race record for subsequent comparison.

This allows genuine prospective tests including:

- TDW #1 strike rate;
- TDW Top-3 hit rate;
- RPR selection strike rate;
- UR1 #1 strike rate;
- UR1 Top-3 hit rate;
- TDW #1 + RPR agreement;
- TDW #1 + UR1 agreement;
- RPR + UR1 agreement;
- TDW + RPR + UR1 three-way agreement;
- strike rate by confidence-star level;
- strike rate by race type;
- average winning SP; and
- level-stakes profitability.

Do not retrospectively change a TDW ranking to create agreement with an external model.

---

## 7. RPR AGREEMENT — PROSPECTIVE BOX-CANDIDATE EXPERIMENT

For now, **TDW #1 = RPR selection** should be recorded as a **potential headline / box-candidate flag**, not an automatic selection rule.

RPR must never create or alter the TDW #1.

The sequence is:

> **TDW analysis → Top 3 → freeze → RPR comparison → agreement flag → headline suitability assessment.**

Agreement is additional independent evidence only.

A horse does not automatically enter a headline box because RPR agrees. Existing headline-race suitability checks still apply, including evidence depth, race type, field size, tactical uncertainty and other material risks.

A compelling TDW #1 may still become a headline selection without RPR agreement.

The experiment must be tracked prospectively over a meaningful sample before being promoted to a formal selection rule.

RPR agreement is an internal challenge/validation tool and should not normally be exposed as the public reason for a Daily Winner selection.

---

## 8. RACING POST SELECTION-BOX FREEZE

Where Racing Post selection-box data is available, preserve it **before racing** rather than trying to reconstruct it after the results are known.

The standard archive columns are:

```text
Meeting
Time
Spotlight
RP Ratings
Topspeed
Postdata
```

Operational sequence:

> **Night before: freeze RP selection-box data → Morning: freeze TDW and Proform/UR1 data → After racing: score all preserved methods against the official result.**

If a selection cannot be read confidently from the source, mark it for verification. Do not guess a difficult name simply to complete the table.

This archive exists to make later press-league comparisons reproducible and prospective.

---

## 9. RESERVES AND NON-RUNNERS

Ordinary non-runners and Irish reserves must not be treated as the same thing for performance scoring.

### Ordinary non-runner

If a frozen TDW #1 is withdrawn in the normal way, preserve that original #1 and exclude it from the #1 strike-rate denominator where appropriate. Do **not** silently promote #2 and pretend it was always the selection.

### Irish reserve that never makes the field

Where the source racecard includes reserves, identify them before the freeze where possible and rank the intended main field separately, with reserves held underneath.

If a reserve was included in the frozen ranking but **never obtains a place in the actual field**, preserve the original ranking for audit but treat the highest-ranked actual runner as the **effective/live #1** for performance scoring.

The race record must make this distinction explicit so the original opinion and the live-field statistic can both be reconstructed later.

A failed-to-get-in reserve must never be scored as though it were an ordinary runner that was subsequently withdrawn.

---

## 10. RESULTS ARCHIVE

After racing, append the official result to the archived race record without altering the frozen predictions.

Record at minimum:

```text
Date
Course
Race Time
Winner
SP
TDW winner position (1 / 2 / 3 / outside)
RPR selection/result where available
UR1 #1/result where available
UR1 Top-3 hit/miss where available
Headline bet/result where applicable
Reserve / NR status where relevant
Surface
Country / jurisdiction
```

Non-runners must be explicitly identified so denominators can be calculated correctly.

Do not count a withdrawn #1 as a losing selection when calculating strike rates. Preserve the race separately where needed for Top-3 coverage statistics.

---

## 11. PERFORMANCE REPORTING — KEEP THE SPLITS

From now on, performance should be retained at minimum as:

- **Great Britain**
- **Ireland**
- **Overall**

Do not allow a combined headline number to hide a materially different record between Britain and Ireland.

Also retain surface/environment splits where the data supports them, particularly:

- **Turf**
- **All-Weather**

Course, race type, field size and confidence-star splits may also be studied over larger samples.

This is measurement, not permission to rewrite the prediction methodology after a handful of races. The purpose is to discover where the supplied speed figures are genuinely most effective over a meaningful sample.

Headline-box performance must also be kept separately from the full prediction engine. A bad day in the boxes does not erase a good Top-3 engine, and a good box day does not prove every underlying ranking decision was correct.

---

## 12. VALUE SIGNALS WITHOUT MASSAGING THE SCORE

Useful price information may appear even when a selection does not win — for example a large-priced #2 or #3 finishing second or placing prominently.

These **market-underestimated placers** may be logged as a separate research signal, including price and finishing position where useful.

They must never be counted as winners, used to inflate the #1 strike rate, or substituted for the official Top-3 hit statistic.

Keep the concepts separate:

> **Prediction accuracy tells us how often we found the winner. Value evidence tells us whether the rankings may contain useful information that the market underestimated.**

Both matter, but they are not the same statistic.

---

## 13. AUDIT BEFORE COMPARISON

Before publishing or relying on a comparison such as TDW vs RPR vs UR1:

1. Confirm the exact races included.
2. Confirm non-runners, reserves and the correct denominator for each method.
3. Confirm the external model's actual ranking/selection field from its header or preserved source.
4. Score the actual winner against the preserved pre-race selection/ranking.
5. Use official SP/result data where available.
6. Reconcile totals against the race-by-race ledger before announcing the headline number.
7. State whether the figure is GB, Ireland or Overall, and use the same basis when comparing methods.

If an earlier comparison is later discovered to have used a misidentified field, withdraw that statistic and re-audit it from the preserved source rather than trying to repair it from memory.

---

## 14. DAILY AUDIT PRINCIPLE

> **Archive first. Analyse second. Never reconstruct when the original evidence can be preserved.**

The archive should make it possible to answer a question such as:

> **“How did UR1 perform on 31 August?”**

months later directly from the preserved machine-readable data, without requiring the user to locate or re-upload the original workbook.

The goal is a reproducible historical dataset: original evidence, frozen TDW opinion, independent challengers and final results all preserved separately.

---

## 15. FAILURE-SAFE RULE

If the original XLSX or CSV exists but cannot be reliably parsed in the current environment:

- do **not** infer spreadsheet fields from extracted row positions;
- do **not** ask the user to repeatedly upload the same file if a machine-readable archive should already exist;
- use the archived CSV companion where available;
- where the direct attachment bridge fails, use the GitHub-hosted **small machine-readable CSV** as the first fallback rather than repeatedly changing filenames or formats;
- if a full Proform export is too large for reliable text retrieval, maintain a reduced racecard/audit CSV containing only the fields actually required for ranking and comparison, while preserving the untouched original separately;
- if no usable machine-readable companion exists, mark the requested statistic as pending verification and create the missing companion when the workbook is next available in a parseable environment.

Do not assume a source is corrupt merely because an attachment path was announced but is not actually accessible to the analysis runtime.

Accuracy takes priority over producing a number immediately.