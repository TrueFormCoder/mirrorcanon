# Style PDFs


This folder contains **distribution-ready PDF artifacts** derived from the editable and Markdown sources.

## Rules
- PDFs are outputs, not sources
- Do not edit PDFs directly
- New versions must increment version numbers
- Old versions may remain for audit purposes

If content changes, update Markdown and editable sources first.,

Naming Convention (Lock This)
MirrorCanon_[ArtifactName]_vX.Y.[md|pages|docx|pdf]
Use the same name across all formats: Example:
	•	MirrorCanon_Editor_OnePage_Guide_v1.3.md
	•	MirrorCanon_Editor_OnePage_Guide_v1.3.pages
	•	MirrorCanon_Editor_OnePage_Guide_v1.3.docx
	•	MirrorCanon_Editor_OnePage_Guide_v1.3.pdf

This makes version mismatches obvious instantly.

⸻

Optional (But Very Smart) Addition

If you want absolute clarity, add a short note to the top of each DOCX/Pages file:

Source-of-truth: Markdown
Layout authority: This file
Distribution: PDF

That prevents collaborators from “fixing text” in layout files.

⸻

Final Verdict
	•	✅ Yes, store DOCX and Pages
	•	✅ Yes, add an editable/ folder with subfolders
	•	✅ Keep Markdown as logic, Pages/DOCX as layout, PDFs as output
	•	❌ Do not let PDFs become sources

This structure is exactly what mature documentation systems use when precision and formatting both matter.
