# Startup Fundraising Skill for Codex

[![MIT License](https://img.shields.io/github/license/songalobung/startup-fundraising-skill)](LICENSE)

An open source AI skill that helps startup founders make practical financing decisions and prepare for fundraising. Compare funding paths, research investors, connect a raise to milestones, and create evidence-backed pitch materials.

## What it helps with

- Decide whether outside capital fits the company's goals and compare relevant funding options.
- Research customer demand, competitors, market scope, and investor fit with dated sources.
- Plan a raise around the next measurable company milestone and a realistic cash plan.
- Prepare a concise investor narrative, pitch deck, outreach drafts, and diligence checklist.
- Use optional specialist agents for independent funding, market, and investor research when the task is substantial and the AI runtime supports delegation.

## Install in Codex

In Codex, run the skill installer with this repository path:

```text
$skill-installer install https://github.com/songalobung/startup-fundraising-skill/tree/main/skills/seed-fundraising
```

The skill is available in your next Codex turn. To install manually, copy [`skills/seed-fundraising`](skills/seed-fundraising) into your Codex skills directory as `seed-fundraising`.

## Try it

- “Help me decide whether to raise venture capital or use another funding path.”
- “Build a sourced investor shortlist for my pre-seed company in Kenya.”
- “Review my raise amount against the milestones and runway in this plan.”
- “Turn these verified traction metrics into an investor pitch outline.”
- “Research the market and investor fit in parallel, then reconcile the sources and assumptions.”

## How it works

The skill starts with founder goals, company location, stage, business model, demand evidence, and the milestone the capital should fund. It separates verified facts from founder-reported claims, estimates, and unknowns; adapts metrics to the business; and treats investor fit as a researched hypothesis.

For substantial work, and only when subagents are available, it can split independent research among a funding strategist, market and customer researcher, and investor researcher. The lead agent remains responsible for checking source quality, reconciling numbers and assumptions, and producing one coherent result. Small or sequential tasks stay with one agent.

## Project structure

```text
skills/
└── seed-fundraising/
    ├── SKILL.md
    └── SOURCES.md
```

## Scope and safeguards

This skill supports research and business planning; it does not provide legal, tax, accounting, or investment advice or guarantee fundraising. Securities rules vary by jurisdiction. Consult qualified local advisers on transaction terms, offering rules, and compliance. The skill requires user authorization before external messages, public posts, file sharing, or other consequential actions.

## Contributing

See [CONTRIBUTING.md](CONTRIBUTING.md) for how to suggest improvements. Please do not include private company, customer, financial, or personal data in public issues.

## License

MIT. See [LICENSE](LICENSE).

