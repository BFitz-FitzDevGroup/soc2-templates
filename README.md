# SOC 2 Templates

A complete SOC 2 compliance template library — 19 policies, 40+ process documents, and 43 evidence explanations mapped to the Trust Services Criteria. Free and open source under the MIT license.

Formerly sold as a paid product at **security-docs.com**. Now maintained here as an open-source resource for startups and small companies working toward SOC 2 compliance.

---

## Table of Contents

- [What's Included](https://c0f715d3-c9d9-4cb7-a2b3-7dcfce64e835.frame.claudeusercontent.com/_f/1790033360-bd5d/#whats-included)
- [Repository Structure](https://c0f715d3-c9d9-4cb7-a2b3-7dcfce64e835.frame.claudeusercontent.com/_f/1790033360-bd5d/#repository-structure)
- [How to Use](https://c0f715d3-c9d9-4cb7-a2b3-7dcfce64e835.frame.claudeusercontent.com/_f/1790033360-bd5d/#how-to-use)
- [Why Open Source](https://c0f715d3-c9d9-4cb7-a2b3-7dcfce64e835.frame.claudeusercontent.com/_f/1790033360-bd5d/#why-open-source)
- [License](https://c0f715d3-c9d9-4cb7-a2b3-7dcfce64e835.frame.claudeusercontent.com/_f/1790033360-bd5d/#license)
- [Contributing](https://c0f715d3-c9d9-4cb7-a2b3-7dcfce64e835.frame.claudeusercontent.com/_f/1790033360-bd5d/#contributing)
- [About](https://c0f715d3-c9d9-4cb7-a2b3-7dcfce64e835.frame.claudeusercontent.com/_f/1790033360-bd5d/#about)

---

## What's Included

**19 policies**, each provided in four variants:

- **Enterprise** — comprehensive version for larger organizations
- **SMB** — streamlined version for small and mid-sized companies
- **Quick Reference** — one-page summary for employees
- **Workbook** — fill-in-the-blank implementation guide

**40+ process documents** — the forms, templates, checklists, and agreements referenced by the policies (access request forms, change request forms, risk registers, business continuity plans, network diagrams, and more).

**43 evidence explanations** — Word documents describing what each piece of audit evidence should contain and how auditors will evaluate it.

**4 implementation guides** — a quick-start checklist, an implementation timeline, a priority guide, and a complete SOC 2 control mapping spreadsheet that ties every artifact back to the specific Trust Services Criteria it addresses.

---

## Repository Structure

```
soc2-templates/
├── policies/       # 19 policies × 4 variants (enterprise, SMB, quick-reference, workbook)
├── documents/      # Process templates, forms, checklists, and agreements
├── evidence/       # Evidence explanations for audit preparation
└── guides/         # Implementation guides and SOC 2 control mapping spreadsheet
```

Every file is a Word document (`.docx`) or Excel spreadsheet (`.xlsx`) — ready to open, customize, and use.

---

## How to Use

**If you're starting from zero:**

1. Read `guides/SOC 2 Priority Implementation Guide.docx` first to understand which artifacts to tackle in what order.
2. Open `guides/SOC2 Control Mapping Spreadsheet.xlsx` to see how each document maps to specific Trust Services Criteria.
3. Start with the **policies** — pick the enterprise or SMB variant that fits your company size. Customize company name, roles, and specific tooling references.
4. Add the **process documents** that support your chosen policies (change request forms, access request forms, etc.).
5. Use the **evidence explanations** to understand what you'll need to show auditors during your Type 1 or Type 2 audit.

**If you're preparing for an audit:**

Jump straight to `guides/SOC 2 Complete Bundle Quick Start Checklist.docx` and use the control mapping spreadsheet to track which evidence you've assembled against which control.

**A note on customization:** These are templates. Every one of them will need to be tailored to your company, your systems, and your specific implementation. Don't ship them unchanged — auditors will spot boilerplate immediately.

---

## Why Open Source

These templates were originally sold as a paid product from mid-2024 through 2026. Two things changed that made open-sourcing the right move:

1. **AI can now generate credible starting drafts of SOC 2 documentation** for a fraction of the price. A paid template library is no longer the best value proposition for early-stage companies.
2. **A curated, human-refined starting point is still useful** — arguably more so, because it's a stable reference rather than a fresh AI generation each time. This repo offers that starting point without the paywall.

If these templates help you avoid a few weekends of wrestling with SOC 2 documentation, they've done their job.

---

## License

Released under the **MIT License**. See [LICENSE](https://c0f715d3-c9d9-4cb7-a2b3-7dcfce64e835.frame.claudeusercontent.com/_f/1790033360-bd5d/LICENSE) for the full text.

You can use these templates in commercial products, modify them freely, and redistribute them — including sublicensing under different terms if you build on them. No attribution required (though it's appreciated).

**Disclaimer:** These templates are provided as-is. They are not legal advice, they do not guarantee SOC 2 compliance, and they have not been reviewed for your specific situation by an auditor or attorney. Use them as a starting point, not a substitute for professional guidance.

---

## Contributing

This repository is **provided as-is and not actively maintained**. Pull requests are welcome — especially for typos, factual corrections, or improved template language — but responses may be slow or non-existent. If you find something useful to fix, fork freely.

Issues are open for reporting problems but should not be relied on as a support channel.

---

## About

Built and open-sourced by **[Brent Fitzpatrick](https://github.com/BFitz-FitzDevGroup)** at **[FitzDevGroup](https://fitzdevgroup.com/)** — a Sacramento-based solo development consultancy.

If you're working on a compliance or security engineering project and want help beyond templates, [get in touch](https://fitzdevgroup.com/).