# The AI Founder's Playbook

## How to Launch a Product in a Weekend Using Claude Code

*By Matt Warren — founder, engineer, AI-first operator*

---

## Why This Playbook Exists

I run a CPG brand. I build software products. I do my own marketing. And for the past year, I've been doing all of it with AI.

Not the "ask ChatGPT to write a blog post" kind of AI. The kind where Claude Code is my co-founder for every sprint. Where a weekend of focused work replaces what used to take a team three weeks.

This playbook walks you through exactly how I'd launch a product from scratch in 48 hours using 24 open-source AI skills I built and use daily. Not theory. Not prompts. The actual workflow.

Here's the deal: the skills are free and open-source on GitHub. But knowing *how to chain them together* — that's what separates a founder who plays with AI from a founder who ships with AI.

Let's go.

---

## What You Need Before You Start

- **Claude Code** installed (or Cursor/Windsurf — the skills work with all of them)
- **The skills repo** installed: `npx skills add mfwarren/entrepreneur-claude-skills`
- **A product idea** — even a rough one. We'll sharpen it in Chapter 1.
- **A domain and hosting** — for the landing page (or use Carrd/Framer if you want to move fast)
- **An email provider** — Beehiiv, ConvertKit, or whatever you use
- **48 hours** of focused time

---

## Chapter 1: Friday Night — Validate the Idea

**Skills used:** market-research, competitive-analysis

**Time: 2 hours**

Most founders skip validation because it feels like busywork. "I'll just build it and see." That's a recipe for building something nobody wants.

With AI, validation doesn't have to be slow. Here's the move:

### Step 1: Market Research (45 minutes)

Open Claude Code and tell it:

> "I want to launch [your product idea]. Run the market-research skill. Here's what I know: [dump everything you know about the market, the customer, the problem]."

The market-research skill will walk you through:
- Defining the research question (what decision are you actually making?)
- TAM/SAM/SOM sizing — you'll get a funnel from total market down to your realistic capture
- Building an Ideal Customer Profile (ICP) with demographics, pain points, buying triggers, and objections
- Identifying where your customers hang out online

**What you're looking for:** Is this market big enough to be worth your time? Do you understand who the buyer is and what they care about?

### Step 2: Competitive Landscape (45 minutes)

Now tell Claude Code:

> "Run the competitive-analysis skill for [your product] against these competitors: [list 3-5 you know about]."

You'll get:
- A per-competitor breakdown of what they offer, how they price, and where they're weak
- A SWOT analysis for your position
- A positioning map showing where white space exists
- A differentiation strategy based on real gaps

**What you're looking for:** Is there a gap you can own? Are you different enough to matter?

### Step 3: Go/No-Go Decision (30 minutes)

After these two sessions, you have enough to decide:
- Is the market real and reachable?
- Is there a gap in the competitive landscape?
- Do you have a clear ICP?

If yes — you're building this weekend. If no — you just saved yourself weeks of wasted effort.

---

## Chapter 2: Saturday Morning — Build the Offer

**Skills used:** offer-creation, pricing-strategy

**Time: 3 hours**

You don't sell a product. You sell an offer. The difference: a product is what you make. An offer is the irresistible package that makes buying feel obvious.

### Step 1: The Value Equation (1 hour)

Tell Claude Code:

> "Run the offer-creation skill. Here's my product: [description]. My customer's dream outcome is: [what they really want]. Their biggest fear about buying is: [objection]."

The skill applies the Hormozi value equation:

```
Value = (Dream Outcome x Likelihood of Achievement) /
        (Time Delay x Effort Required)
```

You'll work through all four levers to maximize perceived value. The output is a structured value stack — your core offer plus bonuses that make the price feel like a steal.

### Step 2: Price It (1 hour)

> "Run the pricing-strategy skill. Here's my value stack: [paste from previous step]. My competitors charge: [range]. My target customer's budget is: [estimate]."

You'll get:
- A recommended pricing model (value-based vs. tiered vs. usage)
- A 3-tier structure (if applicable) with psychology tactics
- Specific pricing recommendations with rationale

### Step 3: Name and Package (1 hour)

The offer-creation skill also produces a name and one-pager. By the end of this session you should have:
- An offer name that communicates the outcome
- A complete value stack with prices
- A guarantee that addresses the #1 objection
- A one-pager you can hand to anyone and they understand what you're selling

---

## Chapter 3: Saturday Afternoon — Ship the Landing Page

**Skills used:** landing-pages, copywriting

**Time: 3 hours**

This is where most people stall. "I need to design it." "I need to find the right template." "I need to write the copy." With the right skills loaded, Claude Code does all of this in one session.

### Step 1: Page Structure (30 minutes)

> "Run the landing-pages skill. Here's my offer: [paste the one-pager from Chapter 2]. Traffic will come from [paid ads / social / organic]. The goal is [signups / purchases / demos]."

You'll get a complete wireframe:
1. Hero (headline + subheadline + CTA)
2. Problem section
3. Solution section
4. Social proof
5. How it works (3 steps)
6. Features/benefits
7. Pricing
8. FAQ (addresses your top objections)
9. Final CTA
10. Guarantee

### Step 2: Write the Copy (1.5 hours)

> "Run the copywriting skill for this landing page. Use PAS framework. Here are my proof points: [testimonials, stats, credentials]. Tone should be: [casual/professional/urgent]."

