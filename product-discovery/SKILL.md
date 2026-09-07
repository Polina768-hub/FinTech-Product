---

name: product-discovery
description: A structured approach for understanding users, identifying meaningful problems, validating opportunities, and deciding what is worth building. Use when exploring a new product opportunity, validating a problem, defining a target user, conducting user interviews, or deciding whether a proposed solution is worth building.
category: product-management
domain: product-discovery
tags:

* product-management
* user-research
* problem-discovery
* opportunity-validation
* product-strategy
* user-interviews

---

# Product Discovery

A structured process for reducing uncertainty before investing significant time and resources into building a product or feature.

Product Discovery helps answer:

> Who has the problem?

> What problem are they actually experiencing?

> How important is the problem?

> How do they solve it today?

> Is this problem worth solving?

> What solution, if any, should we build?

The central principle is:

> **Fall in love with the problem, not the solution.**

A Product Manager should not start with:

> "Let's build feature X."

Instead, start with:

> "What problem are we trying to solve, for whom, and how do we know that it is important?"

---

# When to use this skill

| Situation                                         | Skill applies                                                    |
| ------------------------------------------------- | ---------------------------------------------------------------- |
| Exploring a new product idea                      | Yes                                                              |
| Deciding whether to build a feature               | Yes                                                              |
| Validating a user problem                         | Yes                                                              |
| Conducting user interviews                        | Yes                                                              |
| Entering a new market                             | Yes                                                              |
| Defining a target user                            | Yes                                                              |
| Prioritizing product opportunities                | Yes                                                              |
| CEO proposes a specific feature without evidence  | Yes — investigate the underlying problem first                   |
| User retention is declining                       | Yes — discover the underlying reasons before proposing solutions |
| Choosing between several solutions                | Partially — use Discovery first, then solution validation        |
| Writing technical implementation details          | No — use product requirements / technical planning               |
| Managing delivery after the solution is validated | No — use Product Execution                                       |

---

# The Product Discovery mindset

Product Discovery is not about proving that your idea is good.

It is about finding out whether you are wrong as early and as cheaply as possible.

A weak approach:

```text
Idea
↓
Build
↓
Launch
↓
Hope users need it
```

A stronger approach:

```text
Observe
↓
Understand users
↓
Identify the problem
↓
Validate the problem
↓
Explore alternatives
↓
Test solutions
↓
Decide what to build
```

---

# The Discovery Funnel

```text
Broad Problem Space
        ↓
Target User
        ↓
User Needs & Behaviors
        ↓
Problem Identification
        ↓
Problem Validation
        ↓
Opportunity Selection
        ↓
Solution Exploration
        ↓
Solution Validation
        ↓
Build
```

The goal is to reduce uncertainty at every stage.

---

# The core Discovery framework

## Step 1 — Define the Problem Space

Start broad.

Do not start with a feature.

Instead of:

> "We need an AI Financial Copilot."

Start with:

> "We want to understand why young professionals struggle to manage their personal finances."

At this stage, you are exploring.

You do not yet know:

* what the exact problem is;
* who experiences it most;
* how important it is;
* what solution is needed.

### Output

A problem space statement.

Template:

```text
We want to better understand:

[USER GROUP]

and the challenges they experience when:

[CONTEXT / ACTIVITY].
```

Example:

```text
We want to better understand young professionals
and the challenges they experience when managing
their personal finances.
```

---

# Step 2 — Define assumptions

Before research, identify what you currently believe.

These are assumptions.

Example:

```text
Assumption 1:
Young professionals struggle to understand their spending.

Assumption 2:
Users want to manage their finances more effectively.

Assumption 3:
Existing banking applications do not provide enough useful insights.

Assumption 4:
Users would benefit from personalized financial recommendations.
```

Important:

> An assumption is not a fact.

The purpose of Discovery is to test assumptions.

### Assumption map

Classify assumptions by:

* Importance
* Uncertainty

```text
                HIGH IMPORTANCE

                     |
                     |
      Test first     |      Test first
                     |
HIGH UNCERTAINTY ----+---- LOW UNCERTAINTY
                     |
      Monitor        |      Accept temporarily
                     |
                     |

                LOW IMPORTANCE
```

Prioritize assumptions that are:

> **High importance + High uncertainty**

---

# Step 3 — Define the Target User

Do not define users only by demographics.

Weak:

> Women aged 20–30.

Better:

> Young professionals who recently became financially independent, receive a regular income, and are responsible for managing their own recurring expenses.

Focus on:

* Context
* Behaviors
* Goals
* Motivations
* Constraints

### User definition template

```text
TARGET USER:

Who are they?

What are they trying to accomplish?

In what situation does the problem occur?

What constraints do they have?

What alternatives do they currently use?
```

---

# Step 4 — Conduct user research

The goal of user interviews is not to ask people whether they like your idea.

The goal is to understand what they actually do.

Do not ask:

> "Would you use an AI financial assistant?"

