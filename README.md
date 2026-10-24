# PDF Invoice Local Extractor

> **Tri-Platform Agent Skill** for Claude Desktop / Code, Grok CLI, and Google Antigravity / Gemini.  
> 100% offline, local PDF batch extraction utility isolating invoices and exporting clean Markdown for LLM parsing.

---

## Overview

`pdf-parsing` provides standardized capabilities across conversational AI platforms:
- Completely offline batch extraction utility (extract_to_markdown.py) using pypdf.\n- Automatically isolates PDF files into dedicated workspace subfolders.\n- Translates invoice PDFs into clean, structured Markdown representations.\n- Decouples document parsing from schema structuring for robust LLM-native extraction.\n- Tri-platform NTFS junctions connecting Claude, Grok, and Antigravity.

---

## Tri-Platform Architecture

Zero duplicate code across platforms. Canonical source resides in `.agents`:
- **Canonical Source**: `C:\Users\<you>\.agents\skills\pdf-parsing`
- **Claude**: `C:\Users\<you>\.claude\skills\pdf-parsing` (NTFS Junction)
- **Grok**: `C:\Users\<you>\.grok\skills\pdf-parsing` (NTFS Junction)
- **Antigravity**: `C:\Users\<you>\.gemini\config\skills\pdf-parsing` (NTFS Junction)

---

## Documentation Suite

- [`HOW_TO_USE.txt`](HOW_TO_USE.txt): Standardized user guide and prompt templates.
- [`IMPLEMENTATION_PLAN.md`](IMPLEMENTATION_PLAN.md): Feature checklist and roadmap.
- [`App Changes Tracker.html`](App%20Changes%20Tracker.html): Interactive visual version log.
- [`SKILL.md`](SKILL.md): Agent system instructions and triggers.