The copywriting skill produces:
- 3 headline variants (direct, story-driven, contrarian)
- Full copy for every section
- 3 CTA variants
- All written at a 6th-grade reading level with short paragraphs and benefit-led language

### Step 3: Build and Ship (1 hour)

Take the structured output and drop it into your page builder. Since every section is written and structured, this is assembly — not creation.

If you're using WordPress, ask Claude Code to convert the copy into Gutenberg blocks. If you're using Carrd, Framer, or Webflow — the section-by-section format maps directly to components.

**Ship it. Don't perfect it.** You can optimize after launch. A live page that's 80% perfect beats a draft that's 100% perfect.

---

## Chapter 4: Saturday Evening — Wire the Email System

**Skills used:** email-campaigns, cold-outreach

**Time: 2 hours**

Two email systems to build: one for people who sign up (welcome sequence) and one for people you want to reach directly (cold outreach).

### Step 1: Welcome Sequence (1 hour)

> "Run the email-campaigns skill. Type: welcome sequence. Product: [your offer]. Goal: [purchase / activation / engagement]. Write 5 emails."

You'll get:
- 5 emails with subject lines, preview text, body copy, and CTAs
- Timing recommendations (Day 0, Day 1, Day 3, Day 5, Day 7)
- Each email has a single focus and single CTA
- Segmentation suggestions based on behavior

Load these into Beehiiv (or your ESP) as an automation. This runs forever once it's set up.

### Step 2: Cold Outreach (1 hour, optional)

If you have a list of target prospects:

> "Run the cold-outreach skill. I'm reaching [title] at [company type]. The pain I solve: [problem]. Proof: [result I've achieved]. Write a 4-email sequence."

You'll get:
- 4 emails: Opener, Value Add, Case Study, Breakup
- 5 subject line variants per email
- All under 100 words (cold emails should be short)
- LinkedIn DM variants (if relevant)

---

## Chapter 5: Sunday — Launch

**Skills used:** social-media, paid-ads

**Time: 4 hours**

Launch day. You've validated the idea, built the offer, shipped the page, and wired the emails. Now you need eyeballs.

### Step 1: Organic Social (2 hours)

> "Run the social-media skill. I'm launching [product] today. Key selling point: [hook]. Target audience: [ICP]. Create content for Twitter/X and LinkedIn."

For each platform you'll get 3 variants:
- Direct/educational
- Story-driven/personal
- Contrarian/provocative

Post the strongest variant on each platform. Save the others for the next 2-3 days.

**Twitter tip:** The thread format works best for launches. Hook tweet → problem → solution → what's included → CTA with link.

**LinkedIn tip:** Open with one counterintuitive line that stops the scroll. Keep paragraphs to 1-2 sentences. Ask a question at the end.

### Step 2: Paid Ads (2 hours, optional)

If you have ad budget:

> "Run the paid-ads skill. Platform: Meta. Objective: conversions. Product: [your offer]. Target: [audience]. Landing page: [URL]. Write 5 ad variants."

You'll get:
- 5 primary text variants for A/B testing
- Headline and description options
- A creative brief you can hand to a designer (or use for AI image generation)
- A test matrix telling you what to test first

Start with $20-50/day on 3 variants. Kill losers after 48 hours. Scale winners.

---

## Chapter 6: Monday — Measure and Decide

**Skills used:** unit-economics, decision-frameworks

**Time: 1 hour**

You've got data now. Time to figure out what's working.

### Step 1: Run the Numbers (30 minutes)

> "Run the unit-economics skill. Here's what I know: [spend, signups, conversion rate, revenue, COGS]. Business model: [type]."

You'll get:
- CAC, LTV, LTV:CAC ratio
- Payback period
- Contribution margin
- Scenario analysis ("if you improve X by Y%, here's the impact")
- Clear verdict: healthy, needs work, or unsustainable

### Step 2: Decide What's Next (30 minutes)

> "Run the decision-frameworks skill. Here's my situation: [describe where you are and what options you're considering]."

The skill will classify your decision (Type 1 or Type 2), apply the right framework, and give you a recommendation with confidence level.

Common post-launch decisions:
- Double down on paid ads vs. go organic
- Keep current offer vs. pivot positioning
- Add features vs. focus on distribution
- Keep building vs. shelve and move on

---

## The Bigger Picture

What you just did in a weekend used to require:
- A marketing consultant ($5-10K)
- A copywriter ($2-5K)
- A web designer ($3-8K)
- 3-4 weeks of calendar time

You did it in 48 hours with AI skills that are free and open-source.

This isn't about replacing people. It's about moving fast enough to test ideas before committing serious resources. The ideas that survive the weekend test are the ones worth investing in.

The 24 skills in this marketplace are just the start. I'm adding new ones regularly — sign up for updates and I'll let you know when new skills drop, plus share the workflows I'm using in my own business.

---

## Get the Skills

**GitHub:** github.com/mfwarren/entrepreneur-claude-skills

**Install:**
```bash
npx skills add mfwarren/entrepreneur-claude-skills
```

**Follow for updates:**
mattwarren.co/newsletter

---

*Built by Matt Warren — founder of Psychedelic Water, engineer, and the kind of person who builds his own tools because it's faster than waiting.*