Users may say yes because the idea sounds interesting.

Instead ask about:

> Past behavior.

Strong questions:

```text
Tell me about the last time you tried to understand your spending.

What happened?

What triggered you to look at your finances?

What did you do next?

What tools did you use?

What was difficult?

What did you wish you could understand?

How often does this happen?
```

The key principle:

> **Ask about the past, not hypothetical future behavior.**

---

# Interview question types

## Context questions

```text
How do you currently manage your finances?

What tools do you use?

How often do you review your spending?
```

## Recent behavior questions

```text
Tell me about the last time you checked your finances.

What caused you to check them?

What did you do?

What happened next?
```

## Pain questions

```text
What was difficult?

What took the most time?

What was frustrating?

What information was missing?
```

## Alternative questions

```text
How do you currently solve this problem?

What other tools have you tried?

Why did you stop using them?
```

## Importance questions

```text
How often does this problem occur?

What happens if you do nothing?

How important is solving this problem?
```

---

# Step 5 — Identify patterns

After multiple interviews, do not immediately focus on individual opinions.

Look for patterns.

Example:

```text
Interview 1:
"I check my balance, but I don't know why I spent so much."

Interview 2:
"I can see transactions, but it takes time to understand what changed."

Interview 3:
"I usually realize that I overspent at the end of the month."

Interview 4:
"I use spreadsheets sometimes, but I stop after a few weeks."
```

Potential pattern:

> Users have access to financial data but struggle to interpret changes in their spending behavior.

This is stronger than:

> "Users want a better dashboard."

The first describes a problem.

The second already assumes a solution.

---

# Step 6 — Formulate the Problem Statement

A strong problem statement connects:

* User
* Need
* Context
* Consequence

Template:

```text
[USER]

needs a way to

[NEED / JOB]

because

[PROBLEM / PAIN].
```

Example:

```text
Young professionals need a simple way to understand
unexpected changes in their spending because existing
financial tools show transaction data but do not explain
meaningful patterns or changes.
```

---

# Step 7 — Define the Job To Be Done

Ask:

> What is the user actually trying to accomplish?

Do not describe the product.

Bad:

> The user wants an AI assistant.

Better:

> The user wants to understand why their spending changed and decide what to do next.

A useful JTBD format:

```text
When:

[SITUATION]

I want to:

[MOTIVATION / JOB]

So I can:

[DESIRED OUTCOME].
```

Example:

```text
When I notice that I have less money than expected,

I want to understand what changed in my spending,

so I can decide whether I need to change my financial behavior.
```

---

# Step 8 — Explore existing alternatives

Your competition is not only other products.

Users may currently use:

* Excel
* Notes
* Banking apps
* Google
* Friends
* Manual calculations
* Doing nothing

Discovery question:

> What does the user do today?

This helps identify:

* Existing behavior
* Switching costs
* User expectations
* Gaps in the current experience

---

# Step 9 — Validate the opportunity

A problem is stronger when it is:

```text
Frequent
+
Painful
+
Important
+
Poorly solved today
```

Opportunity evaluation:

| Criteria             | Question                                  |
| -------------------- | ----------------------------------------- |
| Frequency            | How often does this problem occur?        |
| Intensity            | How painful is the problem?               |
| Importance           | Does the user actively want to solve it?  |
| Current alternatives | Are existing solutions insufficient?      |
| Reach                | How many relevant users experience it?    |
| Business value       | Is solving this valuable for the company? |

---

# Step 10 — Explore solutions

Only now should you generate solutions.

Example problem:

> Users struggle to understand changes in their spending.

Possible solutions:

```text
Option A:
Spending dashboard

Option B:
Monthly financial summary

Option C:
Smart notifications

Option D:
AI financial assistant

Option E:
Automated financial goals
```

Important:

> AI is a possible solution, not the starting point.

---

# Solution exploration matrix

| Solution            | User Value | Business Value | Effort | Risk   |
| ------------------- | ---------- | -------------- | ------ | ------ |
| Dashboard           | Medium     | Medium         | Medium | Low    |
| Monthly Summary     | Medium     | Medium         | Low    | Low    |
| Smart Notifications | High       | High           | Medium | Medium |
| AI Copilot          | High       | High           | High   | High   |

The goal is not always to choose the most advanced solution.

The goal is to choose the solution that creates the best value relative to effort and risk.

---

# Step 11 — Validate the solution

Before full development, test the riskiest assumptions.

Possible methods:

```text
Prototype testing
User interviews
Clickable Figma prototype
Landing page
Fake door test
Concierge MVP
Wizard of Oz MVP
Beta release
```

Ask:

> Does this solution actually help users solve the problem?

---

# End-to-End Product Discovery workflow

## Workflow: Explore a new product opportunity

