# Source Verification Reference — ThinkThanks

---

## Source Identity Verification Checklist

For each material source, check and record:

```
□ Title          — Does the title match what is being cited?
□ Author(s)      — Real, identifiable, with verifiable affiliation?
□ Publisher      — Real organization? Known publication?
□ Date           — Publication date and last update date confirmed?
□ URL/Location   — Stable URL, DOI, or physical location recorded?
□ Identifier     — DOI, ISBN, accession number, or equivalent?
□ Version        — Is this the current version? Any superseded?
□ Methodology    — Research method described and assessable?
□ References     — Reference list exists and appears legitimate?
□ Corrections    — Any correction, retraction, or editorial note?
□ Relationships  — Is this derivative of another source already cited?
□ Access         — Was full text accessed or only abstract/summary?
```

**Verification Status Labels:**
- `✓ VERIFIED` — All applicable checks passed
- `~ PARTIAL` — Some checks passed; limitations noted
- `✗ UNVERIFIED` — Could not confirm; do not rely on without disclosure
- `⚠ FLAGGED` — Verified but bias risk or methodological concern identified
- `🚫 RETRACTED` — Formally retracted; do not use as evidence

---

## 8-Point Citation Verification Protocol

Before attributing ANY claim to a source:

```
Check 1  EXISTENCE        Does this source actually exist?
         → Cannot verify? Mark UNVERIFIED. Do not fabricate metadata.

Check 2  ACCESS           Has the source been accessed, or only its metadata verified?
         → If only abstract: state "based on abstract review only"
         → If full text inaccessible: state the limitation

Check 3  TOPICALITY       Does this source address the topic being claimed?
         → A source on a related topic ≠ a source on this topic

Check 4  CLAIM SUPPORT    Does the specific cited section support the specific claim?
         → Read the actual passage; do not assume the abstract = the paper's finding

Check 5  QUOTATION        If quoting directly: is the quotation word-for-word accurate?
         → Paraphrasing ≠ quoting; label correctly

Check 6  CONTEXT          Has important qualifying context been preserved?
         → Authors often limit their own conclusions; honor those limits

Check 7  CURRENCY         Has this source been corrected, retracted, or superseded?
         → Check PubMed, Retraction Watch, publisher errata pages

Check 8  SCOPE            Does the author's stated conclusion match how you are using it?
         → Authors frequently overstate or understate; use the actual data, not just the abstract
```

**If any check fails:** Either remove the citation from the report, note the failure explicitly, or downgrade the claim to [INFERENCE] or [UNVERIFIED].

---

## Citation Integrity Taxonomy

Label every claim-source relationship with its actual type. This prevents misrepresentation.

| Label | Definition | Example |
|-------|-----------|---------|
| `[QUOTE]` | Direct, word-for-word quotation in quotation marks | "The effect size was 0.42 (95% CI: 0.31–0.53)" |
| `[PARAPHRASE]` | Rewording of source's meaning; closely follows source | The authors found a moderate positive effect... |
| `[SUMMARY]` | Condensed version of the source's broader argument | The study concludes that X has benefits for Y under conditions Z... |
| `[INTERPRETATION]` | Your reading of what the source implies, beyond what it states | This suggests that [implied conclusion not stated by authors] |
| `[INFERENCE]` | Conclusion derived by combining multiple sources | Taken together, sources A, B, and C suggest... |
| `[HYPOTHESIS]` | Proposed explanation not yet supported by cited evidence | One possible explanation is... |
| `[UNVERIFIED]` | Source could not be confirmed to exist or access specific claim | [claim] — source not accessible for verification |

**Placement rule:** Citations must be placed at the claim level, not only at the paragraph end. A paragraph containing 5 claims with one citation at the end implies all 5 claims are from that source; this is incorrect unless true.

---

## Bias and Manipulation Indicators

### 20 Red Flags — Escalation Framework

