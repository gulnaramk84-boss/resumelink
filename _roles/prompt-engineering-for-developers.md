---
layout: role
category: "Skills & Frameworks"
title: "Developer-Centric Prompting"
h1: "Using LLMs for Legacy Code Migration and Refactoring"
summary_hack: "Developer-centric prompting means using large language models as a careful assistant for legacy code: understanding old systems, writing tests, planning migrations and refactoring in small, reviewed steps, with the developer remaining responsible for every change."
salary_note: "No salary figure here: this is a skill used inside software engineering roles. See the body for how to show it on a resume."
judgment_skills:
  - "Breaking a migration into small, testable steps"
  - "Writing tests before changing behaviour"
  - "Reviewing generated code critically"
  - "Giving models the right context (files, constraints, examples)"
  - "Security and licensing awareness"
ai_tools:
  - "LLM coding assistants and chat tools"
  - "Test frameworks and coverage tools"
  - "Static analysis and linters"
  - "Version control and code review platforms"
  - "Documentation generators"
ats_keywords:
  - "legacy code migration"
  - "refactoring"
  - "unit testing"
  - "code review"
  - "LLM-assisted development"
  - "technical debt"
  - "software modernisation"
  - "documentation"
  - "CI/CD"
  - "prompt engineering"
resume_bullet_1: "Migrated [N] modules from [old stack] to [new stack] using LLM-assisted refactoring with test coverage reaching [X]%; no critical regressions in [period]."
resume_bullet_2: "Generated characterisation tests for undocumented code, uncovering [N] hidden behaviours before changes."
resume_bullet_3: "Documented [N] legacy services with AI-assisted summaries reviewed by owners, cutting onboarding time for new engineers by [X]."
career_transition: "Software engineers at every level can add this skill. If you maintain older systems, document one migration you did safely, with tests and metrics, and share the approach."
certifications:
  - "Cloud provider developer certificates"
  - "Testing and secure coding courses"
  - "Training from your AI coding tool vendor"
human_touch_tip: "The strongest signal is discipline: tests first, small steps, careful review. Tell a story of a bug the tests caught that the model's code would have shipped."
faq_q1: "Can an LLM migrate a whole legacy system?"
faq_a1: "It can help with parts, such as explaining code, drafting tests and converting well-understood modules, but large migrations still need design decisions, reviews and incremental rollout."
faq_q2: "What should I do before asking a model to refactor?"
faq_a2: "Make sure tests exist (write characterisation tests if not), define the goal and constraints, and work in small diffs that you can review and revert."
faq_q3: "What are the risks?"
faq_a3: "Subtle behaviour changes, security vulnerabilities, licence issues, leaking sensitive code to external tools and over-trusting confident but wrong output."
related_roles:
  - agentic-workflow-optimization
  - prompt-artist
  - ai-cybersecurity-analyst
  - ai-data-curator
description: "How to use LLMs safely for legacy code migration and refactoring: a step-by-step workflow, prompts, testing practices, risks, ATS keywords, resume bullet templates and trusted resources for developers."
insights:
  - "**Tests are the safety net.** Without them, you are asking a model to change behaviour you cannot verify. Characterisation tests capture what the code does today."
  - "**Small diffs, always reviewed.** Ask for one function or module at a time and read every line before merging."
  - "**Give context, not just code.** Include language versions, conventions, constraints and examples of the target style."
  - "**Explain first, change second.** Ask the model to summarise what the code does, then compare with what you know before asking for changes."
mistakes:
  - "Pasting proprietary or sensitive code into tools that your company does not allow."
  - "Merging large generated changes without tests or review."
  - "Accepting new dependencies or licences without checking."
  - "Assuming the model knows your internal libraries and business rules."
interview_questions:
  - "How would you migrate a 15-year-old module with no tests?"
  - "How do you review AI-generated code for security issues?"
  - "What context do you give a model before asking for a refactor?"
  - "How do you decide when not to use an AI tool on a codebase?"
  - "Describe a time a test caught a subtle behaviour change."
action_plan:
  - "**Step 1.** Choose a small module and ask the model to explain it. Verify the explanation against the code and with its owner."
  - "**Step 2.** Write characterisation tests (with AI help) that capture current behaviour, and run them."
  - "**Step 3.** Refactor in small steps, one change per prompt, running tests after each."
  - "**Step 4.** Run static analysis and security checks. Review the full diff."
  - "**Step 5.** Document the approach and results, and roll out gradually behind a flag or in staging."
resources:
  - { title: "Refactoring (Martin Fowler)", url: "https://refactoring.com", note: "the standard reference on safe code changes" }
  - { title: "OWASP Top 10 for LLM Applications", url: "https://owasp.org/www-project-top-10-for-large-language-model-applications/", note: "risks when using or building with LLMs" }
  - { title: "OpenAI: prompt engineering guide", url: "https://platform.openai.com/docs/guides/prompt-engineering", note: "general prompting strategies" }
  - { title: "Google AI for Developers: prompting strategies", url: "https://ai.google.dev/gemini-api/docs/prompting-strategies", note: "guidance for Gemini models" }
---

## What this skill really is

Legacy code is code that matters and is hard to change safely. LLMs are good at reading, summarising and drafting, which makes them useful helpers for understanding old systems and doing repetitive conversions. They are not a replacement for design, testing and review.

## A safe workflow

**Understand** (ask for explanations and verify), **protect** (write tests that capture current behaviour), **change** (small steps, one prompt per change), **verify** (tests, static analysis, review), **release** (gradually, with monitoring). The discipline matters more than any single prompt.

## How to show it on a resume

Describe the system, the migration goal, how you protected behaviour (tests), how AI was used and the measured result: fewer defects, faster migration, better coverage, easier onboarding. Mention reviews and security checks. For pay research, see the [Bureau of Labor Statistics Occupational Outlook Handbook](https://www.bls.gov/ooh/) for software developers, and compare current postings in your market.
