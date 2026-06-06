# Data-Professional-Survey-Analytics
End-to-end Power BI analytics project exploring global data professional survey data. Implements data cleansing in Power Query, star-schema modeling, and interactive visualization to expose key correlations between job roles, regional salary disparities, programming language preferences, and industry entry difficulty.

# Data Professional Survey Breakdown

**Status:** Completed  
**Tools:** Power BI (Power Query, DAX)  
**Dataset:** 630 survey responses from data professionals (2022)

---

## Overview

This project analyzes a survey of 630+ data professionals to understand workforce patterns across salary, satisfaction, career entry difficulty, and role distribution. The dashboard was built in Power BI after data cleaning and transformation in Power Query.

The core finding is that satisfaction with day-to-day work (coworkers, learning, work-life balance) runs notably higher than satisfaction with structural career factors (salary, upward mobility). This suggests a workforce that is engaged with the work itself but uncertain about long-term payoff.

---

## Key Findings

### 1. Satisfaction Misalignment

Survey respondents rated their happiness across several dimensions on a 0-10 scale:

- **Work/Life Balance:** 5.74
- **Salary:** 4.27
- **Coworkers:** ~6.5
- **Learning New Things:** ~7.2
- **Upward Mobility:** ~4.8

The pattern is consistent: relational and experiential factors score higher than economic and advancement factors. This indicates that frustration in data roles is more often about career trajectory than daily work environment.

### 2. Break-In Difficulty as a Lasting Factor

Respondents who reported higher difficulty breaking into data also showed lower satisfaction across most dimensions. This correlation suggests that entry friction is not just an initial hurdle — it appears to have a lasting effect on career outcomes.

Possible mechanisms:

- Weaker initial bargaining power leading to suboptimal first roles
- Slower salary compounding from a lower starting point
- Extended tolerance of poor conditions due to sunk effort in career transition

### 3. Career Switchers

Career switchers into data do not show clear salary advantages over non-switchers, but they often report higher satisfaction. This likely reflects comparison effects: data roles are evaluated against previous careers rather than against an idealized standard. The transition appears to deliver subjective improvement faster than objective economic gain.

### 4. The Growth Gap

A derived variable measuring the gap between learning satisfaction and salary satisfaction reveals a common pattern: many respondents feel they are learning substantially more than they are being paid fairly for. This creates a "development now, reward later" dynamic that is sustainable early in a career but becomes a retention risk if it persists.

### 5. Workforce Segments

Clustering on salary, age, break-in difficulty, satisfaction, and switching behavior identifies four distinct segments:

**Established and Secure**
- Higher salary, lower break-in difficulty, balanced satisfaction across dimensions
- Lowest attrition risk

**Remote-First Optimists**
- Prioritize remote work, moderate compensation, high learning-to-salary gap
- Remote work functions as a partial compensation substitute
- Fragile if remote policies or salary compression worsen

**Salary-Seeking Strivers**
- Younger to mid-career, lower current pay, rank "better salary" as top priority for next role
- High active search risk

**Career-Switcher Strain**
- Many switchers, lower salaries, above-average break-in difficulty, weaker overall satisfaction
- Most vulnerable to disappointment due to already-invested transition cost

### 6. Geographic Salary Variation

The survey shows substantial salary differences by region. The United States cluster averages roughly $75k-$90k+, while India and developing regions show significantly lower ranges. This gap reflects more than cost-of-living differences — it indicates variation in how data roles are positioned within organizations (strategic asset vs. operational support).

### 7. Programming Language Preferences

Python dominates self-reported favorite languages, likely due to accessibility for entry-level professionals. However, this preference metric should be read cautiously: professionals working primarily in SQL or proprietary enterprise tools often report higher compensation than Python users in basic scripting roles. Preference does not necessarily map to production value or market rate.

---

## Dashboard Components

- **KPI Cards:** Total respondents (630), average age (29.87)
- **Treemap:** Country distribution of survey takers
- **Gauge Charts:** Work/life balance satisfaction (5.74) vs. salary satisfaction (4.27)
- **Horizontal Bar:** Average salary by job title
- **Stacked Bar:** Favorite programming language by role
- **Donut Chart:** Distribution of break-in difficulty responses

---

## Technical Approach

**Data Cleaning — Power Query**
- Standardized salary range categories
- Consolidated and normalized "Other" text responses
- Handled missing values
- Created derived indices for satisfaction gaps

**Data Modeling — DAX**
- Calculated custom measures for segment scoring
- Built satisfaction gap metrics
- Developed indices for role premium and market friction

**Visualization — Power BI**
- Designed for executive consumption with direct, action-oriented titles

---

## What This Project Demonstrates

Most Power BI portfolio projects describe what the data shows. This project is structured to explain why the patterns matter and what they imply for workforce strategy.

Example reframes:

- Instead of: "Data Scientists earn more than Data Analysts"
- The analysis shows: "The salary gap between Data Scientist and Data Analyst roles is substantial in mature markets but narrows in emerging markets, suggesting geographic talent arbitrage"

- Instead of: "Python is the most popular language"
- The analysis shows: "Python's popularity reflects low entry barriers, but compensation data suggests SQL and enterprise tool specialists often command higher rates — indicating a skills-market mismatch"

---



