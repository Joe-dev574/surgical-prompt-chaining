# surgical-prompt-chaining

**A disciplined way to use AI for coding — keeping the developer in full control.**

This is a reusable Grok skill that enforces a strict 5-step prompting chain with one simple rule: **never rewrite entire files unless explicitly told**. It grew out of my own frustration with messy AI output while building real apps.

---

## The Idea

After many years of training BJJ and working as a developer, I noticed that the best results come from control, not chaos. Surgical Prompt Chaining is my attempt to bring that same principle to AI-assisted development.

## The 5-Step Chain

1. **Inspect** — Read the current file(s) first  
2. **Understand** — Diagnose the exact root cause  
3. **Design** — Propose the smallest possible fix  
4. **Apply** — Make targeted edits only  
5. **Verify** — Confirm everything works and stays clean  

Every response ends with: **“Ready for next step or human review?”**

## Core Rule
**Do NOT rewrite entire files** unless you explicitly allow it.

## How to Install in Grok

1. Open **Terminal** and run:

  ```bash
mkdir -p ~/.grok/skills/surgical-prompt-chaining
cd ~/.grok/skills/surgical-prompt-chaining
touch SKILL.md README.md
```

Then copy the contents of SKILL.md and README.md from this repo into those files.
Verify the files were created:

```bash
ls ~/.grok/skills/surgical-prompt-chaining/
```

You should see: SKILL.md and README.md
How to Use
Start any message to Grok with one of these trigger phrases:
Recommended Trigger Phrases (copy & paste):

Use surgical prompt chaining to…
```bash
Use surgical prompt chaining to correct only the compile errors in SettingsView.swift. Do NOT rewrite the file.
```

Surgical edits only…
```bash
Surgical edits only: add a new Stepper for default number of strings in the Timer Defaults section.
```

Chain with precision…
```bash
Use surgical prompt chaining to add AVFoundation beeps and randomized delays to the TimerEngine. Do not touch SettingsView.swift.
```
Currently Being Used In
TriggerPulse — a focused training timer for shooters with native Apple Watch support.



