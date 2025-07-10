# Social Media and Mental Health Analysis

This project investigates the impact of social media usage on mental health by performing an Exploratory Data Analysis (EDA) on survey data. It analyzes how platform usage, time spent on social media, and demographic factors correlate with mental health indicators such as ADHD, anxiety, depression, and self-esteem.

---

## Project Objective

- To explore the relationship between social media usage patterns and mental health conditions.
- To identify demographic factors (age, gender, occupation) that influence mental health outcomes.
- To visualize key patterns and correlations in the data to provide actionable insights.

---

## Dataset Overview

The dataset contains survey responses from **481 participants**, including:
- **Demographic Information:** Age, Gender, Relationship Status, Occupation
- **Social Media Usage:** Platforms used, daily usage hours, user status
- **Mental Health Indicators:** ADHD, Anxiety, Self-esteem, Depression (derived from standardized screening tools)

---

## Methodology

### Data Collection & Cleaning
- Collected from an online survey.
- Cleaned inconsistencies in age, gender, and social media user fields.
- Standardized mental health scores where **higher scores represent poorer mental health**.

### Feature Engineering
- Grouped social media platforms into categories: Social Networking, Media Sharing, Discussion Forums.
- Created total mental health scores by summing individual category scores.
- Binned continuous variables like Age into ranges for better analysis.

### Exploratory Data Analysis
- Performed descriptive statistics and correlation analysis.
- Visualized patterns across demographic groups.
- Investigated the relationship between social media engagement and mental health.

---

## Key Findings

- **Younger participants (19-30 years)** reported worse mental health outcomes.
- **University students** and **school students** exhibited the highest mental health scores (indicating poorer mental health).
- **Higher social media usage hours correlated with worse mental health scores**, particularly anxiety and ADHD.
- **Cross-platform usage** (multiple social media types) showed stronger negative mental health effects than single-platform use.
- Female participants, on average, spent slightly more time on social media and reported higher mental health challenges.

