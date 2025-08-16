Task_05_Descriptive_Stats

This project is part of Research Task 05. The goal is to see how well a large language model (LLM) like ChatGPT can analyze a real dataset using simple text prompts. The dataset we worked with is from the 2024 Formula 1 sprint races.

The work was split into two reporting periods. This file shows what was done in both.

Dataset

File used: Formula1_2024season_sprintResults.csv (stored locally)

Contains results from sprint races in the 2024 F1 season.

Includes details such as:

Driver

Team

Track

Starting Grid

Finishing Position

Points

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

Visualizations

Plotted regression graphs for:

Starting Grid vs Points

Improvement vs Points

Prompt Testing with LLM

Asked ChatGPT basic questions about the data.

Compared its answers with Python results.

Documented where it was correct and where it struggled.

Reporting Period 2 (Second Half: Aug 1–15)
Advanced Prompt Testing

Used more detailed prompts to test LLM reasoning.

Asked the LLM to:

Analyze team performance per track

Find drivers who regularly finished better than their starting grid

Rank drivers by “efficiency” (points gained vs starting position)

Compared LLM answers with Python outputs to check accuracy.

Deeper Data Analysis

Looked at:

Driver trends across multiple tracks

Team stability per track

More correlations between grid position, finish position, and points

Key Takeaways

LLM Strengths: Great at giving summaries and big-picture insights quickly.

LLM Weaknesses: Can get confused with multi-step logic, filtering, or calculations.

Python Strengths: Reliable for accurate numbers, detailed analysis, and validation.
