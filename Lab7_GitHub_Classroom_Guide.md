# Lab 7 — GitHub Classroom Guide

## Attack & Defend — Setup & Grading

---

## Template Repository

Name: `genai-lab7-attack-defend`

Uses same devcontainer as Lab 6 (sentence-transformers + ChromaDB + Ollama).

## Auto-Grading Tests (25 points)

| Test | Points |
|------|--------|
| Notebook + security_table.md exist | 5 |
| Notebook executed (≥8 cells) | 5 |
| Attack log saved (data/attack_log.json) | 5 |
| Security table not template (≤5 TODOs) | 5 |
| Security table has key terms | 5 |

## Manual Grading (75 points)

| Component | Points |
|-----------|--------|
| Part 1: Attack quality (≥10, 4 categories) | 25 |
| Part 2: Defense layers + comparison | 20 |
| Part 3: Security table + risk register | 20 |
| Mechanistic connections to Modules 1-6 | 10 |

### Feedback Template

```markdown
## Lab 7 Feedback

**Auto-grading:** X/25
**Manual grading:** X/75

### Red Team (Part 1)
- [ ] ≥10 attacks across 4 categories
- [ ] Success/impact/severity scored for each
- [ ] Indirect injection tested with poisoned docs
- [ ] Bias probes with matched-pair analysis

### Hardening (Part 2)
- [ ] Input sanitizer tested against attacks
- [ ] Hardened prompt compared to original
- [ ] Output validator tested
- [ ] Defense-in-depth conclusion reached

### Documentation (Part 3)
- [ ] Complete attack log table
- [ ] Risk register with ≥5 entries
- [ ] Usage policy present
- [ ] Mechanistic analysis references attention/context
```

---

*GitHub Classroom Guide — Lab 7 of 8*
