# Key Learnings

## 1. Sonnet Is the Default Choice

The biggest takeaway is that **Claude Sonnet should be the starting point for almost every task**.

Why:
- Best balance of speed and quality
- Strong coding capabilities
- Good research synthesis
- Excellent explanations
- Handles most student and professional work

**Rule:**
> Start with Sonnet unless you have a specific reason not to.

---

## 2. Effort Level Matters More Than Most People Think

Many users focus on choosing the right model but ignore the effort setting.

A difficult task on:
- Sonnet + Standard

may perform worse than:

- Sonnet + High

for debugging, analysis, and research.

**Rule:**
> Upgrade effort before upgrading models.

---

## 3. Haiku Is a Utility Tool, Not a Thinking Tool

Haiku excels at:
- Fast answers
- Definitions
- Syntax questions
- Flashcards
- Summaries

It is not intended for:
- Deep reasoning
- Architecture decisions
- Complex debugging
- Research synthesis

**Rule:**
> Use Haiku when speed matters more than depth.

---

## 4. Opus Should Be Reserved for High-Stakes Work

Opus provides the deepest reasoning but comes with higher usage costs.

Best used for:
- Thesis work
- Dissertation research
- Algorithm design
- Multi-source synthesis
- System design reviews

**Rule:**
> Use Opus only when the quality gain justifies the additional resources.

---

## 5. Better Questions Produce Better Answers

The quality of Claude's output is heavily dependent on the quality of the input.

Weak prompt:
```text
Fix my code.
```

Strong prompt:
```text
Here is my code.
Expected output: X
Actual output: Y
Error message: Z
```

**Rule:**
> Context is one of the highest-leverage improvements available.

---

## 6. Iteration Beats One-Shot Prompting

The first response should rarely be considered the final response.

Improve outcomes by asking:
- Why?
- What assumptions were made?
- What are the alternatives?
- What are the trade-offs?

**Rule:**
> Treat Claude like a collaborator, not a search engine.

---

## 7. Model Selection Should Follow Task Complexity

### Simple Tasks
- Haiku + Low

Examples:
- Syntax checks
- Definitions
- Quick summaries

### Standard Tasks
- Sonnet + Standard

Examples:
- Learning
- Coding
- Assignments
- Research summaries

### Difficult Tasks
- Sonnet + High

Examples:
- Debugging
- Architecture
- Paper analysis
- Root-cause investigations

### Critical Tasks
- Opus + High/Max

Examples:
- Thesis work
- Advanced research
- Algorithm design

---

## 8. Resource Efficiency Matters

Using the most powerful model for every task is inefficient.

Many users waste:
- Time
- Rate limits
- Resources

by defaulting to Opus.

A smarter workflow is:

```text
Haiku → Quick tasks
Sonnet → Daily work
Opus → High-stakes work
```

---

## 9. Escalation Strategy Is More Important Than Initial Choice

Instead of trying to pick the perfect configuration immediately:

1. Start with Sonnet + Standard
2. Upgrade to Sonnet + High if needed
3. Move to Opus only when deeper reasoning is required

This creates the best balance of:
- Quality
- Speed
- Cost
- Availability

---

## 10. The Recommended Workflow

```text
Quick Question?
    ↓
Haiku + Low

Daily Work?
    ↓
Sonnet + Standard

Stuck?
    ↓
Sonnet + High

High-Stakes Research?
    ↓
Opus + High

Thesis / Dissertation?
    ↓
Opus + Max
```

---

# Core Philosophy

The most effective Claude workflow is not:

```text
Always use the strongest model.
```

It is:

```text
Use the simplest model and effort level
that can reliably solve the task,
then scale upward only when necessary.
```

This maximizes:
- Productivity
- Response speed
- Resource efficiency
- Overall output quality