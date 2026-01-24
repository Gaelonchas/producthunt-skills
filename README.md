# Product Hunt Launch Skills

A comprehensive collection of **31 AI agent skills** for launching products on Product Hunt. Expert guidance for every phase of your launch - from strategic planning to post-launch optimization.

## Installation

### Method 1: npx add-skill (Recommended)

Works with Claude Code, Cursor, Codex, OpenCode, and 20+ other agents:

```bash
# Install all skills
npx add-skill yoanbernabeu/producthunt-skills

# Install specific skill
npx add-skill yoanbernabeu/producthunt-skills --skill ph-launch-strategy

# Install globally
npx add-skill yoanbernabeu/producthunt-skills --global

# List available skills
npx add-skill yoanbernabeu/producthunt-skills --list
```

### Method 2: npx skills add (Vercel CLI)

```bash
npx skills add yoanbernabeu/producthunt-skills
```

### Method 3: Claude Code Plugin

```bash
/plugin marketplace add yoanbernabeu/producthunt-skills
/plugin install ph-complete@producthunt-launch-skills
```

### Method 4: Manual Installation

Copy the `skills/` directory to:
- **Global**: `~/.claude/skills/` (or `~/.cursor/skills/`, etc.)
- **Project**: `.claude/skills/` (or `.cursor/skills/`, etc.)

## Supported AI Agents

| Agent | Project Path | Global Path |
|-------|-------------|-------------|
| Claude Code | `.claude/skills/` | `~/.claude/skills/` |
| Cursor | `.cursor/skills/` | `~/.cursor/skills/` |
| Codex | `.codex/skills/` | `~/.codex/skills/` |
| OpenCode | `.opencode/skill/` | `~/.config/opencode/skill/` |
| Windsurf | `.windsurf/skills/` | `~/.windsurf/skills/` |

## Available Skill Packs

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
| **`ph-complete`** | **31** | **All skills - complete launch toolkit** |

## All 31 Skills

### Strategy & Planning
| Skill | Description |
|-------|-------------|
| `ph-launch-strategy` | Define objectives, create 4-6 week timeline |
| `ph-competitor-analysis` | Analyze competing launches, benchmark top performers |
| `ph-timing-optimizer` | Choose optimal day/time for your goals |

### Content Creation
| Skill | Description |
|-------|-------------|
| `ph-tagline-writer` | Craft compelling taglines under 60 characters |
| `ph-description-writer` | Write converting product descriptions (AIDA, PAS, FAB) |
| `ph-maker-comment` | Create authentic first comments |
| `ph-thumbnail-creator` | Design scroll-stopping thumbnails and GIFs |
| `ph-gallery-assets` | Build compelling image galleries |
| `ph-video-demo` | Script and structure demo videos (30-60s) |

### Marketing & Outreach
| Skill | Description |
|-------|-------------|
| `ph-email-strategy` | Plan email waves across timezones |
| `ph-social-media-launch` | Coordinate Twitter/LinkedIn/Facebook |
| `ph-community-outreach` | Engage Reddit, Indie Hackers, HN |
| `ph-supporter-network` | Build and activate your network |

### Launch Day
| Skill | Description |
|-------|-------------|
| `ph-launch-day-checklist` | Hour-by-hour execution plan |
| `ph-comment-responder` | Respond effectively to comments (< 9 min) |
| `ph-real-time-monitor` | Track and adjust in real-time |

### Compliance & Risk
| Skill | Description |
|-------|-------------|
| `ph-ban-prevention` | Avoid shadow bans and penalties |
| `ph-algorithm-guide` | Understand ranking factors |
| `ph-safe-messaging` | Use approved language patterns |

### Hunters & Profile
| Skill | Description |
|-------|-------------|
| `ph-hunter-finder` | Find and approach top hunters |
| `ph-profile-optimizer` | Build maker reputation |

### Pricing & Offers
| Skill | Description |
|-------|-------------|
| `ph-launch-offers` | Create exclusive PH deals |
| `ph-pricing-psychology` | Leverage FOMO and urgency |

### Analytics
| Skill | Description |
|-------|-------------|
| `ph-analytics-setup` | Configure tracking tools |
| `ph-conversion-tracking` | Measure launch performance and ROI |

### Post-Launch
| Skill | Description |
|-------|-------------|
| `ph-post-launch-followup` | Thank supporters, collect reviews |
| `ph-content-recycling` | Repurpose launch assets |
| `ph-relaunch-strategy` | Plan your next launch (v2.0) |
| `ph-seo-benefits` | Maximize SEO value from PH backlink |

### Awards & Features
| Skill | Description |
|-------|-------------|
| `ph-newsletter-pitch` | Get featured in PH newsletter |
| `ph-golden-kitty` | Strategy for Golden Kitty Awards |

## Quick Start

1. **Install skills**: `npx add-skill yoanbernabeu/producthunt-skills`
2. **Plan**: Start with `ph-launch-strategy` to define goals
3. **Time**: Use `ph-timing-optimizer` to pick launch date
4. **Create**: Work through content skills for assets
5. **Launch**: Execute with `ph-launch-day-checklist`
6. **Optimize**: Follow up with post-launch skills

## Key Product Hunt Rules

| Rule | Why It Matters |
|------|---------------|
| **Never ask for upvotes** | Ask for "support" or "feedback" instead - violating this can get you banned |
| **Launch at 12:01 AM PST** | Maximize your 24-hour window |
| **First 4 hours are critical** | Algorithm weights early momentum heavily |
| **Respond to every comment** | Engagement depth boosts ranking |
| **Stagger your outreach** | All-at-once looks spammy to algorithm |

## Example Usage

Ask your AI agent:

```
"Help me prepare for my Product Hunt launch using the ph-launch-strategy skill"

"Write a tagline for my product using ph-tagline-writer"

"Create a launch day checklist using ph-launch-day-checklist"

"Review my email for compliance using ph-safe-messaging"
```

## Resources

- [Product Hunt Help Center](https://help.producthunt.com)
- [Product Hunt Launch Guide](https://www.producthunt.com/launch)
- [Community Guidelines](https://help.producthunt.com/en/articles/3615694-community-guidelines)
- [add-skill CLI Documentation](https://add-skill.org)

## Contributing

Contributions welcome! Please:
1. Fork the repository
2. Create a feature branch
3. Follow the SKILL.md format
4. Submit a pull request

## License

MIT License - Feel free to use, modify, and distribute.

---

Star ⭐ this repo if it helps you launch!
