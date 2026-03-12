# Lenny PM Skills

**10 deep PM skills distilled from 303 episodes of Lenny's Podcast.**

Not another generic PM framework collection. Each skill is a curated masterclass built from real conversations with the best product minds -- Shreyas Doshi, Marty Cagan, Brian Balfour, Julie Zhuo, Gibson Biddle, and dozens more. Real quotes, real frameworks, real company stories.

## Quick Start

### As Claude Code Skills (Recommended)

Install any skill directly from the packaged `.skill` files:

```bash
# Clone the repo
git clone https://github.com/harshpuri84/lenny-pm-skills.git
cd lenny-pm-skills

# Install individual skills
claude skill install dist/product-strategy.skill
claude skill install dist/prioritization.skill
claude skill install dist/finding-product-market-fit.skill
# ... or install all 10:
for f in dist/*.skill; do claude skill install "$f"; done
```

Then just describe what you need -- skills trigger automatically:
```
"I need to define our product strategy for Q2"
"Help me prioritize this feature backlog"
"We're not sure if we have product-market fit"
```

### As Standalone Prompts

Don't use Claude Code? Each skill ships as a standalone prompt you can copy-paste into any LLM. Browse the [`prompts/`](prompts/) directory.

## The Skills

| Skill | What It Does | Key Guests | Artifact |
|-------|-------------|------------|----------|
| [`product-strategy`](skills/product-strategy/) | Craft a product strategy using battle-tested frameworks | Shreyas Doshi, Gibson Biddle, Marty Cagan | 1-page strategy doc |
| [`finding-product-market-fit`](skills/finding-product-market-fit/) | Assess and find product-market fit systematically | Mike Maples Jr, Casey Winters, Dalton Caldwell | PMF assessment scorecard |
| [`growth-frameworks`](skills/growth-frameworks/) | Build growth models and identify your best growth levers | Brian Balfour, Casey Winters, Sean Ellis | Growth model + channel plan |
| [`prioritization`](skills/prioritization/) | Prioritize ruthlessly using proven decision frameworks | Shreyas Doshi, Brandon Chu, Shishir Mehrotra | Prioritized backlog with reasoning |
| [`experimentation`](skills/experimentation/) | Design and run high-quality experiments | Ronny Kohavi, Gibson Biddle, Ramesh Johari | Experiment design doc |
| [`user-research`](skills/user-research/) | Run effective customer discovery and research | Bob Moesta, Lane Shackleton, Teresa Torres | Research plan + interview guide |
| [`retention-and-engagement`](skills/retention-and-engagement/) | Diagnose and fix retention problems | Gibson Biddle, Naomi Gleit, Patrick Campbell | Retention analysis + action plan |
| [`storytelling-and-influence`](skills/storytelling-and-influence/) | Communicate product vision and influence stakeholders | Nancy Duarte, Andy Raskin, Wes Kao | Narrative memo or pitch outline |
| [`team-and-hiring`](skills/team-and-hiring/) | Build and scale high-performing product teams | Gokul Rajaram, Emily Kramer, Claire Hughes Johnson | Hiring scorecard or team plan |
| [`pm-career-growth`](skills/pm-career-growth/) | Navigate your PM career from IC to leadership | Jackie Bavaro, Ravi Mehta, Julie Zhuo | Career growth plan |

## How It Works

Each skill has three layers:

### 1. Knowledge Base (`knowledge.md`)
Curated wisdom extracted from real podcast episodes:
- Named frameworks attributed to specific guests
- Direct quotes with episode references
- Common mistakes guests warn against
- Real company stories (Airbnb, Slack, Instagram, Netflix, etc.)

### 2. Skill Definition (`SKILL.md`)
Interactive Claude Code skill that:
1. Understands what you're working on
2. Surfaces the most relevant frameworks from the knowledge base
3. Walks you through applying them to your situation
4. Challenges your assumptions with hard questions
5. Generates a structured deliverable

### 3. Standalone Prompt (`prompt.md`)
Copy-paste prompt for any LLM, containing the same curated wisdom and guided workflow.

## Built for Senior PMs

Every skill skips the basics and targets experienced practitioners: contrarian insights, edge cases, challenging questions, and nuanced trade-offs. When a skill pushes back on your assumptions, that's by design.

## Source Material

All wisdom is extracted from [Lenny's Podcast transcripts](https://github.com/ChatPRD/lennys-podcast-transcripts) -- 303 episodes featuring guests from companies like Airbnb, Stripe, Meta, Netflix, Figma, Notion, Slack, and many more.

Every framework and quote is attributed to the original guest and episode.

## Contributing

Found a great insight in a Lenny's episode that's missing? PRs welcome. Each skill's `knowledge.md` is the place to add new frameworks, quotes, and examples.

## License

MIT
