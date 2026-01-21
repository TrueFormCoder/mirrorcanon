📌 MirrorCanon™ Version-Bump Policy (Lock This)

Add this as docs/governance/versioning-policy.md.

Semantic Versioning Rules

Use vMAJOR.MINOR (no patch numbers).

⸻

MAJOR Version Bump (v1 → v2)

Required when you change meaning or scope.

Examples:
	•	redefining a core term
	•	altering a diagnostic dimension
	•	changing lane definitions
	•	modifying Canon rules or prohibitions
	•	restructuring an Issue’s thesis

Signal: prior citations may need reevaluation.

⸻

MINOR Version Bump (v1.1 → v1.2)

Required when you change expression without changing meaning.

Examples:
	•	formatting improvements
	•	accessibility upgrades
	•	visual refinements
	•	added examples or clarifying sentences
	•	re-layout of the same content

Signal: safe to update without reinterpreting conclusions.

⸻

NO Version Bump

Do not bump versions for:
	•	typo fixes
	•	spacing adjustments
	•	file path changes
	•	repo reorganization

These are silent maintenance.

⸻

Cross-Format Rule (Critical)

If any one of these changes:
	•	Markdown
	•	DOCX / Pages layout
	•	PDF output

…and the others do not match → version mismatch.

All three must carry the same version number.

⸻

Naming Enforcement

Every artifact must match exactly: MirrorCanon_[ArtifactName]_vX.Y.[md|pages|docx|pdf]

If filenames diverge, the artifact is out of compliance.
