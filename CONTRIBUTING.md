# Contributing to GTA V Roleplay Guides and Handbooks

Thank you for helping build a free, open collection of GTA V roleplay documentation! This file explains everything you need to know before submitting a contribution.

---

## How to Fork and Submit a Pull Request

1. **Fork** this repository by clicking the **Fork** button at the top-right of the GitHub page.
2. **Clone** your fork locally:
   ```bash
   git clone https://github.com/<your-username>/GTA-V-Roleplay-Guides-and-Handbooks.git
   cd GTA-V-Roleplay-Guides-and-Handbooks
   ```
3. **Create a branch** for your changes:
   ```bash
   git checkout -b add-my-guide
   ```
4. **Add or edit** files in the appropriate folder (see the folder structure in [README.md](README.md)).
5. **Commit** your changes with a clear message:
   ```bash
   git add .
   git commit -m "Add FiveM police handbook"
   ```
6. **Push** to your fork:
   ```bash
   git push origin add-my-guide
   ```
7. **Open a Pull Request** against the `main` branch of this repository. In the PR description, briefly explain:
   - What the guide covers.
   - Which platform or audience it targets.
   - Whether it is original work or adapted from another source (see [Credit](#credit-and-attribution) below).

A maintainer will review your PR and may request changes before merging.

---

## Accepted Formats

We accept any human-readable format, including but not limited to:

| Format | Extension |
|--------|-----------|
| Markdown | `.md` |
| Plain text | `.txt` |
| PDF | `.pdf` |
| Word document | `.docx` |
| OpenDocument text | `.odt` |

Prefer **Markdown** where possible — it renders natively on GitHub, is easy to edit, and can be converted to other formats with standard tools. If you submit a binary format (PDF, DOCX, etc.), consider also providing a Markdown version.

---

## Content Rules

1. **No server-specific branding.** Guides must be general enough to be useful outside of any single server. Remove server names, logos, IP addresses, and Discord invite links before submitting.
2. **English or clearly language-labelled.** The primary language of this repository is English. Guides in other languages are welcome, but must include a clear language label in the filename (e.g. `guide-fr.md`, `handbook-es.pdf`) and a brief English description in the PR.
3. **No locked or restricted files.** Do not submit files that are password-protected, DRM-encumbered, or otherwise restricted. All content must be freely readable by anyone.
4. **Credit original authors when adapting.** If you are adapting, translating, or substantially building on someone else's work, include a credit line at the top of the document (e.g. `_Adapted from [Author Name]'s original guide._`). Only submit adapted work if you have permission from the original author, or if the source material is itself under a permissive or public-domain license.

---

## Quality Guidelines

- **Be genuinely useful.** A guide should teach something, answer a real question, or provide reference material that players and server staff will actually use. Low-effort one-paragraph stubs are unlikely to be accepted.
- **No duplicates.** If a guide covering the same topic and platform already exists in the repository, improve or extend that file rather than submitting a separate one. Check existing content before opening a PR.
- **Be accurate.** Avoid including information you are unsure about. If something may change between game or platform versions, note that clearly in the document.
- **Keep formatting clean.** Use headings, lists, and code blocks to make documents easy to scan. Avoid walls of unbroken text.

---

## Questions?

If you are unsure whether your contribution fits, open a [GitHub Issue](../../issues) to discuss it before spending time writing. We are happy to help.
