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
| [efficient-delegation-skill](https://github.com/alexadark/efficient-delegation-skill) | Claude Code skill: keep frontier models on judgment-only work, route volume tasks to cheaper executors (Codex, Sonnet, Haiku). |
| [garden-check-skill](https://github.com/alexadark/garden-check-skill) | Read-only audit of your Claude Code setup: dead file references, rules whose paths never match, orphaned memory entries, duplicated instructions. |
| [claude-api-skill](https://github.com/alexadark/claude-api-skill) | Lightweight replacement for Claude Code's built-in claude-api skill: ~1k tokens on trigger instead of ~340k, with model IDs and prices verified live. |

### Content & media

| Skill | Description |
|---|---|
| [media-extract-skill](https://github.com/alexadark/media-extract-skill) | Universal media extraction (YouTube, web, local files) with structured output for downstream skills. |
| [video-animals](https://github.com/alexadark/video-animals) | Generate viral AI animal videos from text descriptions using Kie CLI. |
| [post-social](https://github.com/alexadark/post-social) | Distribute video content to TikTok, Instagram, YouTube via Blotato MCP. |
| [content-ideas-skill](https://github.com/alexadark/content-ideas-skill) | Turn a topic into a search-intent content plan and ship it as a shareable page via the ideas CLI and plan-preview. |
| [compress-video-skill](https://github.com/alexadark/compress-video-skill) | Shrink a video to 480p with FFmpeg, hardware-accelerated on macOS. |

### Business & CRM

| Skill | Description |
|---|---|
| [sales-call-skill](https://github.com/alexadark/sales-call-skill) | Sales call analysis and follow-up automation. |
| [ghl-onboard-skill](https://github.com/alexadark/ghl-onboard-skill) | Onboard new clients into GoHighLevel CRM with welcome email, tags, pipeline opportunities, and follow-up tasks. |

## CLI tools

Standalone command-line tools, several wrapped into skills above.

| CLI | Description |
|---|---|
| [ideas-cli](https://github.com/alexadark/ideas-cli) | Print Google autocomplete suggestions for a topic, one per line. No API key. Powers the content-ideas skill. |
| [ghl-cli](https://github.com/alexadark/ghl-cli) | Command-line interface for GoHighLevel API v2. 17 command domains, 80+ operations. |
| [kie-cli](https://github.com/alexadark/kie-cli) | CLI for Kie.AI, generate images and videos with Kling, Veo 3, and Nano Banana 2. |

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
