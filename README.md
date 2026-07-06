# AI Student Impact Analysis

## Project Overview

This project explores how Generative AI affects students' academic performance, study habits, knowledge retention, and AI dependency.

---

## Dataset

The dataset contains information about students from different academic majors and study years.

### Features

| Category | Columns |
|-----------|----------|
| Academic | `pre_gpa`, `post_gpa`, `gpa_change`, `study_hours` |
| AI Usage | `genai_hours`, `tool_diversity`, `prompt_skill`, `paid_sub`, `use_case` |
| Student Behaviour | `ai_dependency`, `exam_anxiety`, `burnout`, `retention_score` |
| Institutional | `policy` |
| Other | `major`, `study_year`, `cluster` |

---
## Key Findings

- Students with **advanced prompt engineering skills** achieved the highest average GPA improvement.
- **Study hours** showed the strongest positive relationship with GPA improvement.
- **GenAI usage hours** were strongly positively correlated with **AI dependency**.
- **Post-GPA** was highly correlated with **Pre-GPA**, suggesting that students' prior academic performance is a much stronger predictor of future performance than their level of GenAI usage.
- **AI dependency** showed little to no meaningful relationship with GPA improvement.
- Students who used a **greater diversity of AI tools** demonstrated slightly better knowledge retention and higher average GPA gains.
- Students with **paid AI subscriptions** spent considerably more time using GenAI but experienced only marginally higher GPA improvements than non-subscribers.
- **STEM** students were the most frequent users of GenAI among all majors, yet their GPA improvements remained relatively similar to those of students from other disciplines.
- Institutions that **allowed AI with proper citation** exhibited slightly higher average GPA improvements than institutions with stricter AI policies.
- Students with higher **AI dependency** tended to report higher levels of **burnout**, indicating a positive association between AI reliance and burnout risk.
- Students who primarily used **GenAI for Debugging/Troubleshooting** achieved higher average GPA improvements, whereas those who mainly used it for **Direct Answer Generation** showed the smallest GPA gains.
