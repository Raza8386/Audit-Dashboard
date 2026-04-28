# Audit Dashboard

A GRC (Governance, Risk & Compliance) resource hub featuring AI governance templates, risk frameworks, and compliance tools — rendered as an interactive HTML viewer.

## Contents

- [Overview](#overview)
- [Templates](#templates)
- [Getting Started](#getting-started)
- [Resources](#resources)

## Overview

This repository provides ready-to-use AI governance documents and an HTML viewer to browse them. It includes the [awesome-grc-ai](awesome-grc-ai/) collection — a curated set of prompts, templates, and scripts for AI + GRC workflows.

## Templates

Open `templates.html` in any browser to view all three templates interactively.

| Template | Type | Frameworks | Complexity |
|---|---|---|---|
| [AI Acceptable Use Policy](awesome-grc-ai/templates/ai-acceptable-use-policy.md) | Policy | NIST AI RMF, ISO 42001, EU AI Act | Intermediate |
| [AI Risk Assessment Framework](awesome-grc-ai/templates/ai-risk-assessment-framework.md) | Framework | NIST AI RMF, ISO 42001, EU AI Act | Advanced |
| [Model Development Lifecycle Standard](awesome-grc-ai/templates/model-development-lifecycle.md) | Standard | NIST AI RMF, ISO 42001, MLOps | Advanced |

### HTML Viewer Features

- Tab-based navigation between all three templates
- Sidebar with section jump-links and search filter
- Template variable placeholders (`{{VARIABLE_NAME}}`) highlighted for easy customisation
- Colour-coded risk matrices (Critical / High / Medium / Low)

## Getting Started

1. Clone the repo
   ```bash
   git clone https://github.com/Raza8386/Audit-Dashboard.git
   cd Audit-Dashboard
   ```

2. Open the template viewer
   ```bash
   # Windows
   start templates.html

   # macOS
   open templates.html

   # Linux
   xdg-open templates.html
   ```

3. Customise a template by replacing the `{{VARIABLE_NAME}}` placeholders with your organisation's details.

## Resources

The `awesome-grc-ai/` directory contains additional GRC resources:

- **[Prompts](awesome-grc-ai/prompts/)** — Claude prompts for SOC 2, PCI DSS, FedRAMP, FISMA, and NIST AI RMF workflows
- **[Scripts](awesome-grc-ai/scripts/)** — Automation scripts for compliance evidence collection (AWS, GitHub)
- **[Templates](awesome-grc-ai/templates/)** — Source markdown for the policy templates above

## License

Templates and resources are released under [CC0-1.0](awesome-grc-ai/LICENSE) — free to use without restriction.
