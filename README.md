# Project Review Feedback Pack

**Status:** Public feedback draft  
**Data:** Fake sample only  
**Purpose:** Invite comments from process, data, review, and workflow practitioners

## Why This Exists

We are designing a generic project review workflow. The goal is to improve how teams separate facts, assumptions, risks, missing items, and decision conditions before a project moves to a higher review stage.

This pack is intentionally small. It does not include protected business material, live records, formulas, production instructions, access material, organization names, or client names.

## What We Want Feedback On

Please comment on:

1. What fields are missing from the input schema?
2. Which risk categories should be separated more clearly?
3. What validation rules would prevent weak review output?
4. What output format would be easiest for a review team to use?
5. What edge cases should an assisted review workflow handle?

## What Is Out Of Scope

Please do not ask for or share:

- live project records
- private organization information
- client names
- private status updates
- protected documents
- formulas or decision methods
- production instructions
- access material
- advice on a specific live matter

## Files

| File | Purpose |
|---|---|
| `sample_project_fake.json` | Fake sample project for discussion |
| `project_review_input_schema_public.json` | Minimal public schema for feedback |
| `public_review_checklist.md` | Generic review checklist |
| `community_posts.md` | Ready-to-use GitHub/LinkedIn post drafts |
| `.github/ISSUE_TEMPLATE/feedback.md` | GitHub issue template for structured comments |

## Suggested Review Lens

Use this structure in your comment:

```text
ROLE:
Process / Data / Review / Workflow / Operations / Other

WHAT IS MISSING:

WHAT IS UNCLEAR:

WHAT RISK WOULD YOU ADD:

WHAT VALIDATION RULE WOULD YOU ADD:

WHAT WOULD MAKE THIS MORE USEFUL:
```

## Core Principle

A review workflow should not mix verified facts with assumptions. If evidence is incomplete, the default decision should be conditional or pending, not final.
