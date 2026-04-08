# GMB Skill — Google Business Profile Specialist for Claude Code

Complete Google Business Profile (GBP / GMB) skill for Claude Code. Covers the full lifecycle of any local business profile — from setup to 10/10 optimization.

## What It Does

16 modules covering every aspect of GBP management:

| Module | Description |
|--------|-------------|
| Profile Foundation | Business name, address, phone, hours, attributes |
| Description & Categories | Keyword-optimized descriptions, primary + secondary categories |
| Photos & Videos | Visual strategy, specs, geo-tagging, upload frequency |
| Google Posts | All post types + monthly content calendars |
| Products & Services | Catalog, menu, service listings |
| Q&A | Question seeding strategy (feeds AI Overviews) |
| Reviews | Response templates, generation strategy, fake review handling |
| Messaging | GBP chat setup, quick reply templates |
| Booking & Appointments | Reserve with Google, external booking links |
| Citations & NAP | Directory listings by market/country, consistency audit |
| Insights & Metrics | KPIs, monthly reporting structure |
| AI Overviews 2026 | Optimization for Google AI search answers |
| Competitor Analysis | Reverse-engineering top-ranked profiles |
| Full Audit | 0-100 scored audit with prioritized action plan |
| Suspension & Recovery | Diagnosis, evidence collection, reinstatement |
| Multi-location & Agency | Multiple clients and locations management |

## Reference Files

- `references/audit-scoring-guide.md` — 100-point scoring rubric (5 blocks, 14 criteria)
- `references/post-calendar-templates.md` — Seasonal calendars and post templates by niche
- `references/review-templates.md` — Response templates by industry and review type

## Installation

Copy the `gmb` folder into your Claude Code skills directory:

```bash
cp -r gmb /path/to/your/skills/
```

Or if using a skills repository:

```bash
git clone https://github.com/heliodcf/gmb-skill.git skills/gmb
```

## Features

- Works for **any country, language, or business type** — responds in the user's language
- **Scored audits** with objective 100-point rubric
- **Copy-paste ready** outputs for posts, review responses, descriptions
- **Agency mode** for managing multiple clients
- Optimized for **AI Overviews 2026** and local E-E-A-T signals

## Usage Examples

```
# Run a full audit
"Audit my Google Business Profile for [Business Name] in [City]"

# Create a monthly content calendar
"Create a GBP post calendar for a dental clinic in Miami for June"

# Respond to reviews
"Write responses for these 5 Google reviews: [paste reviews]"

# Optimize profile
"Optimize my GBP description and categories for a stone countertop showroom in Pompano Beach, FL"
```

## License

MIT
