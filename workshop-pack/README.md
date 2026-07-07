# Workshop pack — Build Your Own Agent Skill

Everything you need for the hands-on parts of the workshop.

## Where to put it
Unzip this pack so its contents sit **directly inside your working folder** (the one you `cd` into and run `claude` from). If your working folder is `~/Desktop/skills-workshop`, you should end up with:

```
~/Desktop/skills-workshop/
├── example_skill/
│   └── plain-language-summary/SKILL.md
├── sample_inputs/
│   ├── kdense_blog.txt
│   ├── messy_meeting_notes.txt
│   ├── abstract.txt
│   ├── experiment_notes.txt
│   └── results.csv
├── templates/
│   ├── your-skill-template.md
│   └── paper-draft-SKILL.md
└── use_case/
    ├── CRISPR_with_skill.pdf
    └── CRISPR_no_skill.pdf
```

This matters because the workshop commands use **relative paths** (e.g. `cp -R example_skill/plain-language-summary ~/.claude/skills/`), which only work when these folders are in your current working folder.

## What's inside, and where it's used

| File | Used in | What it is |
|------|---------|------------|
| `example_skill/plain-language-summary/` | Warm-up | The ready-made skill you install to feel the before/after |
| `sample_inputs/kdense_blog.txt` | Warm-up | Dense text to summarize (with vs. without the skill) |
| `sample_inputs/abstract.txt` | Open build | The paper abstract for the `paper-draft` baseline + test |
| `templates/your-skill-template.md` | Open build → "Now do your own" | Blank `SKILL.md` to copy for your own skill |
| `templates/paper-draft-SKILL.md` | Open build (Step 3) | The full `paper-draft` skill body to paste while building together |
| `sample_inputs/experiment_notes.txt` | Optional | Messy lab notes — good for a protocol / lab-log skill idea |
| `sample_inputs/messy_meeting_notes.txt` | Optional | Messy meeting notes — good for a notes / summary skill idea |
| `sample_inputs/results.csv` | Optional | Tiny synthetic dataset — good for a data / plot skill (demo-friendly) |
| `use_case/CRISPR_with_skill.pdf` | Intro (use case) | The report written **with** K-Dense's `scientific-writing` skill — real generated figures + cited references |
| `use_case/CRISPR_no_skill.pdf` | Intro (use case) | The same prompt **without** any skill — text only, no real figures — for the before/after contrast |

All inputs are **synthetic or public** — safe to paste and reproduce.
