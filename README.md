# The Impact of AI on Jobs by 2030: An Automation-Risk Analysis

## 1. Project Overview

**Purpose.** Artificial intelligence is changing what work looks like. This project uses a dataset of **3,000 worker records across 20 job titles** (source: [Kaggle – AI Impact on Jobs 2030](https://www.kaggle.com/datasets/khushikyad001/ai-impact-on-jobs-2030)) to find out **which jobs are most likely to be automated by 2030, and which commonly assumed "protective" factors (pay, education, experience, AI exposure) actually make a difference.**

**Approach.**
1. Understand the business context and stakeholders.
2. Load and clean the data, and check its quality.
g3. Frame **five business problems**, and answer each with one chart.
4. For every chart: write an **Observation** (what the chart shows), a **Conclusion** (what it means) and a **Recommendation** (what to do about it).


- The data was sourced from [Kaggle](https://www.kaggle.com/datasets/khushikyad001/ai-impact-on-jobs-2030)
- The data has the following characteristics
   - Job_Title - The job
   - Average_Salary - Average salary the respective job gets
   - years_Experiencing - Number of years person has been on been on the job
   - Education Level - The level of education a person has
   - AI_Exposure_Index - The level of exposure to AI
   - Tech_Growth_Factor - 
   - Automation_Probability_2030 - How likely will the job be automated by 2030
   - Risk_Category - How risky is the job to be replaced by ai 
   - Skills - Random Skills

   ## 2. Business Understanding

**Business context.** Governments, employers, schools and workers are all making long-term decisions (budgets, hiring, curricula, career moves) without a clear picture of which roles AI is likely to automate. Getting this wrong means either wasted training money or workers being caught unprepared.

**Business objective.** Identify the roles and worker groups most exposed to automation by 2030 and give each stakeholder evidence-based actions to reduce that exposure.


**Stakeholders**

| Stakeholder | What they care about | How they will use this analysis |
|---|---|---|
| Government / labour-ministry policy makers | Unemployment, social protection, national skills strategy | Decide where to direct reskilling funds and transition support |
| Education & training providers (universities, technical colleges, bootcamps) | Relevant curricula, graduate employability | Redesign programmes towards roles and skills that stay in demand |
| Employers & HR / workforce-planning leaders | Cost, productivity, retention, redeployment | Plan role redesign, redeployment and upskilling before roles are automated |
| Workers & trade unions | Job security, fair transitions | Negotiate retraining and transition support; understand personal exposure |
| Career counsellors, students & job seekers | Choosing a durable career path | Advise on which occupations are safer and which "safe" assumptions are false |
| Investors & industry bodies | Sector outlook, talent supply | Anticipate labour-cost changes and talent shortages by sector |

**Key questions (the five business problems).**
1. Which jobs face the highest automation risk, and how much of the workforce is that?
2. Does a higher education level protect a worker?
3. Does more work experience protect a worker?
4. Does the AI Exposure Index tell us who is actually at risk
5. what skill combination best insulate roles from high automation risk?
6. How do tech growth trends compare to automation exposure?

**Python libraries**
1. Pandas
2. numpy
3. matplotlib
4. seaborn