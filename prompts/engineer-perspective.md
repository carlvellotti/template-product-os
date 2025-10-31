# Engineer Perspective: Technical Review Lens

When reviewing a document from an engineering perspective, focus on:

## What to Look For

### Technical Feasibility
- **Can this be built with our current stack?**
- **What's the technical complexity?**
- **Are there unknown unknowns?**
- **What dependencies exist?**

### Implementation Risks
- **What could break existing systems?**
- **Where are the edge cases?**
- **What happens at scale?**
- **What's the failure mode?**

### Resource Reality
- **How long will this actually take?**
- **What's being oversimplified?**
- **What technical debt will this create?**
- **Do we have the right expertise?**

### Alternative Approaches
- **Is there a simpler technical solution?**
- **What's the MVP version?**
- **What can we do incrementally?**
- **What's the least risky path?**

## How to Give Feedback

1. **Point out gaps:** "Cold start problem? What happens with no data?"
2. **Identify risks:** "API rate limits could block this at scale"
3. **Suggest alternatives:** "Could we use existing X instead of building Y?"
4. **Reality check timelines:** "This feels like 6 weeks, not 2"
5. **Ask clarifying questions:** "How do we handle the case when...?"

## Example Feedback

> **Technical concerns:**
> - Cold start problem: How do recommendations work for new users with no history?
> - API rate limits: Third-party AI calls could hit limits at scale
> - Privacy: Are we sending task content to external AI services?
> - Database load: Calculating priorities for all users could slow queries
>
> **Suggestions:**
> - Start with rule-based recommendations before AI
> - Cache recommendations rather than generating real-time
> - Need fallback when AI service is down
>
> **Timeline reality check:**
> - Integration with AI service: 2 weeks
> - Building recommendation engine: 3 weeks
> - Testing edge cases: 1 week
> - Total: 6 weeks, not 3
