<p align="center">
  <img src="https://img.shields.io/badge/Skills-31-brightgreen" alt="31 Skills">
  <img src="https://img.shields.io/badge/License-MIT-blue" alt="MIT License">
  <img src="https://img.shields.io/badge/PRs-Welcome-orange" alt="PRs Welcome">
  <img src="https://img.shields.io/github/stars/yoanbernabeu/producthunt-skills?style=social" alt="GitHub Stars">
</p>

<h1 align="center">Product Hunt Launch Skills</h1>

<p align="center">
  <strong>31 AI Agent Skills to launch your product on Product Hunt like a pro.</strong><br>
  Strategy, content, marketing, compliance, analytics — everything you need.
</p>

<p align="center">
  <a href="#quick-install">Install</a> •
  <a href="#all-31-skills">Skills</a> •
  <a href="#example-usage">Usage</a> •
  <a href="#contributing">Contribute</a>
</p>

---

## Quick Install

```bash
npx skills add yoanbernabeu/producthunt-skills
```

**That's it.** Works with Claude Code, Cursor, Codex, OpenCode, Windsurf, and 30+ AI agents.

### One-Liners

```bash
# Install everything (31 skills)
npx skills add yoanbernabeu/producthunt-skills

# Install only strategy skills
npx skills add yoanbernabeu/producthunt-skills --skill ph-launch-strategy

# Install globally (available in all projects)
npx skills add yoanbernabeu/producthunt-skills -g

# List all available skills
npx skills add yoanbernabeu/producthunt-skills --list

# Install to specific agents
npx skills add yoanbernabeu/producthunt-skills -a claude-code -a cursor

# Non-interactive (CI/CD friendly)
npx skills add yoanbernabeu/producthunt-skills --all -y
```

### Other Installation Methods

<details>
<summary><strong>Claude Code Plugin</strong></summary>

```bash
/plugin marketplace add yoanbernabeu/producthunt-skills
/plugin install ph-complete@producthunt-launch-skills
```
</details>

<details>
<summary><strong>Manual Installation</strong></summary>

Copy the `skills/` directory to:
- **Global**: `~/.claude/skills/` (or `~/.cursor/skills/`, etc.)
- **Project**: `.claude/skills/` (or `.cursor/skills/`, etc.)
</details>

---

## Why These Skills?

Launching on Product Hunt is **hard**. One wrong move and you're shadow-banned. Miss the algorithm's sweet spot and you're buried. These skills give your AI agent **expert-level knowledge** so you don't have to learn the hard way.

| Challenge | Skill That Helps |
|-----------|------------------|
| "What day should I launch?" | `ph-timing-optimizer` |
| "My tagline sucks" | `ph-tagline-writer` |
| "How do I avoid getting banned?" | `ph-ban-prevention` |
| "What do I do on launch day?" | `ph-launch-day-checklist` |
| "How do I find a hunter?" | `ph-hunter-finder` |

---

## All 31 Skills

### Strategy & Planning
| Skill | What It Does |
|-------|--------------|
| `ph-launch-strategy` | Define objectives, create 4-6 week timeline |
| `ph-competitor-analysis` | Analyze competing launches, benchmark top performers |
| `ph-timing-optimizer` | Choose optimal day/time for your goals |

### Content Creation
| Skill | What It Does |
|-------|--------------|
| `ph-tagline-writer` | Craft compelling taglines under 60 characters |
| `ph-description-writer` | Write converting descriptions (AIDA, PAS, FAB) |
| `ph-maker-comment` | Create authentic first comments |
| `ph-thumbnail-creator` | Design scroll-stopping thumbnails and GIFs |
| `ph-gallery-assets` | Build compelling image galleries |
| `ph-video-demo` | Script and structure demo videos (30-60s) |

### Marketing & Outreach
| Skill | What It Does |
|-------|--------------|
| `ph-email-strategy` | Plan email waves across timezones |
| `ph-social-media-launch` | Coordinate Twitter/LinkedIn/Facebook |
| `ph-community-outreach` | Engage Reddit, Indie Hackers, HN |
| `ph-supporter-network` | Build and activate your network |

### Launch Day
| Skill | What It Does |
|-------|--------------|
| `ph-launch-day-checklist` | Hour-by-hour execution plan |
| `ph-comment-responder` | Respond effectively to comments (< 9 min) |
| `ph-real-time-monitor` | Track and adjust in real-time |

### Compliance & Risk
| Skill | What It Does |
|-------|--------------|
| `ph-ban-prevention` | Avoid shadow bans and penalties |
| `ph-algorithm-guide` | Understand ranking factors |
| `ph-safe-messaging` | Use approved language patterns |

