# Personality vs Decision-Making Style: Statistical Analysis

A study of how **Big Five (OCEAN) personality traits** relate to **decision-making styles** (Rational, Intuitive, Avoidant) among people aged 17–27, with comparisons by gender and age group.

**Tools:** Excel · Power BI · Google Forms
**Methods:** Pearson correlation · Independent-samples t-test · One-way ANOVA

---

## Aim

To examine the relationship between OCEAN personality traits and decision-making styles, and to test whether decision-making style differs by gender or age group.

**Hypothesis:** Organised individuals decide logically, and anxious individuals avoid making decisions.

## Dataset

- **Source:** Google Form survey, approved by the project mentor
- **Sample:** 76 responses (25 male, 51 female), ages 17–27

| Age group | Respondents |
|---|---|
| 17–19 | 26 |
| 20–22 | 41 |
| 23–25 | 4 |
| 25–27 | 5 |

- **Questionnaire:** age and gender, 10 personality statements (2 per OCEAN trait), 5 decision-style statements, all on a 1–5 scale
- **Scoring:** each trait or style score is the average of its items. Avoidant is measured by a single item.

## Data Preparation

Responses were exported from Google Forms to Excel (CSV), cleaned, and the columns renamed. Score columns were then built for O, C, E, A, N, Rational, Intuitive and Avoidant.

## Statistical Tests and Results

| Test | Purpose | Result |
|---|---|---|
| Pearson correlation | OCEAN vs decision style (15 pairs) | Conscientiousness and Rational: r = 0.46 (moderate). Openness and Rational: r = 0.34 (weak). Neuroticism and Avoidant: r = −0.02 (negligible). |
| Independent t-test | Male vs female | Rational p = 0.195, Intuitive p = 0.958, Avoidant p = 0.682. None significant. |
| One-way ANOVA | Across the 4 age groups | Rational: F = 4.05, p = 0.0102, significant (scores rise from 3.25 to 4.50 with age). Intuitive p = 0.768 and Avoidant p = 0.505 are not significant. |

## Key Findings

- **Conscientiousness** has the strongest link to Rational decision-making, so this part of the hypothesis is supported.
- The hypothesis that anxious (neurotic) people avoid decisions is **not supported**.
- **Age** affects only Rational decision-making.
- **Gender** has no effect on any decision style.

## Visualisation

- **Excel:** heatmap, scatter plot, age bar chart and gender bar chart
- **Power BI:** interactive dashboard with KPI cards, slicers, a heatmap table, a key-findings box, and info pages for OCEAN and Decision Style

## Limitations

- Avoidant is measured by only one item.
- Only 9 respondents fall in the 23–27 age groups, so the ANOVA result needs caution.
- The sample has more females than males.
- The age brackets "23–25" and "25–27" overlap at 25.
- Each trait has only 2 items, and reliability (Cronbach's alpha) was not checked.

## Future Work

- Run multiple regression, which was discussed but not yet carried out.

## Author

**Lavanya Ajit Dive**
B.Sc. Data Science, SIES College, Nerul
