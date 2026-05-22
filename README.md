# Ad Angle Generator — Research-to-Angles Meta Ads Skill

**Generate 25+ research-backed ad angles for any product through a structured 8-step pipeline.**

Give Claude a brand or product name and it runs the full research chain — brand research across the internet, competitive SWOT analysis, target audience definition, customer persona development, pain point extraction, USP identification, framework selection — and generates ad angles that are traceable back to real data.

## Install

**Claude Desktop (Cowork):** download [`ad-angle-generator.skill`](https://github.com/the-baweja/ad-angle-generator/releases/latest) → Settings → Skills → drop it in.

**Claude Code:**
```
git clone https://github.com/the-baweja/ad-angle-generator.git ~/.claude/skills/ad-angle-generator
```

**Manual:** clone this repo into any skills directory your Claude setup reads from.

## What it does

You give it a brand or product. It runs the **Angle Chain Method** — 8 sequential steps where each step feeds the next:

1. **Brand Research** — searches the internet, reviews, Reddit, social media, and Meta Ad Library for everything about the brand
2. **Competitive Analysis** — identifies 3-5 competitors and maps strengths, weaknesses, and advertising gaps
3. **Target Audience Definition** — builds a demographic, psychographic, and behavioral profile of the buyer
4. **Customer Persona Development** — creates 1-2 specific, named personas from real customer data
5. **Pain Point Extraction** — ranks 10-15 pain points mapped to personas, in real customer language
6. **USP Identification** — connects 5-8 USPs to the pain points they solve and competitive advantages they represent
7. **Framework Selection** — weights 9 ad frameworks by relevance to this specific product
8. **Angle Generation** — produces 25-30 ad angles, each with hook, body concept, format, funnel stage, persona, and a "why it works" tied to the research chain

## Output

A branded DOCX report with:

- Brand research summary with Ad Library stats
- Competitive landscape map
- Target audience and customer personas
- Ranked pain points in real customer language
- USP map connecting features to pain points
- 25-30 ad angles organized by framework
- Top 5 priority recommendations
- 8-week testing roadmap

## Customize Your Branding

Edit `references/branding.md` with your own brand colors, typography, and document structure. The skill reads this file to generate reports that match your brand identity.

## Example

Prompt:
```
Generate ad angles for PDPAOLA.
They're a Barcelona-based jewelry brand selling in 70+ countries.
Focus on their demi-fine positioning — luxury look at accessible prices.
```

Output: 8-step research chain completed, 27 ad angles generated across 9 frameworks — each traced to a specific pain point, persona, and competitive gap.

## Who this is for

Media buyers, creative strategists, brand owners, and performance marketers who want ad angles grounded in research instead of guesswork.

This is skill 2 of 10 in the **AI Skills for Media Buyers** series by [Baweja Media](https://bawejamedia.com).

---

## Want Baweja Media to audit your ad account and explore opportunities to work together?

[→ Book a strategy call](https://webinar.sannidhyabaweja.com/vsl-lp-ind)

---

Built by [Baweja Media](https://bawejamedia.com) · MIT License
