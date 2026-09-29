# AI Governance Readiness Agents

**Interactive Multi-Agent AI Governance Readiness Assessment**

AI Governance Readiness Agents is an interactive applied-AI demonstration showing how a seven-agent workflow can analyze enterprise AI evidence, discover Shadow AI, establish an AI inventory, identify governance risks, map controls, support human decision-making, and generate an implementation roadmap.

The demo uses a fictional customer scenario and synthetic evidence to illustrate a practical AI Governance Readiness engagement.

## What This Demo Shows

- AI estate discovery
- Shadow AI identification
- AI inventory and ownership
- Risk and governance condition analysis
- NIST AI RMF control mapping
- Human governance review
- Readiness scoring
- 30/60/90/180-day implementation planning
- Executive decision support

**Core principle:** Evidence first. Agents propose. Humans decide. Unknowns stay visible.

## Governance Analyzer

| # | Agent / Stage | Purpose |
|---|---|---|
| 1 | Evidence Intake | Reviews customer scope, pre-work, and available evidence |
| 2 | Shadow AI Discovery | Identifies AI tools, SDKs, API keys, agent configurations, AI traffic, and unsanctioned usage |
| 3 | Inventory & Ownership | Builds the AI estate register and compares discovered assets with customer-declared AI |
| 4 | Risk & Conditions | Identifies governance conditions, owners, required actions, and next gates |
| 5 | Control Mapping | Maps identified conditions to NIST AI RMF core functions |
| 6 | Governance Review | Introduces a human decision gate for critical and high-risk findings |
| 7 | Roadmap & Scorecard | Generates readiness scores, implementation priorities, and executive recommendations |

## Example Evidence Sources

The fictional assessment includes synthetic examples of:

- Customer pre-work
- Identity provider exports
- Developer AI surveys
- Git repository scans
- Proxy and DNS logs
- CASB reports
- Cloud billing and expense data
- Endpoint / IDE extension inventories
- Vendor and contract registers
- Governance policies and approval records

Each conclusion is classified as:

- **FACT** — confirmed by a specific evidence source
- **ASSUMPTION** — plausible but requires confirmation
- **UNKNOWN** — unresolved and assigned an owner / follow-up action

## Key Outputs

1. Executive Governance Readiness View
2. AI Estate & Ownership Register
3. Developer AI / Shadow AI View
4. Priority Risks & Conditions
5. Target AI Governance Operating Model
6. Governance Readiness Scorecard
7. 30/60/90/180-Day Implementation Roadmap
8. Critical UNKNOWNs & Evidence Owners
9. Review Record & Evidence Coverage

A PDF summary report can also be generated directly from the application.

## Human-in-the-Loop Governance

For critical and high-risk conditions:

```text
Agent recommendation
        ↓
Human review
        ↓
Final disposition
        ↓
Roadmap impact
```

Example dispositions:

- Remediate
- Assure
- Block / Pause
- Accept

## Demo Modes

### Demo Mode
Uses pre-built outputs and synthetic evidence. No API key is required.

### Claude Mode
Uses Anthropic Claude for model-driven workflow stages.

### OpenAI Mode
Uses OpenAI models for model-driven workflow stages.

In live AI modes, model responses are validated before they are presented in the workflow.

## Architecture

This project is intentionally an **interactive demonstration**, not a production backend implementation.

```text
Browser UI
   |
   +-- HTML / CSS / JavaScript
   |
   +-- Synthetic evidence
   |
   +-- Deterministic rules
   |
   +-- Optional Claude API
   |
   +-- Optional OpenAI API
   |
   +-- Human governance review
   |
   +-- Readiness outputs / PDF report
```

This project belongs to the **Applied AI Solutions — Interactive Demos** section of my portfolio.

A separate portfolio section is being developed for **production-grade reference implementations** using backend services, orchestration frameworks, durable state, RAG, observability, policy enforcement, CI/CD, and containerized deployment.

## Run Locally

No build process is required.

```bash
git clone https://github.com/<your-github-username>/ai-governance-readiness-agents.git
cd ai-governance-readiness-agents
open index.html
```

You can also host the repository with GitHub Pages.

## Suggested GitHub Pages URL

```text
https://<your-github-username>.github.io/ai-governance-readiness-agents/
```

## Live AI Usage

When using Claude or OpenAI mode:

- Use only test / demo API keys.
- Use spending limits where available.
- Do not enter real customer evidence.
- Do not use production credentials.
- The fictional scenario and all included evidence are synthetic.

## Fictional Scenario

The demo uses **Arenal Play**, a fictional online casino operator, to illustrate governance-readiness analysis.

No finding or score in this repository relates to any real organization.

## Portfolio Context

This project is part of a broader portfolio focused on enterprise architecture, applied AI, agentic AI, AIOps, AI governance, cloud, networking, security, and automation.

**Portfolio:** https://www.soltelco.com

## Author

**Daniel Mazzini**  
Principal Solutions Architect & Senior Technical Program Manager  
Enterprise Architecture · Applied AI · Agentic AI · Cloud · Networking · Security · Telco

LinkedIn: https://www.linkedin.com/in/daniel-mazzini-22059734/  
Portfolio: https://www.soltelco.com

## Disclaimer

This project is an educational and portfolio demonstration.

- All organizations, evidence, users, risks, and findings are fictional or synthetic.
- The demo is not a compliance certification.
- It does not provide legal advice.
- It is not a substitute for a formal security, privacy, risk, or governance assessment.
- Live AI outputs should be independently reviewed before being used in any real decision.

## License

This repository is provided for portfolio and demonstration purposes. Add the license terms that best fit your intended reuse model.
