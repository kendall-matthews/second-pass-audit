---
name: second-pass-audit
description: Decide whether consequential AI-assisted work is ready to be accepted by comparing it directly against the decision-relevant source, requirements, evidence, and constraints before action.
---

# Second-Pass Audit

Use this method when the consequence of accepting a weak AI-assisted answer, recommendation, or artifact is meaningful.

## Required inputs

1. Current work or recommendation.
2. Decision-relevant source, evidence, requirements, or constraints.
3. Intended use or decision.

If a required source is missing, do not pretend the work can be checked against it. Return **HOLD** and identify the smallest missing evidence step.

## Method

### 1. Compare
Return to the decision-relevant source. Compare it directly with the current work rather than auditing from memory or rereading the output alone.

### 2. Identify
Check for:
- material omissions
- factual or interpretive errors
- unsupported conclusions
- weak interpretations
- underweighted details
- missed constraints or qualifiers
- changed emphasis
- downstream inconsistencies

### 3. Correct
Correct material issues when the source resolves them. Preserve content that is already supported. Do not rewrite merely for novelty.

### 4. Recheck
Recheck the areas affected by each material correction. A change can alter dependent claims, recommendations, calculations, links, metadata, or other elements.

### 5. Decide
Return one outcome:

**SHIP** — no unresolved material issue remains for the intended use.

**REVISE** — the direction remains usable but requires material correction before acceptance.

**HOLD** — the source is insufficient, a material issue remains unresolved, or additional qualified review is required.

### Optional visual explanation

After completing the source-grounded audit and rechecking affected work, determine whether a visual explanation would materially improve understanding of the findings, evidence gaps, dependencies, or decision consequences.

When useful and supported by the host, provide the simplest effective visual alongside the written audit.

Every visual finding must remain traceable to its source basis, issue type, and required action. Distinguish verified discrepancies from missing evidence, assumptions, and unresolved risks.

Show only source-supported dependencies. Distinguish prerequisites for release from corrections that can be specified immediately; do not imply an approval is required before identifying or correcting a known defect unless the source requires that order.

Use the same final findings and SHIP / REVISE / HOLD decision in both formats. Do not introduce unsupported relationships, invented scores, or additional conclusions through visualization.

If visualization adds no meaningful decision value or the host cannot support it, return the complete written audit without penalty.

Preserve the existing materiality criteria, boundaries, human accountability, and stop rule.

## Output

**Decision:** SHIP / REVISE / HOLD

**Short rationale**

**Material issues**
- discrepancy
- source basis
- required correction

**Affected downstream elements**

**Next action**

## Boundaries

**Matching the source does not prove the source is right.**

Do not claim this method proves correctness, guarantees safety, replaces professional judgment, or validates an unreliable source.

For medical, legal, financial, technical, compliance, security, or other high-stakes decisions, use HOLD when qualified review or additional evidence is still required.

The human or organization acting on the work owns the final decision.
