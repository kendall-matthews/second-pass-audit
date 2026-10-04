# Second-Pass Audit Method

## Purpose

Second-Pass Audit creates a deliberate acceptance checkpoint for consequential information or work.

The public GitHub version is optimized for AI-assisted work because AI can make incomplete reasoning look unusually finished. The underlying decision discipline can also inform how people inspect advice, recommendations, proposals, and other consequential material.

## Origin

The behavior started with a recurring prompt:

> **What did you miss?**

The limitation became clear: another answer from the same system is still another answer.

The process became source-grounded:

**What did you miss? → Return to the source → Compare → Identify → Correct → Recheck → Decide**

Software evaluation, regression testing, and acceptance-testing concepts later helped make the process more explicit and repeatable.

## Core principle

**Polish is not an acceptance standard.**

**Generation creates a candidate. Verification earns acceptance.**

## Required inputs

The audit requires:

- the current work or recommendation
- the decision-relevant source, evidence, or requirements
- the intended use or decision

A source may be a brief, contract, specification, policy, dataset, research, meeting decision, approved messaging, instructions, records, or another authoritative reference.

## Materiality

Focus on issues that could change scope, meaning, priority, confidence, qualification, sequence, credibility, safety, compliance, usability, or the acceptance decision.

Do not manufacture criticism. A valid audit can return **SHIP**.

## Method

### COMPARE
Return to the source or governing evidence and compare it directly with the current work.

### IDENTIFY
Find material omissions, factual or interpretive errors, unsupported conclusions, weak interpretations, underweighted details, missed constraints, changed emphasis, or downstream inconsistencies.

### CORRECT
Correct what the available authoritative material actually resolves. Preserve supported content.

### RECHECK
Verify the areas affected by the correction so the fix does not create a regression.

### DECIDE
Return **SHIP**, **REVISE**, or **HOLD**.

## Stop rule

The goal is not endless review.

**Slow down at the decision point, not throughout the work.**

Once material issues are resolved, affected areas have been rechecked, and the evidence supports the intended use, stop.

## Broader application

The acceptance principle can travel across domains. The governing source changes.

A contractor proposal may be compared with the requested scope, exclusions, materials, terms, warranties, and competing bids.

An educational recommendation may be checked against the syllabus, rubric, assignment, source material, or learning objective.

A financial recommendation may be checked against statements, terms, contracts, assumptions, tax documents, and qualified advice.

A health-related recommendation may be checked against records, lab results, medication instructions, reputable guidance, and questions for a qualified healthcare professional.

This does not convert Second-Pass Audit into medical, legal, financial, engineering, or other professional expertise. When expert review is required, **HOLD** is an appropriate result.

## Final boundary

**Source fidelity is not source truth.**

An answer can perfectly match a bad or outdated source. The audit may therefore surface a higher-order question:

**Is this the right source to trust for this decision?**
