Task_05_Descriptive_Stats

This project is part of Research Task 05. The goal is to see how well a large language model (LLM) like ChatGPT can analyze a real dataset using simple text prompts. The dataset we worked with is from the 2024 Formula 1 sprint races.
The work was split into two reporting periods. This file shows what was done in both.

Dataset:
File used: Formula1_2024season_sprintResults.csv (stored locally)

Contains results from sprint races in the 2024 F1 season.

Includes details such as:
Driver, Team, Track, Starting Grid, Finishing Position, Points

Reporting Period 1 (First Half)

Data Analysis with Python
Loaded and summarized the dataset (shape, columns, sample rows).

Calculated:

Top drivers and teams by total points
Average finishing position for each driver
Team consistency (using standard deviation of finishing positions)
Checked correlations between:
Starting Grid and Finishing Position
Improvement (gaining positions) and Points
Starting Grid and Points

Visualizations:

Plotted regression graphs for:
Starting Grid vs Points
Improvement vs Points
Prompt Testing with LLM

Asked ChatGPT basic questions about the data, and compared its answers with Python results.
Documented where it was correct and where it struggled.

Key Takeaways

1. LLM Strengths: Great at giving summaries and big-picture insights quickly.

2. LLM Weaknesses: Can get confused with multi-step logic, filtering, or calculations.

Python Strengths: Reliable for accurate numbers, detailed analysis, and validation.
