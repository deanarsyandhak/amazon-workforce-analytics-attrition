# Amazon Frontline Attrition Diagnostic & Pilot Intervention
End-to-end workforce analytics project analyzing frontline attrition drivers and translating employee feedback into operational diagnosis and pilot intervention design

## Executive Summary
This project analyzes frontline employee feedback from Amazon fulfillment centers across two platforms — Glassdoor and YouTube — to identify the primary operational drivers of dissatisfaction and attrition. Using combined sentiment analysis, keyword-based thematic tagging, and adjusted negative signal detection, three core themes were surfaced: burnout and physical strain, scheduling pressure, and management bias.
Burnout emerged as the most severe theme, with approximately 95% adjusted negative sentiment and near-zero neutral presence — indicating a threshold experience rather than gradual dissatisfaction. Analysis further revealed a psychological safety gap, with employees turning to YouTube to process workplace experiences rather than internal channels, suggesting that formal feedback mechanisms are failing to capture primary attrition signals.
Based on these findings, a 14-day pilot is proposed: a standardized task rotation system for Tier 1 Associates in a single fulfillment zone, using predefined exposure thresholds and a lightweight tracking metric — Task Exposure Balance (TEB) — to make biomechanical strain operationally visible. The intervention is zero additional headcount cost, leverages existing Learning Ambassadors for floor-level compliance, and is designed to prove workload sustainability without disrupting productivity targets.

## Key Skills
### Technical
- Python
- Pandas
- Matplotlib / Seaborn
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
Amazon's fulfillment centers operate on a high-churn labor model designed to sustain productivity through continuous workforce replacement rather than retention. This model produces a 150% annual turnover rate — double the industry average — with 70% of new hires exiting within 90 days, costing an estimated $8 billion annually in recruitment, onboarding, and lost productivity.
The model is operationalized through strict performance monitoring, automated warning systems, and mandatory overtime structures that prioritize throughput over workforce sustainability. While effective at short-term cost control, this approach has surfaced three compounding risks: higher-than-sector injury rates linked to repetitive high-intensity tasks, saturation of local labor markets in key regions reducing the available replacement workforce, and increasing regulatory and public scrutiny from labor researchers and advocacy groups.
Amazon has responded with pay increases, upskilling investments, and localized HR flexibility — measures that address symptoms rather than the underlying model. This project examines what frontline employee feedback, drawn from Glassdoor and YouTube, reveals about the specific operational drivers of dissatisfaction and attrition, and whether a targeted, low-cost intervention can reduce strain at the point where it is most acute.

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
1. Data preparation and text preprocessing  
2. Exploratory text analysis  
3. Sentiment analysis and hidden strain signal detection  
4. Cross-platform comparison  
5. Thematic analysis  
6. Root cause analysis  
7. Workforce segmentation and prioritization  
8. Pilot intervention design

## Key Insights
<img width="567" height="550" alt="image" src="https://github.com/user-attachments/assets/fcee1efc-ace4-4b5d-a6ee-b145d35f8033" />

- Burnout-related physical and mental strain emerged as the dominant dissatisfaction theme across both Glassdoor and YouTube discussions, indicating significant operational sustainability and attrition risk among frontline workers.
- Hidden operational strain signals frequently appeared within reviews initially classified as neutral or positive, suggesting that standard sentiment analysis alone underestimated dissatisfaction severity.
- Employees used YouTube as an external public platform to express workplace frustrations, suggesting potential gaps in psychological safety and internal feedback visibility.
- On Glassdoor, reviews consistently cite favoritism, nepotism, and biased promotions as structural management failures rather than individual incidents, suggesting the problem is systemic rather than isolated to specific managers.

## Workforce Prioritization
The analysis idnetified Tier 1 Associates as the highest-priority intervention segment.
<img width="681" height="562" alt="image" src="https://github.com/user-attachments/assets/eb1b8a73-6e3a-42c3-a0a9-fa865b72100f" />

## Pilot Recommendation
The proposed intervention introduces a standardized task rotation process supported by lightweight strain-monitoring mechanisms to improve workload sustainability and reduce burnout-related operational risk among **Tier 1 Associates**.

## Repository Structure

```text
README.md
amazon_attrition_analysis.ipynb
