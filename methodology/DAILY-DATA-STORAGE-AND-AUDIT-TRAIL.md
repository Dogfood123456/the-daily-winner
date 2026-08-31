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

Where practical also preserve race type, field size and other pre-race descriptors useful for later analysis.

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

## 8. RESULTS ARCHIVE

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
```

Non-runners must be explicitly identified so denominators can be calculated correctly.

Do not count a withdrawn #1 as a losing selection when calculating strike rates. Preserve the race separately where needed for Top-3 coverage statistics.

---

## 9. AUDIT BEFORE COMPARISON

Before publishing or relying on a comparison such as TDW vs RPR vs UR1:

1. Confirm the exact races included.
2. Confirm non-runners and the correct denominator for each method.
3. Confirm the external model's actual ranking/selection field from its header.
4. Score the actual winner against the preserved pre-race selection/ranking.
5. Use official SP/result data where available.
6. Reconcile totals against the race-by-race ledger before announcing the headline number.

If an earlier comparison is later discovered to have used a misidentified field, withdraw that statistic and re-audit it from the preserved source rather than trying to repair it from memory.

---

## 10. DAILY AUDIT PRINCIPLE

> **Archive first. Analyse second. Never reconstruct when the original evidence can be preserved.**

The archive should make it possible to answer a question such as:

> **“How did UR1 perform on 31 August?”**

months later directly from the preserved machine-readable data, without requiring the user to locate or re-upload the original workbook.

The goal is a reproducible historical dataset: original evidence, frozen TDW opinion, independent challengers and final results all preserved separately.

---

## 11. FAILURE-SAFE RULE

If the original XLSX exists in GitHub but cannot be reliably parsed in the current environment:

- do **not** infer spreadsheet fields from extracted row positions;
- do **not** ask the user to repeatedly upload the same file if a machine-readable archive should already exist;
- use the archived CSV companion where available;
- if no CSV companion exists, mark the requested statistic as pending verification and create the missing machine-readable archive when the workbook is next available in a parseable environment.

Accuracy takes priority over producing a number immediately.
