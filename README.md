# Lab 7 — Attack & Defend

**Generative AI & Prompt Engineering — A Mechanistic Approach**

Module 7: Security, Bias & Ethics | Duration: 90 minutes

---

## Overview

Before shipping DevAssist, the team needs a security review. You'll **red-team** the RAG assistant from Lab 6, then **harden** it with three defense layers, and **document** everything in a security artifact.

1. **Part 1 (45 min):** Red Team — 4 attack categories, ≥10 attacks
2. **Part 2 (30 min):** Harden — input sanitization + hardened prompt + output validation
3. **Part 3 (15 min):** Document — security table, risk register, usage policy

---

## Repository Structure

```
genai-lab7-attack-defend/
├── lab7_attack_defend.ipynb            # ← YOUR MAIN WORKSPACE
├── security_table.md                   # ← YOUR DELIVERABLE
├── corpus/docs/                        # TaskFlow docs (reused from Lab 6)
│   ├── project_overview.md
│   ├── api_reference.md
│   ├── getting_started.md
│   ├── faq.md
│   └── changelog.md
├── utils/
│   ├── generation_utils.py
│   ├── chunking_utils.py
│   ├── embedding_utils.py
│   ├── retrieval_utils.py
│   └── security_utils.py              # sanitize_input, validate_output, HARDENED_SYSTEM_PROMPT
├── tests/
│   └── test_deliverables.py
└── data/
    └── precomputed_outputs.json
```

---

*Lab 7 of 8 — DevAssist / TaskFlow Lab Series*
