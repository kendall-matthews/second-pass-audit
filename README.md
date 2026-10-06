# Second-Pass Audit

Use this before you trust important AI-assisted work.

AI can produce work that looks finished before it has earned acceptance.

Second-Pass Audit creates a deliberate checkpoint between generation and action:

**COMPARE → IDENTIFY → CORRECT → RECHECK → DECIDE**

Every audit ends with:

**SHIP / REVISE / HOLD**

## Start here

**You do not need to know GitHub or how to code. You do not need to install anything to try the method.**

The fastest way to use Second-Pass Audit is:

1. Open the [Quick-use Prompt](PROMPT.md).
2. Copy it into the AI tool you already use.
3. Add the work you want to check.
4. Add the source, evidence, requirements, records, or other material the work should follow.
5. State what you are about to do with the work.
6. Run the audit and get a **SHIP / REVISE / HOLD** decision.

**[Open the Quick-use Prompt →](PROMPT.md)**

Some AI tools let you save instructions, upload files, or create reusable projects or assistants. You can use the files here that way when your AI tool supports it, but setup differs by product. **You do not need to install a "Skill" to use Second-Pass Audit.**

## New to GitHub?

GitHub is simply where the public source files live.

You can read any file by clicking its name.

If you want all of the repository files on your computer, use GitHub's **Code** menu and choose **Download ZIP**.

You can also ignore GitHub entirely and use the Quick-use Prompt above.

## Choose what you need

| If you want to... | Open this |
| --- | --- |
| **Try it right now** | [Quick-use Prompt](PROMPT.md) |
| **Use reusable AI instructions** | [Reusable AI Instructions](SKILL.md) |
| **Understand the full method** | [Full Second-Pass Audit](SECOND-PASS-AUDIT.md) |
| **See how it works** | [Examples](EXAMPLES.md) |
| **Understand what it cannot do** | [Limitations](LIMITATIONS.md) |

## The idea

**The problem is not only generation. It is acceptance.**

Second-Pass Audit started from a simple question Kendall E. Matthews repeatedly asked AI:

> **What did you miss?**

Over time, generic self-critique proved too weak. The process became source-grounded: return to the material that should govern the answer, compare directly, identify material gaps, correct them, recheck affected work, and make an acceptance decision.

Later, concepts from software evaluation, regression testing, and acceptance testing helped formalize and strengthen the method. They did not originate it.

## Use it when

Use a Second-Pass Audit when AI-assisted work is important enough that a material omission, unsupported conclusion, missed requirement, or weak interpretation could change what you approve, present, publish, or act on.

You need three inputs:

1. The work or recommendation you are considering.
2. The source, evidence, requirements, records, terms, or other material that should govern it.
3. What you are about to do with the work.

## What it checks

- material omissions
- factual errors
- interpretive errors
- unsupported conclusions
- weak interpretations
- important details given too little weight
- missed constraints or qualifiers
- changed emphasis
- downstream inconsistencies

## Outcomes

**SHIP** — no unresolved material issue remains for the intended use.

**REVISE** — the direction is usable, but material corrections are still required.

**HOLD** — evidence is insufficient, a material issue remains unresolved, or additional qualified review is required.

## Important limit

**Matching the source does not prove the source is right.**

Second-Pass Audit does not prove that the source itself is true, current, complete, or appropriate. It does not replace medical, legal, financial, technical, security, compliance, customer, or other qualified review when that review is required.

The person or organization acting on the work remains responsible for the final decision.

## Additional files

- [ATTRIBUTION.md](ATTRIBUTION.md) — attribution guidance
- [THIRD-PARTY-NOTICES.md](THIRD-PARTY-NOTICES.md) — third-party source boundaries
- [LICENSE](LICENSE) — CC BY 4.0 legal text

## Read the articles

**Start here:** [The Problem Isn't Generation. It's Acceptance: The Second-Pass Audit](https://kendallmatthews.com/second-pass-audit-decision-making/)  
The cornerstone article explains the acceptance problem, the method, its boundaries, and a worked campaign example.

**Origin:** [What Did You Miss? How a Simple Question Became My Second-Pass Audit](https://kendallmatthews.com/what-did-you-miss-second-pass-audit/)  
The origin story shows how a recurring self-check evolved into source comparison, guardrails, correction, rechecks, and an acceptance decision.

Created by Kendall E. Matthews.
