# DOCX Layout Sources

This folder contains **DOCX backups** for layout-source documents.

## Purpose
- Cross-platform editing support
- Review markup and comments
- Backup if Pages is unavailable

## Rules
- DOCX files must mirror the latest Pages versions
- Do not treat DOCX as the primary layout authority
- Increment version numbers on any layout change
- Do not edit PDFs directly

DOCX is a fallback for cross-platform editing, not the canonical layout source.

Naming Convention (Lock This)
MirrorCanon_[ArtifactName]_vX.Y.docx

Use the same base name across Markdown, Pages, DOCX, and PDF.

Recommended Header (Add to DOCX Files)
Source-of-truth: Markdown
Layout authority: This file
Distribution: PDF
