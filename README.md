# Lenny PM Skills

**10 deep PM skills distilled from 303 episodes of Lenny's Podcast.**

Not another generic PM framework collection. Each skill is a curated masterclass built from real conversations with the best product minds -- Shreyas Doshi, Marty Cagan, Brian Balfour, Julie Zhuo, Gibson Biddle, and dozens more. Real quotes, real frameworks, real company stories.

## Quick Start

### As Claude Code Skills

```bash
# Clone the repo
git clone https://github.com/hpuri84/lenny-pm-skills.git

# Add to your Claude Code project
# In your CLAUDE.md or settings, add:
# skill-directory: /path/to/lenny-pm-skills/skills
```

Then invoke any skill:
```
/pm product-strategy
/pm prioritization
/pm finding-product-market-fit
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

### 2. Skill Definition (`skill.md`)
Interactive Claude Code skill that:
1. Asks your experience level (junior / mid / senior)
2. Understands what you're working on
3. Surfaces the most relevant frameworks from the knowledge base
4. Walks you through applying them to your situation
5. Generates a structured deliverable

### 3. Standalone Prompt (`prompt.md`)
Copy-paste prompt for any LLM, containing the same curated wisdom and guided workflow.

## Adapts to Your Level

- **Junior PMs (0-3 years):** Full framework explanations, guided step-by-step, foundational examples
- **Mid PMs (3-6 years):** Concise frameworks, focus on application and trade-offs
- **Senior PMs (6+ years):** Skip basics, nuanced insights, contrarian perspectives, edge cases

## Source Material

All wisdom is extracted from [Lenny's Podcast transcripts](https://github.com/ChatPRD/lennys-podcast-transcripts) -- 303 episodes featuring guests from companies like Airbnb, Stripe, Meta, Netflix, Figma, Notion, Slack, and many more.

Every framework and quote is attributed to the original guest and episode.

## Contributing

Found a great insight in a Lenny's episode that's missing? PRs welcome. Each skill's `knowledge.md` is the place to add new frameworks, quotes, and examples.

## License

MIT