| # | Red Flag | Escalation Level |
|---|----------|-----------------|
| 1 | Extraordinary claims with no primary data | 🔴 Needs Verification |
| 2 | Statistics cited without defining the metric | 🔴 Needs Verification |
| 3 | Sample described as representative without evidence | 🟡 Methodological Concern |
| 4 | Correlation used to assert causation | 🟡 Methodological Concern |
| 5 | Unequal comparisons presented as equivalent | 🟡 Methodological Concern |
| 6 | Selectively reported subset of available data | 🟠 High Concern |
| 7 | Undisclosed conflict of interest (funder, author) | 🟠 High Concern |
| 8 | Appeal to authority without relevant expertise | 🔴 Needs Verification |
| 9 | Quotation stripped of qualifying context | 🟠 High Concern |
| 10 | Article repeats claims from single undisclosed source | 🟡 Methodological Concern |
| 11 | Results not replicated despite high-profile claim | 🟡 Methodological Concern |
| 12 | Dataset provenance not disclosed | 🟡 Methodological Concern |
| 13 | Misleading chart scale or truncated y-axis | 🟡 Methodological Concern |
| 14 | Technical terminology applied incorrectly | 🔴 Needs Verification |
| 15 | Emotional or inflammatory framing in research context | 🔴 Needs Verification |
| 16 | Fabricated or unresolvable DOI | 🔴 Confirmed Issue |
| 17 | Peer review not conducted or misrepresented | 🟠 High Concern |
| 18 | Author's stated conclusion contradicts their own data | 🔴 Confirmed Issue |
| 19 | Source has been formally retracted | 🔴 Confirmed Issue |
| 20 | Dataset with unexplained perfect values or round numbers | 🟡 Methodological Concern |

### Escalation Levels

```
🔴 NEEDS VERIFICATION    — Flag raised; verify before relying on this source
🟡 METHODOLOGICAL CONCERN — Method has identifiable weakness; lower confidence; note limitation
🟠 HIGH CONCERN          — Significant bias risk; require independent confirmation
🔴 CONFIRMED ISSUE       — Verified problem; do not use as evidence; document the finding
⬛ UNCONFIRMED SUSPICION  — Concern exists but cannot be established from available information
```

**Rule:** A single red flag ≠ confirmed manipulation. Document the indicator, escalate appropriately, and seek independent verification. Reserve confirmed findings for what has been established.

---

## Independence-Aware Triangulation Checklist

Before claiming that multiple sources confirm a finding:

```
□ Do these sources use different underlying datasets?
□ Are these from different research groups?
□ Were these studies designed independently (not replications of each other)?
□ Do they cite the same original primary source as their foundation?
□ Are they reporting results from different geographic/demographic contexts?
□ Were they conducted in different time periods?
□ Are they reporting on the same press release or institutional announcement?
□ Were they funded by different, independent sources?
```

**Rule:** If 3 articles all cite the same single study and add no independent data, they represent ONE data point — not three. Independence must be genuine, not apparent.

**Dependency notation:**
```
Source A: Independent ✓
Source B: Shares dataset with Source A — dependent
Source C: Independent ✓
→ Effective independent confirmations: 2 (not 3)
```

---

## Contradiction Mapping Table

Use when sources disagree on a material point:

```
CONTRADICTION ANALYSIS
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
Claim in dispute  : [Specific point of disagreement]
Source A position : [Finding and citation]
Source B position : [Finding and citation]

Dimension         | Source A          | Source B
──────────────────┼───────────────────┼──────────────────
Data used         | [dataset/source]  | [dataset/source]
Method            | [design type]     | [design type]
Population        | [who/what]        | [who/what]
Time period       | [when]            | [when]
Key definitions   | [definition]      | [definition]
Conflict of int.  | [disclosure]      | [disclosure]
Bias risk         | [assessment]      | [assessment]
Quality           | [evaluation]      | [evaluation]

Resolution options:
  □ Source A better supported for this context because: [reason]
  □ Both findings valid in different conditions: [specify conditions]
  □ Disagreement cannot currently be resolved
  □ Insufficient evidence — neither position adequately supported

Final position    : [Chosen resolution]
Confidence impact : [How does this contradiction affect overall confidence?]
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
```

---

## Source Diversity Rules

### What diversity means
- Different methodologies (experimental, observational, qualitative)
- Different research groups and institutions
- Different time periods where temporal pattern matters
- Different geographic and demographic contexts where applicable
- Different funding sources and institutional affiliations

### What diversity does NOT mean
- Simply having many sources (10 articles from same group = 1 perspective)
- Collecting sources across media types if all repeat the same claim
- Balancing viewpoints artificially where the evidence is not actually balanced

### Minimum diversity for High Confidence claims
- At least 2 genuinely independent studies
- At least one study with pre-registration or publicly available data
- Active search for contradictory evidence completed and documented

### When diversity is impossible
- State why: single event, proprietary data, limited research domain
- Downgrade confidence accordingly
- Do not inflate confidence to compensate for unavoidable limitation