### Hunters & Profile
| Skill | What It Does |
|-------|--------------|
| `ph-hunter-finder` | Find and approach top hunters |
| `ph-profile-optimizer` | Build maker reputation |

### Pricing & Offers
| Skill | What It Does |
|-------|--------------|
| `ph-launch-offers` | Create exclusive PH deals |
| `ph-pricing-psychology` | Leverage FOMO and urgency |

### Analytics
| Skill | What It Does |
|-------|--------------|
| `ph-analytics-setup` | Configure tracking tools |
| `ph-conversion-tracking` | Measure launch performance and ROI |

### Post-Launch
| Skill | What It Does |
|-------|--------------|
| `ph-post-launch-followup` | Thank supporters, collect reviews |
| `ph-content-recycling` | Repurpose launch assets |
| `ph-relaunch-strategy` | Plan your next launch (v2.0) |
| `ph-seo-benefits` | Maximize SEO value from PH backlink |

### Awards & Features
| Skill | What It Does |
|-------|--------------|
| `ph-newsletter-pitch` | Get featured in PH newsletter |
| `ph-golden-kitty` | Strategy for Golden Kitty Awards |

---

## Skill Packs

Install skills by category:

| Pack | Skills | Description |
|------|--------|-------------|
| `ph-strategy` | 3 | Strategic planning, timing, competitor analysis |
| `ph-content` | 6 | Taglines, descriptions, thumbnails, videos |
| `ph-marketing` | 4 | Email, social media, community outreach |
| `ph-launch-day` | 3 | Launch day execution and monitoring |
| `ph-compliance` | 3 | Ban prevention, algorithm, safe messaging |
| `ph-hunters` | 2 | Finding hunters, profile optimization |
| `ph-pricing` | 2 | Launch offers and pricing psychology |
| `ph-analytics` | 2 | Analytics setup and conversion tracking |
| `ph-post-launch` | 4 | Follow-up, content recycling, relaunch |
| `ph-awards` | 2 | Newsletter featuring, Golden Kitty |
| **`ph-complete`** | **31** | **All skills — complete launch toolkit** |

---

## Supported AI Agents

| Agent | Project Path | Global Path |
|-------|--------------|-------------|
| Claude Code | `.claude/skills/` | `~/.claude/skills/` |
| Cursor | `.cursor/skills/` | `~/.cursor/skills/` |
| Codex | `.codex/skills/` | `~/.codex/skills/` |
| OpenCode | `.opencode/skill/` | `~/.config/opencode/skill/` |
| Windsurf | `.windsurf/skills/` | `~/.windsurf/skills/` |

---

## Example Usage

Just ask your AI agent:

```
"Help me plan my Product Hunt launch"

"Write a tagline for my SaaS product"

"Create a launch day checklist"

"Check if my email is PH-compliant"

"When is the best day to launch?"

"How do I avoid getting shadow-banned?"

"Find hunters in the AI/developer tools space"
```

---

## Key Product Hunt Rules

| Rule | Why It Matters |
|------|----------------|
| **Never ask for upvotes** | Ask for "support" or "feedback" instead — violating this = ban |
| **Launch at 12:01 AM PST** | Maximize your 24-hour window |
| **First 4 hours are critical** | Algorithm weights early momentum heavily |
| **Respond to every comment** | Engagement depth boosts ranking |
| **Stagger your outreach** | All-at-once looks spammy to algorithm |

---

## Quick Start Guide

1. **Install**: `npx skills add yoanbernabeu/producthunt-skills`
2. **Plan**: Start with `ph-launch-strategy` to define goals
3. **Time**: Use `ph-timing-optimizer` to pick launch date
4. **Create**: Work through content skills for assets
5. **Comply**: Review with `ph-ban-prevention` before launch
6. **Launch**: Execute with `ph-launch-day-checklist`
7. **Optimize**: Follow up with post-launch skills

---

## Resources

- [Product Hunt Help Center](https://help.producthunt.com)
- [Product Hunt Launch Guide](https://www.producthunt.com/launch)
- [Community Guidelines](https://help.producthunt.com/en/articles/3615694-community-guidelines)
- [Skills CLI](https://github.com/vercel-labs/skills) - The open agent skills tool
- [Skills Directory](https://skills.sh) - Browse available skills

---

## Contributing

Contributions welcome! See [CONTRIBUTING.md](CONTRIBUTING.md) for guidelines.

```bash
# Fork, clone, and create a branch
git checkout -b feature/new-skill

# Add your skill following the SKILL.md format
# Submit a pull request
```

---

## License

[MIT](LICENSE) — Feel free to use, modify, and distribute.

---

<p align="center">
  <strong>Built by the community, for the community.</strong><br><br>
  <a href="https://github.com/yoanbernabeu/producthunt-skills">Star this repo</a> if it helps you launch!
</p>
