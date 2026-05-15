# Mental models for making decision in this project

This is how we make good decisions:

# Value Optimized Decision Making

Business understanding (global context)

- Current feature or task (local context)
- Mental models (mind algorithms)

## Business understanding (global context)

Minimalist mobile first web app for logging interactions with the people you care and help you
-remember what's important to them
-remember you to get in touch with them

Customer goals:

- easy of use, mobile first, log interactions fast, few clicks to get the job done, minimal clean UI
- focus on human connection, app is secondary

## Current feature or task (local context)

Provided by my prompts

## Mental models (mind algorithms)

- Prioritize in terms of opportunity cost (sense of utility)
  - don't choose the optimal technical solution if it's going to use way more tokens or increase complexity, calibrate.
- 80/20 for deciding when it's good enough and where to focus (specially architecture decisions)
- Calibrate decision effort by the cost of being wrong (one-way vs two-way doors)
  - think more if the cost of being wrong is greater
- Know what you don't know for better risk assessment, prioritization, and debugging
  - if you have known unknowns or unknown unknowns about something, research or ask me
- Everything is more complex than it looks
  - don't assume something is easy, think it through
- The hidden costs of additions to a system
  - avoid adding new abstractions, patterns, libraries. be considerate with the hidden cost of increased complexity
- Understand the difference between local optimization and global optimization
  - always think of the overall code readability and complexity
- Look for historical context and trends
  - when fixing a bug, look for the root cause, log the bugs that you fix so you know what kind of mistakes you've been making
- Work-in-progress tasks add no value, drive them to completion
- Urgent/important matrix for not letting important things become urgent
  - surface tasks that are important and that we should prioritize
- Problem space vs solution space for making sure you fix the right problem
  - if you don't have a clear understanding of the problem, don't start implementing. ask me questions and do research before jumping to the solution
- 5 Whys to find the root cause
  - best way to look for real root causes. When fixing a bug, always look for the root cause by asking why this bug was introduced in the first place. propose new guardrails and refactors we can add to prevent similar issues in the future
- Probabilistic thinking as a tool for clear thinking
- Communicate efficiently by compacting the most amount of relevant information in the least amount of words
- When in doubt, over communicate to prevent possible misalignments
- Respect people's time by keeping everyone posted about your progress and challenges
