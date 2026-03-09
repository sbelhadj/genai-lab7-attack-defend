# Lab 7 — Attack & Defend

## Student Instructions

**Module:** 7 — Security, Bias & Ethics | **Duration:** 90 min | **Pair programming**

---

## Context

DevAssist works — but is it safe? Every mechanism that makes LLMs useful also creates a vulnerability. In this lab you systematically attack your Lab 6 RAG assistant, then defend it.

---

## Lab Structure

| Phase | Time | Activity |
|-------|------|----------|
| Part 1: Red Team | 45 min | 4 attack categories, ≥10 attacks with analysis |
| Part 2: Harden | 30 min | 3 defense layers: sanitizer, hardened prompt, output validator |
| Part 3: Document | 15 min | security_table.md: attack log + risk register + usage policy |

---

## Attack Categories

| # | Category | Mechanism Exploited |
|---|----------|-------------------|
| 1 | Direct Injection | Attention is context-agnostic (Module 2) |
| 2 | Indirect Injection | Poisoned docs enter context via RAG (Module 6) |
| 3 | System Prompt Exfiltration | Auto-regressive completion (Module 1) |
| 4 | Bias Probes | Training data statistical patterns (Module 1) |

---

## Deliverables

| # | What | Where |
|---|------|-------|
| 1 | Completed notebook with ≥10 attacks + defense comparison | `lab7_attack_defend.ipynb` |
| 2 | Security table with attack log, defenses, risk register, usage policy | `security_table.md` |

---

## Evaluation Criteria

| Criterion | Weight |
|-----------|--------|
| Mechanistic understanding (why attacks work, connection to Modules 1-6) | 25% |
| Attack quality (variety, creativity, correct classification) | 25% |
| Defense implementation & comparison (3 layers, measured improvement) | 20% |
| Documentation quality (security table completeness, risk register) | 20% |
| Responsibility (usage policy, ethical reflection) | 10% |

---

*Lab 7 of 8 — DevAssist / TaskFlow Lab Series*
