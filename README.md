# Student AI Consumption

Applied analytics project for the Michigan State STT-810 graduate course. The repository packages anonymized usage logs, a reproducible exploratory notebook, and refreshed narrative insights on how students rely on AI support tools.

## Repository Contents
- `analysis/ida_eda.ipynb` holds the initial and exploratory data analysis (IDA/EDA) with staged visuals, statistical tests, and live narrative commentary.
- `data/AI_usage_data.csv` is the cleaned interaction log used throughout the notebook.
- `README.md` (this file) captures the latest study highlights and operational guidance.

## Data Source
- Kaggle: [Data Usage AI in School](https://www.kaggle.com/datasets/danishbaariq/data-usage-ai-in-school)


## Key Insights
| Theme | Highlights |
| --- | --- |
| Participation landscape | 9,551 records across 7 disciplines, 3 student levels, and 6 task types. |
| Satisfaction profile | Mean 3.58 (median 3.60, skew 0.85); bootstrap 95% CI [3.55, 3.61]; 38.9% of sessions score at least 4/10. |
| Segment highlights | Writing tasks average 3.66 satisfaction; undergraduates lead graduates by 0.13 points (Welch's t-test p = 0.0002). |
| Engagement intensity | Average session length 20.78 minutes, prompts 5.87, assistance level 3.64; prompts correlate with session length (r = 0.908) but loosely with satisfaction. |
| Repeat usage | 69.7% of students return; repeat users register 0.13 higher satisfaction on average (Welch p < 0.001). |
| Assistance impact | Linear fit: satisfaction ≈ 0.23 + 0.92 × assistance (R² = 0.719); correlation 0.848. |
| Task popularity | Writing is the most common task (2,892 records); brainstorming appears least (474 records). |

## Next Research Iterations
- Instrument policy-awareness and integrity sentiment questions to mirror external benchmarks.
- Extend task-level post-hoc testing to isolate drivers within the writing and research clusters.
- Prototype intervention simulations that vary assistance intensity and measure predicted satisfaction shifts.