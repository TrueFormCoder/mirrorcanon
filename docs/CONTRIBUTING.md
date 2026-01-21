MirrorCanon™ Contributor Onboarding

Welcome. MirrorCanon™ is a governed system, not an open-ended content project. This document explains how to contribute without causing drift.

⸻

Canonical Principle

MirrorCanon™ separates logic, layout, and distribution.
	•	Markdown defines meaning
	•	Pages / DOCX define layout
	•	PDFs are outputs only

No file type substitutes for another.

⸻

Folder Structure (Authoritative)

mirrorcanon/
├── assets/
│   ├── public-access/
│   ├── press/
│   ├── scholar-canon/
│   └── institutional-framework/
│
├── docs/
│   ├── style/
│   │   ├── canon-style.md
│   │   ├── mirrortone-style.md
│   │   ├── visual-system.md
│   │   ├── symbol-library.md
│   │   ├── editable/
│   │   │   ├── pages/
│   │   │   └── docx/
│   │   └── pdf/
│   ├── governance/
│   │   ├── lane-rules.md
│   │   └── versioning-policy.md
│   └── CONTRIBUTING.md
│
├── issues/
│   ├── issue-001-succession/
│   └── issue-002-godfather/


⸻

Lane Governance (Required)

Every asset must declare:
	•	Lane (Public / Press / Scholar / Institutional)
	•	Reading grade
	•	Intended use

Assets may not cross lanes without redesign.

⸻

Writing Rules (Canon)
	•	No em dashes
	•	No advice language
	•	No therapy or fandom terms
	•	One claim per sentence where possible
	•	Each paragraph must include:
	•	a mechanism
	•	a consequence
	•	an institutional noun

MirrorTone™ relaxes rhythm but not truth.

⸻

Visual Rules
	•	Public = simple, calming, single symbol
	•	Press = editorial caricature only
	•	Scholar = typographic-first
	•	Institutional = diagrammatic, gold-only

If a General Counsel would object, downgrade to Institutional.

⸻

Versioning (Non-Negotiable)

Artifacts use semantic versions: vMAJOR.MINOR
	•	MAJOR → meaning or scope changes
	•	MINOR → layout, clarity, accessibility

Markdown, Pages/DOCX, and PDF must match versions.

PRs with mismatched versions are rejected.

⸻

Final Rule

If you are unsure:
	•	do not improvise
	•	do not optimize for cleverness
	•	default to lower volatility

Structure beats speed.

⸻

✅ Status Summary

You now have:
	•	Correct Apple Pages workflow (no hacks)
	•	CI rules that prevent silent divergence
	•	A contributor doc that explains why, not just what
	•	A repo that enforces discipline instead of relying on memory

This is field-level operational maturity.
