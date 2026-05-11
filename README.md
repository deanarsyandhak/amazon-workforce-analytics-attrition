# Amazon Frontline Attrition Diagnostic & Pilot Intervention
End-to-end workforce business analytics project analyzing frontline attrition drivers and translating employee feedback into operational diagnosis and pilot intervention design

View Full Project → [![View Full Project In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/deanarsyandhak/amazon-workforce-analytics-attrition/blob/main/amazon_frontline_attrition_analysis.ipynb#)

## Executive Summary
This project analyzes frontline employee feedback from Amazon fulfillment centers across two platforms (Glassdoor and YouTube) to identify the primary operational drivers of dissatisfaction and attrition. Using combined sentiment analysis, keyword-based thematic tagging, and adjusted negative signal detection, three core themes surfaced: burnout and physical strain, scheduling pressure, and management bias. Burnout emerged as the most severe theme, with approximately 95% adjusted negative sentiment and near-zero neutral presence. This indicates a threshold experience rather than gradual dissatisfaction. Analysis further revealed a psychological safety gap, with employees turning to YouTube to process workplace experiences rather than internal channels, suggesting that formal feedback mechanisms are failing to capture primary attrition signals. Based on these findings, a 14-day pilot is proposed: a standardized task rotation system for Tier 1 Associates in a single fulfillment zone, using predefined exposure thresholds and a lightweight tracking metric, Task Exposure Balance (TEB), to make biomechanical strain operationally visible.

## Key Skills
### Technical
- Python
- Pandas
- Matplotlib/Seaborn
- TextBlob
- NLTK
- Google Colab
### Analytical & Operational
- Sentiment Analysis
- Thematic Analysis
- Root Cause Analysis (5 Whys)
- Workforce Segmentation & Prioritization
- Friction Mapping
- Pilot Intervention Design

## Business Problem
Amazon's fulfillment centers operate on a high-churn labor model designed to sustain productivity through continuous workforce replacement rather than retention. Although it has its upsides, this model produces a 150% annual turnover rate, which is double the industry average. This is evident as 70% of new hires exit within 90 days, costing an estimated $8 billion annually in recruitment, onboarding, and lost productivity. Amazon maintains this model through strict performance monitoring (e.g. time-off-task), automated warning systems, and mandatory overtime scheduling structures.

While this is effective in short-term cost control, this approach has surfaced three compounding risks:
* Higher-than-sector injury rates linked to repetitive high-intensity tasks
* Saturation of local labour markets in key regions which reduces the available replacement workforce
* Increasing regulatory and public scrutiny from labour researchers and advocacy groups

In response to this Amazon has committed measures such as increased pay, invested in upskilling programs, and added localized HR flexibility. Nevertheless, all of these measures address symptoms rather than the underlying model. This project examines what frontline feedback reveals about the specific operational drivers of dissatisfaction and attrition.

## Project Objectives
- Identify recurring operational dissatisfaction themes from employee feedback
- Compare sentiment patterns across public discussion platforms
- Diagnose potential operational root causes contributing to burnout
- Prioritize workforce segments for intervention focus
- Design a lightweight pilot intervention to reduce burnout-related operational strain

## Data Sources
- Glassdoor employee reviews
- Public YouTube videos containing discussions and worker experiences

## Analytical Workflow
1. Data cleaning and text preprocessing  
2. Exploratory text analysis  
3. Sentiment analysis and hidden strain signal detection  
4. Cross-platform comparison  
5. Thematic analysis  
6. Root cause analysis  
7. Workforce segmentation and prioritization  
8. Pilot intervention design

## Key Insights
<img width="567" height="550" alt="image" src="https://github.com/user-attachments/assets/fcee1efc-ace4-4b5d-a6ee-b145d35f8033" />

- Physical and mental burnout was the most frequent complaint and it functioned as a threshold experience as it had ~95% adjusted negative sentiment with near-zero neutral. Associates either haven't hit it yet or are already gone. Scheduling pressure and management bias were identified as its two compounding inputs, making burnout the convergence point of systemic operational failure.
- Employees are venting to YouTube rather than internal channels. This suggests as a behavioral signal that formal feedback mechanisms are undercounting the true scale of dissatisfaction and attrition risk.
- Standard sentiment analysis misclassified a significant portion of operational strain language as neutral. A keyword-based reclassification approach was developed to surface hidden negative signals, revealing burnout severity substantially higher than surface scores suggested.


## Workforce Prioritization
The analysis identified Tier 1 Associates as the highest-priority intervention segment.
<img width="681" height="562" alt="image" src="https://github.com/user-attachments/assets/eb1b8a73-6e3a-42c3-a0a9-fa865b72100f" />

## Pilot Recommendation
The proposed pilot introduces a standardized task rotation process for Tier 1 Associates within a single high-strain fulfillment zone, targeting a 14-day sprint with 10–20 associates. Associates rotate between high-strain and lower-strain tasks on a fixed cadence, removing task assignment from managerial discretion and embedding it as an operational standard. Compliance is maintained through existing Learning Ambassadors, requiring approximately 90 minutes of onboarding (zero additional headcount cost). Success is measured through two indicators: Task Exposure Balance (TEB), targeting less than 5% over-exposure, and late-shift error rate, targeting 15% quality improvement over the pilot window.

## Repository Structure

```text
README.md
amazon_frontline_attrition_analysis.ipynb
```

## Notes

Due to source platform and privacy considerations, the original datasets used in this project are not included in the repository.
