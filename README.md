---
license: cc-by-4.0
language:
  - pl
  - en
pretty_name: "DrugieJa.pl (Alter Ego) — 24 Behavioral Archetypes, Situation Blockers & 10D Capability Vectors"
description: "Bilingual-documented behavioral design and situational adaptation taxonomy from DrugieJa.pl (Alter Ego): 24 behavioral archetypes with 10-dimensional capability vectors (0-5) and 5 tone axes (-2..2), 12 situational blockers, 16 behavioral moves with diplomatic/neutral/direct opening lines, and 204 cultural role-model references."
size_categories:
  - n<1K
task_categories:
  - text-classification
  - tabular-classification
  - question-answering
tags:
  - behavioral-science
  - psychology
  - decision-making
  - archetypes
  - taxonomy
  - local-first
  - self-regulation
  - poland
---

# DrugieJa.pl (Alter Ego) — 24 Behavioral Archetypes, Situation Blockers & 10D Capability Vectors

> **Canonical Web Application:** [https://drugieja.pl/](https://drugieja.pl/)

---

## English Overview

**[DrugieJa.pl — Alter Ego](https://drugieja.pl/)** is a privacy-first, local-first behavioral design tool that translates a concrete high-stakes or blocked situation into an actionable, time-bounded **Mission Card** (*Karta Misji*).

Instead of treating personality as a fixed diagnostic label, **Alter Ego** models two formal taxonomies connected by a mathematical **Behavior Bridge** (*Most Zachowania*):
1. **The Situation World (*Świat Sytuacji*):**
   - **8 Life Domains (`domainId`):** `work`, `sport`, `family`, `social`, `growth`, `wellbeing`, `creative`, `change`.
   - **12 Situational Blockers (`blockerId`):** `fog` (*Mgła*), `choice_paralysis` (*Paraliż wyboru*), `avoidance` (*Unikanie*), `exposure_fear` (*Lęk przed ekspozycją*), `overload` (*Przeciążenie*), `inconsistency` (*Brak konsekwencji*), `performance_pressure` (*Presja wyniku*), `conflict` (*Konflikt*), `weak_boundaries` (*Słabe granice*), `uncertainty` (*Niepewność i zmiana*), `failure_restart` (*Porażka i restart*), `meaninglessness` (*Brak sensu lub połączenia*).
   - **16 Behavioral Moves (`moveId`):** `understand`, `decide`, `start`, `simplify`, `focus`, `finish`, `speak_up`, `negotiate`, `lead`, `set_boundary`, `perform_under_pressure`, `endure`, `adapt`, `repair`, `create`, `recover` — each equipped with structured vs. free-form first actions and diplomatic, neutral, and direct opening lines.
2. **The Alter Ego World (*Świat Alter Ego*):**
   - **24 Behavioral Archetypes** (e.g., *Kartograf*, *Decydent*, *Pionier*, *Rzemieślnik*, *Zawodnik*, *Kapitan*, *Głos*, *Dyplomata*, *Strażnik*, *Odkrywca*, *Alchemik*, *Kotwica*, *Strateg*, *Badacz*, *Redaktor*, *Improwizator*, *Rzecznik*, *Negocjator*, *Mentor*, *Gospodarz*, *Ogrodnik*, *Regenerator*, *Iskra*, *Łącznik*), each parameterized by:
     - a **10-Dimensional Capability Vector (`0–5`)**: `[clarity, decisiveness, courage, focus, resilience, flexibility, empathy, assertiveness, expression, care]`,
     - a **12-Blocker Fit Vector (`0–5`)**,
     - **5 Tone Axes (`-2..+2`)**: `intensity`, `warmth`, `directness`, `structure`, `playfulness`,
     - entry/exit rituals, somatic body signals, 3 operational rules, and shadow risk + mitigation.

### Dataset Contents

| File (JSON & CSV pairs) | Records | Description |
| :--- | :---: | :--- |
| `alter-ego-24-behavioral-archetypes.json` / `.csv` | **24** | Complete profiles, 10D capability vectors, 5 tone axes, context fit scores, somatic signals, rituals, and shadow mitigations for all 24 behavioral archetypes. |
| `situation-blockers-and-behavioral-moves.json` / `.csv` | **28** | 12 situational blockers and 16 behavioral moves with 10D need vectors, safety sensitivity flags, and diplomatic/neutral/direct opening lines. |
| `cultural-role-models-inspiration-catalog.json` / `.csv` | **204** | Curated catalog of 204 fictional and public figures across 6 cultural domains (`book`, `film`, `series`, `game`, `sport`, `science_art_business`) used for bottom-up trait exploration. |

---

## Opis po polsku (Polish Overview)

**[DrugieJa.pl (Alter Ego)](https://drugieja.pl/)** to lokalne narzędzie adaptacyjne przygotowujące sposób działania do konkretnej sytuacji: od krótkiego wywiadu, przez dobór profilu roboczego na podstawie wektorów potrzeb i zdolności, po edytowalną **Kartę Misji** (zasady, rytuał wejścia i wyjścia, sygnał z ciała, pierwsze działanie w 10 minut i pierwsze zdanie).

Pakiet Open Data (CC BY 4.0) udostępnia pełny model domenowy aplikacji:
- **24 archetypy zachowania** z 10-wymiarowymi wektorami zdolności (`clarity`, `decisiveness`, `courage`, `focus`, `resilience`, `flexibility`, `empathy`, `assertiveness`, `expression`, `care`), 5 osiami tonu (`intensity`, `warmth`, `directness`, `structure`, `playfulness`), rytuałami oraz analizą cienia (ryzyko nadużycia i korekta),
- **12 blokad sytuacyjnych i 16 ruchów behawioralnych** tworzących Most Zachowania oraz warianty komunikacyjne (dyplomatyczny, neutralny, bezpośredni),
- **204 postacie kultury i wzorce publiczne** w 6 kategoriach wykorzystywane w ścieżce eksploracji cech.

---

## Citation & License

Released under **Creative Commons Attribution 4.0 International (CC BY 4.0)**. Please cite **[DrugieJa.pl](https://drugieja.pl/)**:

```bibtex
@misc{pytlarz2026drugieja,
  author       = {Pytlarz, Piotr},
  title        = {DrugieJa.pl (Alter Ego): 24 Behavioral Archetypes, Situation Blockers and 10D Capability Vectors},
  year         = {2026},
  url          = {https://drugieja.pl/},
  note         = {CC BY 4.0 Open Data Package}
}
```
