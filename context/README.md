# Context Folder

This folder holds your company's persistent context—the information that should be available for every Product OS workflow.

## What to Put Here

Create markdown files for:

### 1. Product Overview (`product-overview.md`)
What your product does and who uses it:
- What problem does your product solve?
- Core features and capabilities
- Target users and personas
- Competitive positioning
- Current metrics (users, revenue, growth)
- Pricing tiers

### 2. Company Strategy (`company-strategy.md`)
Your current strategic goals and priorities:
- Quarterly or annual goals
- Key metrics you're trying to move
- Competitive threats and opportunities
- Resource constraints
- Strategic bets you're making

### 3. User Research
Files containing user interview insights, pain points, and quotes:
- `user-research-[topic].md` for specific research studies
- Pain points organized by frequency
- Direct user quotes
- Behavioral observations
- Feature requests and feedback

### 4. Other Context (Optional)
- Technical architecture and constraints
- Brand guidelines and voice
- Team structure and responsibilities
- Roadmap and past decisions

## How to Get Started

**Option 1: Run the setup interview (recommended)**

Tell your CLI LLM:
```
Help me set up my Product OS using @SETUP.md
```

Your AI will interview you about your product, strategy, and users (5-10 minutes). It will create the three core context files for you.

**Option 2: Create them yourself**

Copy existing docs you have:
- Company all-hands slides → `company-strategy.md`
- Product marketing pages → `product-overview.md`
- User research docs → `user-research-[topic].md`

Or just create them manually following the structure shown above.

## Tips

- Keep files focused (one topic per file)
- Update them as things change
- Use clear, factual language
- Include specific examples and data
- Link to source materials when relevant

The better your context files, the better your Product OS becomes.