```text
1. Define the problem space
2. Identify assumptions
3. Define the target user
4. Prepare research questions
5. Conduct user interviews
6. Analyze patterns
7. Identify user problems
8. Validate the most important problem
9. Define the Job To Be Done
10. Explore existing alternatives
11. Evaluate the opportunity
12. Generate multiple solutions
13. Prioritize solutions
14. Prototype the best hypothesis
15. Test with users
16. Decide what to build
```

---

# Practical example: AI Financial Copilot

## Starting request

Leadership says:

> "We should build an AI Financial Copilot."

Do not immediately build the AI Copilot.

---

## Discovery Step 1

Define the problem space:

```text
We want to understand how young professionals
currently manage their personal finances and where
they experience the biggest difficulties.
```

---

## Discovery Step 2

Create assumptions:

```text
Assumption 1:
Users do not understand where their money goes.

Assumption 2:
Users struggle to notice changes in spending.

Assumption 3:
Users want personalized financial insights.

Assumption 4:
AI can improve financial decision-making.
```

---

## Discovery Step 3

Interview users.

Example insight:

```text
Users do not necessarily lack financial data.

They lack interpretation.

They can see their transactions,
but they do not understand:

"What changed?"

"Why did it change?"

"What should I do next?"
```

---

## Discovery Step 4

Problem statement:

```text
Young professionals need a simple way to understand
significant changes in their spending because existing
financial applications provide transaction data without
helping users interpret what the changes mean.
```

---

## Discovery Step 5

Explore solutions:

```text
1. Better spending visualization

2. Automated monthly insights

3. Smart notifications

4. AI-powered financial explanations
```

---

## Discovery Step 6

Test the solutions.

Possible MVP:

```text
When a significant spending change is detected:

The system sends:

"Your restaurant spending increased by 28% this month,
primarily because you visited restaurants 5 more times
than last month."
```

This MVP may solve the problem without building a full AI Copilot.

---

# Clarify First

Before starting Discovery, confirm the following.

If unknown, do not assume.

```text
[INPUT] What business or product context are we exploring?

[INPUT] What triggered the need for Discovery?

[INPUT] Who do we currently believe the target users are?

[INPUT] What decision needs to be made at the end of Discovery?

[INPUT] What constraints exist?
Time?
Budget?
Technology?
Regulation?
```

---

# Discovery Outputs

A complete Product Discovery process may produce:

```text
Problem Space Definition

Assumption Map

Target User Definition

Interview Guide

Research Notes

Key Insights

Pain Points

User Journey

Problem Statements

Jobs To Be Done

Opportunity Map

Existing Alternatives

Solution Ideas

Prioritization Framework

Prototype

Validation Results

Product Recommendation
```

---

# Anti-patterns

## 1. Starting with a solution

Bad:

> "Let's add AI."

Better:

> "What problem would AI help solve?"

---

## 2. Asking hypothetical questions

Bad:

> "Would you use this product?"

Better:

> "Tell me about the last time you experienced this problem."

---

## 3. Treating one interview as evidence

One user insight is:

> A signal.

It is not:

> A validated market truth.

Look for patterns.

---

## 4. Confusing feature requests with problems

User says:

> "I want a dashboard."

Ask:

> "What are you trying to understand when you need a dashboard?"

The requested feature may not be the actual need.

---

## 5. Falling in love with your idea

If you try to prove that your idea is correct:

You will interpret research selectively.

Instead ask:

> "What evidence would prove that my idea is wrong?"

---

## 6. Doing research without a decision

Do not conduct interviews simply to "learn about users."

Before research, ask:

> "What decision will this research help us make?"

---

# Product Discovery Checklist

Before moving to development, confirm:

```text
[ ] I understand the target user.

[ ] I understand the user's context.

[ ] I have identified a real problem.

[ ] I understand how frequently it occurs.

[ ] I understand the current alternatives.

[ ] I have evidence that the problem matters.

[ ] I can describe the user's Job To Be Done.

[ ] I explored multiple possible solutions.

[ ] I tested the riskiest assumptions.

[ ] I know what success would look like.

[ ] I can explain why this problem is worth solving now.
```

---

# Practical Exercise

## Exercise: Personal Finance Discovery

Problem space:

```text
Why do young professionals struggle to manage
their personal finances effectively?
```

### Your task

1. Write 5 assumptions.
2. Define the target user.
3. Create an interview guide.
4. Conduct 3–5 interviews.
5. Identify recurring patterns.
6. Write 3 problem statements.
7. Define the strongest Job To Be Done.
8. List existing alternatives.
9. Generate 5 possible solutions.
10. Choose one hypothesis to test.

### Deliverable

Create:

```text
/exercises/personal-finance-discovery/
    problem-space.md
    assumptions.md
    interview-guide.md
    research-notes.md
    insights.md
    problem-statements.md
    opportunities.md
    solutions.md
    final-recommendation.md
```

---

# The core principle

Product Discovery is successful when you can move from:

> "I have an idea."

to:

> "I understand a specific user problem, I have evidence that it matters, and I know which solution hypothesis is worth testing next."

