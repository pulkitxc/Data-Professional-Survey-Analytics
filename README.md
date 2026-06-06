# Data-Professional-Survey-Analytics

End-to-end Power BI analytics project exploring global data professional survey data. Implements data cleansing in Power Query, star-schema modeling, and interactive visualization to expose key correlations between job roles, regional salary disparities, programming language preferences, and industry entry difficulty.  # 📊 Data Professional Survey Breakdown



**Tools:** Power BI, Power Query, DAX

**Dataset:** 630 survey responses from data professionals



---



## Overview



This project began as a survey dashboard exploring salary, job roles, programming languages, and satisfaction among data professionals.



The initial expectation was that compensation would explain most of the variation in how people felt about their careers. Instead, the data pointed toward a different story.



Many respondents appeared satisfied with the work itself—learning opportunities, coworkers, and work-life balance scored relatively well—but were less convinced about compensation and long-term progression.



The gap between enjoying the work and feeling rewarded by it became the central theme of the analysis.



---



## What the Satisfaction Scores Suggest



The survey asked respondents to rate several aspects of their professional lives.



Work-life balance averaged **5.74**, while salary satisfaction averaged **4.27**. Learning opportunities and coworker relationships scored noticeably higher.



At first glance, this does not look like a workforce in crisis. Most respondents are not reporting negative experiences on a day-to-day basis.



What stands out is that the strongest dissatisfaction appears around future outcomes rather than present experiences. The issue seems less about enjoying the job and more about uncertainty regarding where the job leads.



---



## Entry Difficulty Leaves a Mark



One of the more interesting patterns involved respondents who reported difficulty entering the field.



These individuals tended to report lower satisfaction across multiple dimensions even after reaching data-related roles.



The dataset cannot explain causation, but it raises an interesting possibility: breaking into the field may not be a temporary hurdle. The experience itself may continue influencing how people evaluate their careers long after they have entered the industry.



In practical terms, the first step into the profession may matter more than many organizations assume.



---



## Career Switchers Tell a Different Story



Career switchers produced a result that initially seemed counterintuitive.



They did not consistently earn more than non-switchers. In some cases, they earned less.



Yet many reported stronger satisfaction levels.



A possible explanation is that switchers evaluate their current role against what they left behind rather than against industry averages. The move into data may improve autonomy, flexibility, or intellectual engagement before it improves compensation.



The transition appears to create psychological gains faster than economic ones.



---



## The Learning-Pay Gap



Another recurring pattern emerged when comparing learning satisfaction with salary satisfaction.



A sizeable portion of respondents reported feeling more satisfied with what they were learning than with what they were earning.



Early in a career, this can be healthy. Learning often acts as a form of future compensation.



The challenge appears when that tradeoff lasts too long. At some point, professionals expect the skills they are building to translate into economic rewards. When that conversion does not happen, dissatisfaction begins to grow.



---



## Four Workforce Profiles



Rather than looking only at age or salary, respondents were grouped according to broader career patterns.



### Established & Secure



Higher salaries, lower entry difficulty, and balanced satisfaction scores.



This group represents the most stable career outcome observed in the dataset.



### Remote-First Optimists



Moderate salaries paired with a strong preference for flexibility.



For these respondents, remote work appears to compensate for some dissatisfaction with compensation.



### Salary-Seeking Strivers



Professionals whose strongest priority for a future role is better pay.



The pattern suggests less of a motivation problem and more of an economic one—they feel their compensation has not caught up with expectations.



### Career-Switcher Strain



Individuals who successfully entered the field after switching careers but have not yet seen the returns they expected.



Their dissatisfaction appears tied more to delayed payoff than to dislike of the work itself.



---



## Geography and Technical Preferences



The largest respondent groups came from the United States and India, with noticeable differences in compensation between regions.



While part of that gap reflects local labor markets, it also reflects how organizations position data roles. In some markets, data functions operate as strategic decision-making assets. In others, they remain primarily operational support roles.



Python emerged as the most commonly preferred programming language.



However, preference should not automatically be interpreted as market value. The data suggests that professionals working heavily with SQL and enterprise tooling can often achieve compensation levels that exceed those of more general Python-focused roles.



Popularity and economic value do not always move together.



---



## Dashboard Overview



The Power BI dashboard includes:



* KPI cards for respondent count and average age

* Country distribution treemap

* Work-life and salary satisfaction indicators

* Average salary by job title

* Programming language preferences

* Difficulty entering the field distribution



Power Query was used for data cleaning and transformation, while DAX was used for measures and calculations.



---



## Final Takeaway



The strongest pattern in this dataset is not that data professionals dislike their work.



Most appear to enjoy learning, collaborating, and working in the field.



The tension emerges when expectations shift toward compensation, advancement, and long-term career payoff.



In that sense, the profession appears highly effective at attracting talent but less consistent at converting that early optimism into durable career satisfaction.



If the analysis can be reduced to a single observation, it is this:



> Many data professionals enjoy the work. A significant number are still waiting for the career to fully deliver on its promise.
