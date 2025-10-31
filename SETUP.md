# Setup Instructions for AI

**This file is for Claude (or any CLI LLM) to read when the user first tries to use the Product OS.**

---

## When the User Tries the PRD Workflow

If the user runs the PRD workflow command but the context files are missing, follow these steps:

### Step 1: Notice Missing Context

Check if these files exist in the `context/` folder:
- `product-overview.md`
- `company-strategy.md`
- `user-research.md`

If they're missing or empty, say:

"I notice you don't have company context files yet. Let me interview you quickly to create them. This will take about 5-10 minutes, and then your Product OS will know about YOUR company for all future workflows.

Ready to start?"

Wait for confirmation.

### Step 2: Interview About Product

Say: "First, tell me about your product:
- What's it called and what does it do?
- Who are your target customers?
- What are your key features?
- What's your tech stack?
- What are your current metrics (ARR, users, churn, NPS, etc.)?
- What's your pricing model?"

Listen to their answers. Ask follow-up questions if needed for clarity.

### Step 3: Interview About Strategy

Say: "Now tell me about your current strategy:
- What are your top goals for this quarter?
- What metrics are you trying to move?
- Who are your main competitors?
- What market pressures are you facing?
- What are your strategic priorities right now?"

Listen to their answers.

### Step 4: Interview About Users

Say: "Finally, tell me what you know about your users:
- What are their biggest problems or pain points?
- What features are they requesting most?
- Do you have any recent user research or feedback?
- What patterns do you see in user behavior?"

Listen to their answers.

### Step 5: Create Context Files

Say: "Perfect! I'm creating your company context files now..."

**Action:** Create three files in the `context/` folder:

1. **`context/product-overview.md`** - Include:
   - Product name and description
   - Target customers
   - Core features
   - Tech stack
   - Current metrics
   - Pricing model
   - Competitive positioning

2. **`context/company-strategy.md`** - Include:
   - Current goals and priorities
   - Metrics they're trying to move
   - Competitive landscape
   - Market pressures
   - Strategic priorities
   - Investment capacity/constraints

3. **`context/user-research.md`** - Include:
   - User pain points
   - Feature requests
   - Recent research insights
   - User behavior patterns
   - Key quotes (if they shared any)

### Step 6: Confirm and Continue

Say: "Done! I've created three context files:
- `context/product-overview.md` - Your product details
- `context/company-strategy.md` - Your strategic goals
- `context/user-research.md` - User insights

Your Product OS now knows about YOUR company. These files will be available for all future workflows.

Now let's continue with your PRD. I'll load all this context plus the PRD template and Socratic questions framework..."

Then proceed with the normal PRD workflow, loading:
- `@context/product-overview.md`
- `@context/company-strategy.md`
- `@context/user-research.md`
- `@templates/lennys-prd-template.md`
- `@prompts/socratic-questions.md`

---

## Important Notes

- Be conversational and friendly during the interview
- If the user says "I don't know" to something, that's fine—just note it and move on
- Format the context files clearly with headers and bullet points
- Use exact quotes when the user shares specific user feedback
- The goal is to make their Product OS immediately useful with their real company information

---

## For Subsequent Uses

Once the context files exist, you DON'T need to interview them again. Just load the files normally.

Users can update these files anytime as their company evolves. You might occasionally say something like: "By the way, if your strategy or goals have changed, feel free to update the context files."
