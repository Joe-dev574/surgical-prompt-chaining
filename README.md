# Surgical Prompt Chaining

**A disciplined approach to AI-assisted coding — keeping the developer in full control.**

Surgical Prompt Chaining is a reusable prompting framework designed to bring precision, clarity, and control to AI-supported software development. Inspired by the disciplined mindset of Brazilian Jiu-Jitsu and years of real-world coding experience, this method prevents messy, overreaching AI output and ensures you remain the architect of your codebase.

---

## Why Surgical Prompt Chaining?

Large language models are powerful tools, but without structure they often produce bloated, inconsistent, or hallucinated changes that require heavy cleanup. This skill enforces a **strict 5-step chain** that mimics surgical precision:

- **Minimal viable changes**
- **Full developer oversight**
- **No uncontrolled rewrites**

It transforms chaotic “vibe coding” into a repeatable, professional workflow.

---

## The 5-Step Chain

Every interaction follows this exact sequence:

1. **Inspect**  
   Carefully read and analyze the current file(s) and relevant context.

2. **Understand**  
   Diagnose the root cause of the issue or requirement with precision.

3. **Design**  
   Propose the smallest, cleanest, and most targeted solution possible.

4. **Apply**  
   Deliver only the necessary, focused code edits — never rewrite entire files unless explicitly instructed.

5. **Verify**  
   Confirm the changes are correct, maintain code quality, and do not introduce regressions.

---

## Core Rule

> **Never rewrite entire files unless the user explicitly allows it.**

This single constraint prevents AI overreach and keeps changes surgical, reviewable, and safe for production codebases.

---

## How to Use

1. Activate the skill by referencing it at the start of your prompt (e.g., `# surgical-prompt-chaining`).
2. Describe your task or issue clearly.
3. The AI will automatically follow the 5-step chain.
4. Every response will conclude with:  
   **“Ready for next step or human review?”**

You stay in complete control at every stage.

---

## Benefits

- **Precision** — Changes are minimal and focused
- **Safety** — Reduced risk of unintended side effects
- **Clarity** — Every step is transparent and auditable
- **Efficiency** — Faster iteration with less cleanup
- **Maintainability** — Code remains consistent with your style and architecture

---

## Installation

```bash
mkdir -p ~/.grok/skills/surgical-prompt-chaining
cd ~/.grok/skills/surgical-prompt-chaining
# Place SKILL.md and this README.md in the directory
```

Now place the following two files inside ~/.grok/skills/surgical-prompt-chaining/:

README.md — (this file) — contains documentation and usage instructions
SKILL.md — contains the exact system-level instructions that tell Grok how to behave when the skill is triggered

Expected Final Directory Structure
After installation, your folder should look like this:

~/.grok/skills/surgical-prompt-chaining/
├── README.md
└── SKILL.md
