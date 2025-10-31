# Your Product OS Template

This is a blank template to build your own Product OS. It includes all the templates and frameworks you need—you just add your company context.

## What's Included

✅ **Templates**
- Lenny's PRD template for writing product requirements

✅ **Frameworks**
- Socratic questions for clarifying thinking
- Engineer perspective for technical review
- Executive perspective for business review
- UX perspective for user needs review

⚠️ **Empty Context Folders**
- You'll add YOUR company information here

## Quick Start

### 1. Clone this repo
```bash
git clone https://github.com/carlvellotti/template-product-os.git
cd template-product-os
```

### 2. Run the setup interview

Tell your CLI LLM:
```
Help me set up my Product OS using @SETUP.md
```

Your AI will interview you about:
- Your product (what it does, who uses it, metrics)
- Your strategy (goals, priorities, competitive landscape)
- Your users (pain points, feedback, behavior patterns)

This takes 5-10 minutes. It saves your answers to three context files in the `context/` folder.

Now your Product OS knows YOUR company.

### 3. Start using workflows

Once setup is complete, you can start using any workflow. For example, write a PRD:

```
Help me write a PRD for [your feature]

Use these files:
@context/product-overview.md
@context/company-strategy.md
@context/user-research.md
@templates/lennys-prd-template.md
@prompts/socratic-questions.md

Before writing, ask clarifying questions using the Socratic framework.
```

### 4. Evolving system

Every time you use it:
- New context gets added
- Templates get refined for your needs
- Prompts get customized to your style
- The system gets smarter

## Example Workflows

### Write a PRD

```
Help me write a PRD for [feature name]

Use these files:
@context/product-overview.md
@context/company-strategy.md
@context/user-research-[topic].md
@templates/lennys-prd-template.md
@prompts/socratic-questions.md

Before writing, ask clarifying questions using the Socratic framework.
```

After answering questions:

```
Based on my answers, write the PRD using the Lenny template.
Save it to outputs/[feature-name]-prd.md
```

Get multi-perspective feedback:

```
Review @outputs/[feature-name]-prd.md from three perspectives:
1. @prompts/engineer-perspective.md
2. @prompts/executive-perspective.md
3. @prompts/ux-perspective.md
```

### Synthesize User Research

```
I have interview transcripts in context/interviews/

Help me identify:
- Top pain points (with frequency)
- Key quotes for each pain point
- Patterns across interviews
- Actionable insights

Save the synthesis to outputs/research-synthesis.md
```

### Analyze Data

```
@data/funnel-metrics.csv

Help me understand:
- Where are users dropping off?
- Which cohorts are performing best?
- What patterns explain the differences?
```

## See It In Action

Want to see a working example first? Check out the demo with realistic company context:

https://github.com/carlvellotti/demo-product-os

## Tips for Success

1. **Start small** - Try one workflow, like writing a PRD
2. **Build context incrementally** - Add files as you need them
3. **Customize templates** - Adjust them to match your company's style
4. **Share workflows** - Once you build something good, share it with your team
5. **Keep evolving** - Your Product OS should grow with you

## What Makes This Powerful

This isn't just about AI writing things for you. The power comes from:

- **Persistent context** - Information is always available, not retyped every time
- **Better thinking** - Frameworks like Socratic questions sharpen your thinking before you write
- **Multi-perspective review** - Catch blindspots before sharing with your team
- **Compounding system** - Every workflow you build makes the next one easier

You bring the judgment and strategy. AI brings synthesis and diverse perspectives.

Together: better product work.

## Build Your Own Workflows

The workflows above are starting points. You can create workflows for:

- Strategy docs and vision statements
- Feature specs and technical requirements
- Launch plans and go-to-market documents
- User research synthesis
- Data analysis and A/B test interpretation
- Design feedback and critique
- Stakeholder communications

The same pattern works for all of them:
1. Load relevant context files
2. Use frameworks to guide thinking
3. Generate outputs
4. Get multi-perspective review

## Ready?

Start with one workflow. Add your company context. Watch it compound.

Keep building.
