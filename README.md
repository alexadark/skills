# Claude Code Skills

A collection of [Claude Code](https://claude.com/claude-code) skills I use daily for development, content creation, and business operations. Each skill lives in its own repo, this is the index.

## Skills

### Development tools

| Skill | Description |
|---|---|
| [audit-codebase-skill](https://github.com/alexadark/audit-codebase-skill) | Codebase health audit: AI-readiness scoring, bug detection (Assay), and optional Codex deep adversarial pass with synthesis. |
| [plan-preview-skill](https://github.com/alexadark/plan-preview-skill) | Generate a standalone HTML preview of any project plan as a beautiful, navigable single-file document. |
| [skill-creator-skill](https://github.com/alexadark/skill-creator-skill) | Create, iterate, and optimize Claude Code skills with eval benchmarking. Lean fork of Anthropic's skill creator. |
| [review-skill-skill](https://github.com/alexadark/review-skill-skill) | Review and audit Claude Code skills for structure, effectiveness, and strategic design. |

### Content & media

| Skill | Description |
|---|---|
| [media-extract-skill](https://github.com/alexadark/media-extract-skill) | Universal media extraction (YouTube, web, local files) with structured output for downstream skills. |
| [video-animals](https://github.com/alexadark/video-animals) | Generate viral AI animal videos from text descriptions using Kie CLI. |
| [post-social](https://github.com/alexadark/post-social) | Distribute video content to TikTok, Instagram, YouTube via Blotato MCP. |

### Business & CRM

| Skill | Description |
|---|---|
| [sales-call-skill](https://github.com/alexadark/sales-call-skill) | Sales call analysis and follow-up automation. |
| [ghl-onboard-skill](https://github.com/alexadark/ghl-onboard-skill) | Onboard new clients into GoHighLevel CRM with welcome email, tags, pipeline opportunities, and follow-up tasks. |

## Installing a skill

Each skill repo has its own detailed README with prerequisites and usage. Common install pattern:

```bash
# Clone the skill into your dev folder
git clone https://github.com/alexadark/<skill-name> ~/DEV/skills/<skill-name>

# Symlink into Claude Code's skills directory
ln -s ~/DEV/skills/<skill-name> ~/.claude/skills/<skill-name>
```

After this, the skill is invocable inside any Claude Code session.

## License

Each skill is licensed under MIT. See the individual repos for details.

## Contact

Built by Alexandra Spalato — [@alexadark](https://github.com/alexadark)
