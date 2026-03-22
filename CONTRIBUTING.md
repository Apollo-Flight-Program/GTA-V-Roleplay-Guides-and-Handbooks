# Contributing to GTA V Roleplay Guides and Handbooks

Thank you for considering a contribution to this project. This repository is a free, open, community-driven collection of GTA V roleplay documentation — and it gets better every time someone adds to it.

---

## What Contributions Are Welcome

We welcome the following kinds of contributions:

- **New guides** — Original content covering any aspect of GTA V roleplay: general RP concepts, platform-specific guides (FiveM, RageMP, alt:V), role-specific handbooks, server profiles, or reference material.
- **Corrections** — Factual corrections, updated information, or fixes to inaccurate content.
- **Expansions** — Additional depth, examples, or context added to existing guides.
- **Translations** — Translations of existing guides into other languages.
- **Structural improvements** — Better organization, navigation aids, or cross-references between related guides.

We do **not** accept:
- Promotional content for specific servers, communities, or products.
- Content that is copied from copyrighted sources without permission.
- Content that targets, harasses, or demeans individuals or communities.

---

## How to Contribute

### 1. Fork the Repository

Click the **Fork** button on the repository's GitHub page to create your own copy.

### 2. Clone Your Fork

```bash
git clone https://github.com/YOUR-USERNAME/Roleplay-Guides-and-Handbooks.git
cd Roleplay-Guides-and-Handbooks
```

### 3. Create a Branch

Create a descriptive branch for your changes:

```bash
git checkout -b add-ems-roleplay-guide
```

### 4. Make Your Changes

Add or edit files following the conventions described below. Write your content, review it, and ensure it matches the style and quality of existing guides.

### 5. Commit and Push

```bash
git add .
git commit -m "Add EMS roleplay guide for FiveM servers"
git push origin add-ems-roleplay-guide
```

### 6. Open a Pull Request

Go to the original repository on GitHub and open a Pull Request from your branch. In the PR description:

- Summarize what you added or changed.
- Explain why the addition or change is valuable.
- Note any existing guides that your contribution relates to or builds upon.

A maintainer will review your PR and may suggest changes before merging.

---

## Folder Structure

The repository is organized into the following top-level directories:

```
Roleplay-Guides-and-Handbooks/
├── Roleplay in General/          ← Platform-agnostic guides, general RP concepts
│   ├── Notable-Roleplay-Servers/ ← Server profiles and history
│   └── Articles/                 ← Long-form articles and essays
├── Guides-To-Each-Role/          ← Role-specific guides (LEO, EMS, civilian, criminal, etc.)
├── Guides-for-Server-Owners/     ← Server administration and management guides
├── References/                   ← Reference material, glossaries, code lists
├── README.md
├── CONTRIBUTING.md               ← You are here
├── SUPPORT.md
└── LICENSE
```

When adding new content:

- Place it in the most appropriate existing directory.
- If no existing directory fits, propose a new one in your PR description.
- Server-specific profiles go in `Roleplay in General/Notable-Roleplay-Servers/` within a directory named after the server.
- Role-specific guides go in `Guides-To-Each-Role/`.

---

## File Naming Conventions

- Use **kebab-case** for file and directory names: `my-guide-title.md`, not `My Guide Title.md` or `my_guide_title.md`.
- Server profile directories use the server's common name: `NoPixel-Server/`, `Eclipse-RP-Server/`, `GTA-World-Server/`.
- All guide files should use the `.md` (Markdown) extension.
- Choose descriptive, specific names: `Fear-RP-and-Value-of-Life.md` is better than `guide3.md`.

---

## Writing Style Guide

Consistency matters. Please match the style of existing guides:

### Tone

- **Informative, not promotional.** Describe what something is and how it works. Do not sell it.
- **Neutral and fair.** When covering servers, communities, or individuals, present facts and context rather than opinion or judgment.
- **Direct.** Say what you mean. Avoid filler, hedging, and unnecessary qualifiers.

### Structure

- Start every guide with a `#` title.
- Use `---` horizontal rules to separate major sections.
- Use `##` for major sections and `###` for subsections.
- Include a brief introductory paragraph or italicized subtitle explaining what the guide covers.
- For server profiles, include a **Key Facts** table near the top with essential information (platform, culture, founding date, current status).

### Formatting

- Use **bold** for key terms when first introduced.
- Use *italics* for emphasis, titles of external works, or direct quotes.
- Use bullet points for lists of items.
- Use numbered lists for sequential steps or procedures.
- Use code blocks for commands, code, or technical syntax.

### Content Quality

- **Be accurate.** Verify facts before including them. Cite sources where possible.
- **Be thorough.** A complete guide is more valuable than a brief one. Aim for depth.
- **Be respectful.** Real people built these communities. Discuss their work with the respect it deserves, even when covering failures or controversies.
- **Provide context.** Connect specific topics to the broader landscape of GTA V roleplay when relevant.

---

## Content Standards

### Minimum Quality

All contributions should meet the following minimum standards:

- Written in clear, grammatically correct English.
- Free of spelling errors (use a spell checker).
- Factually accurate to the best of the author's knowledge.
- Properly formatted in Markdown.
- Long enough to provide genuine value (a two-paragraph guide rarely justifies its own file).

### Server Profiles

Server profiles should cover, at minimum:

- Server history and founding.
- Platform and technical details.
- Culture and community style.
- Unique features or contributions.
- Impact on the broader RP community.
- Lessons learned.
- Current status.
- Sources.

See the existing NoPixel, DOJRP, Eclipse RP, FamilyRP, and GTA World profiles for examples.

### Role Guides

Role-specific guides should cover, at minimum:

- What the role is and what it involves.
- How to get started in the role.
- Common expectations and standards.
- Tips for doing the role well.
- Common mistakes to avoid.
- How the role fits into the broader RP ecosystem.

---

## Code of Conduct

Contributors are expected to:

- **Be respectful** in all interactions — in PRs, issues, discussions, and commit messages.
- **Be constructive** when reviewing others' contributions.
- **Be honest** about sources, accuracy, and the limits of their knowledge.
- **Not harass, demean, or target** any individual, community, or group.

Contributions that violate these expectations will be rejected. Repeated violations may result in being blocked from the repository.

---

## AI-Assisted Content

This project acknowledges the use of AI tools in content creation (as noted in the README). AI-assisted contributions are welcome, provided:

- The contributor reviews and verifies all AI-generated content for accuracy.
- The content meets the same quality standards as human-written content.
- Factual claims are verified against reliable sources.

AI-generated content that has not been reviewed or verified will not be accepted.

---

## License

All content in this repository is released under the **Creative Commons Zero v1.0 Universal (CC0)** license. By contributing, you agree that your contributions will be released under the same license. This means:

- Your contributions become part of the public domain.
- Anyone can use, copy, modify, and distribute them without restriction or attribution.
- You cannot later revoke this permission.

If you are not comfortable with these terms, please do not contribute.

See [LICENSE](LICENSE) for the full legal text.

---

## Questions?

If you have questions about contributing that are not answered here, open an issue on the repository and a maintainer will respond.

Thank you for helping build a better resource for the GTA V roleplay community.
