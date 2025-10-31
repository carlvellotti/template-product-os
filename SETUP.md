# Product OS Setup Guide

**This file guides you (the AI) through setting up the user's Product OS for the first time.**

---

## Your Mission

You are conducting a guided setup interview to initialize the user's Product OS with their company context. This will take 5-10 minutes and create three core context files that power all future workflows.

Be conversational, friendly, and efficient. If they say "I don't know" to something, that's fine—just note it and move on.

---

## Setup Flow

### Step 1: Welcome and Explain

Say this (customize if needed):

"Welcome! I'm going to help you set up your Product OS. This will take about 5-10 minutes.

I'll ask you questions about:
1. Your product (what it does, who uses it)
2. Your strategy (goals, priorities, competitive landscape)
3. Your users (pain points, feedback, behavior patterns)

Your answers will be saved to context files that every future workflow can use. This means you'll never have to re-explain your company to me again.

Ready to start?"

**Wait for confirmation before proceeding.**

---

### Step 2: Product Overview Interview

Say: "Great! Let's start with your product."

Ask these questions **one section at a time** (don't dump them all at once):

**Basic Info:**
- "What's your product called and what does it do in one sentence?"
- "Who are your target customers? Any specific personas or segments?"

**Product Details:**
- "What are your core features or capabilities?"
- "What's your tech stack? (Just the main pieces - don't need exhaustive detail)"

**Metrics & Business:**
- "What are your current key metrics? Things like ARR, users, MRR, churn rate, NPS—whatever you track."
- "What's your pricing model?"

**Positioning:**
- "Who are your main competitors?"
- "What makes you different from them?"

**Listen to their answers. Ask natural follow-up questions if something is unclear or interesting.**

---

### Step 3: Strategy Interview

Say: "Perfect. Now let's talk about your current strategy and goals."

Ask these questions:

**Goals:**
- "What are your top 2-3 goals this quarter (or this year if quarterly isn't relevant)?"
- "What specific metrics are you trying to move?"

**Competitive & Market Context:**
- "What are the biggest competitive pressures or threats you're facing?"
- "Any major market shifts or opportunities you're responding to?"

**Priorities & Constraints:**
- "What are your strategic priorities right now? What are you saying 'yes' to?"
- "Any major resource constraints or limitations I should know about? (budget, team size, technical debt, etc.)"

**Listen to their answers.**

---

### Step 4: User Research Interview

Say: "Last section—tell me about your users and what you know about them."

Ask these questions:

**Pain Points:**
- "What are the biggest problems or pain points your users have? Can be problems with your product OR the broader problem you're solving."
- "Which pain points come up most frequently?"

**Feedback & Requests:**
- "What are users asking for most? Any repeated feature requests?"
- "Do you have recent user research, interviews, or feedback you can summarize?"

**Behavior Patterns:**
- "Any interesting patterns in how users actually use your product?"
- "What do power users do differently than casual users?"

**If they share specific quotes or stories, note them exactly as stated.**

---

### Step 5: Create Context Files

Say: "Awesome—thank you! I have everything I need. I'm creating your context files now..."

**Create these three files:**

#### 1. `context/product-overview.md`

Use this format:

```markdown
# Product Overview

## Product Description
[Product name and one-sentence description]

## Target Customers
[Customer segments, personas, key users]

## Core Features
- [Feature 1]
- [Feature 2]
- [Feature 3]
[etc.]

## Tech Stack
[Main technologies they mentioned]

## Current Metrics
- [Metric 1: value]
- [Metric 2: value]
- [etc.]

## Pricing Model
[How they charge]

## Competitive Landscape
**Main Competitors:** [List competitors]

**Differentiation:** [What makes this product different]
```

#### 2. `context/company-strategy.md`

Use this format:

```markdown
# Company Strategy

## Current Goals
**This Quarter/Year:**
- [Goal 1]
- [Goal 2]
- [Goal 3]

## Key Metrics to Move
- [Metric 1 and target]
- [Metric 2 and target]

## Competitive Pressures & Market Context
[Description of competitive threats, market shifts, opportunities]

## Strategic Priorities
**We are saying YES to:**
- [Priority 1]
- [Priority 2]

**We are saying NO to:**
- [Anti-priority 1 if mentioned]

## Constraints & Limitations
- [Resource constraint 1]
- [Resource constraint 2]
[Note: Only include if they mentioned specific constraints]
```

#### 3. `context/user-research.md`

Use this format:

```markdown
# User Research & Insights

## Top User Pain Points

### [Pain Point 1 - most frequent]
[Description]
[Quote if they provided one]

### [Pain Point 2]
[Description]

### [Pain Point 3]
[Description]

## Feature Requests
- [Request 1 - include frequency if known]
- [Request 2]
- [Request 3]

## Behavioral Patterns
[Patterns they described about how users actually use the product]

## Recent Research Insights
[Any recent user research they summarized]

[Note: If they said "I don't know" or didn't have much here, that's fine—just include what they shared]
```

**Important formatting rules:**
- Use clear headers and bullet points
- Include exact quotes when they shared specific user feedback
- Use their actual data/numbers, not placeholders
- If they didn't have info for a section, write "Not yet defined" or skip it
- Keep it factual and clear

---

### Step 6: Confirm Completion

After creating the files, say:

"Done! I've created three context files:

- `context/product-overview.md` - Your product details
- `context/company-strategy.md` - Your strategic goals and priorities
- `context/user-research.md` - User insights and pain points

Your Product OS now knows about YOUR company. These files are available for all future workflows—you'll never have to re-explain this context again.

You can update these files anytime as your company evolves. Just edit them directly or ask me to update them.

**What would you like to work on first?** Some ideas:
- Write a PRD for a new feature
- Synthesize user research
- Analyze product data
- Create a strategy doc

Or just ask me 'what can I do with my Product OS?' to see all the workflows available."

---

## Important Notes

### Conversation Style
- Be natural and conversational, not robotic
- Don't read the questions like a script—adapt them to the conversation flow
- If they go on a tangent that's relevant, that's great—capture it
- If something is unclear, ask follow-up questions
- If they say "I don't know," acknowledge it and move on

### Handling Missing Info
- It's totally fine if they don't have answers to everything
- Don't make up information or use placeholders
- Mark sections as "Not yet defined" if they don't have the information

### After Setup
- Once these three files exist, you don't need to run this setup again
- Users can manually edit these files or ask you to update them
- You can suggest updating context if you notice it seems outdated during future workflows

---

## That's It!

Your job is to make this feel easy and natural. After this setup, their Product OS will know their company and be ready for actual PM work.
