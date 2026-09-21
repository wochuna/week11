# Mock Interview Script — Yvonne Wochuna (Data Analyst / Operations Roles)

Use this as a rehearsal script. Read the interviewer's question, then practice saying the answer
in your own words rather than memorizing it word-for-word — the STAR structure (Situation, Task,
Action, Result) is what matters, not the exact phrasing.

---

## Warm-up

**Interviewer:** "Tell me about yourself."

**Suggested answer:** "I'm a Biomedical Engineering graduate from Kenyatta University who moved into
data and cloud work over the last year. After graduating, I did AWS cloud training and became an
AWS Certified Cloud Practitioner, then completed a Data Science & AI program where I worked on
real-world datasets — cleaning data, running exploratory analysis, and building machine learning
models in Python. Right now I'm a DevOps Engineer at E&M Technology House, where I containerize
applications with Docker and manage deployments, and I also just finished a hackathon project
called FlowGuard, where I worked as the data engineer on a decision-intelligence platform for
Kenya Pipeline Company. I'm looking for a role where I can keep combining data analysis with
hands-on technical delivery."

---

## STAR Questions

**1. "Tell me about a time you solved a problem with data."**
*(S)* On the FlowGuard hackathon project, our team was trying to help Kenya Pipeline Company
reduce truck turnaround delays that were causing demurrage costs at their terminals.
*(T)* My part was building the data layer that would feed accurate, real-time information to the
prediction and optimization models.
*(A)* I helped design the database structure for orders, dispatch assignments, and predictions, and
made sure the data pipeline captured events cleanly so the models downstream could trust the input.
*(R)* In testing, the resulting system resolved 46 of 50 at-risk scenarios and cut average
turnaround time from 87 to 56 minutes — a 36% improvement, which we translated into a business
case protecting an estimated KES 14.82M in demurrage exposure.

**2. "Describe a time you had to learn something new quickly."**
*(S)* When I joined the AWS re/Start program, I had almost no cloud infrastructure background.
*(T)* I needed to get comfortable with EC2, IAM, S3, VPC, and CloudFormation within a few months
in order to pass the AWS Certified Cloud Practitioner exam and complete hands-on labs.
*(A)* I built a daily practice routine — working through labs, using the AWS CLI directly instead
of only the console, and troubleshooting failed deployments on my own before asking for help.
*(R)* I passed the certification and was able to apply that same cloud comfort almost immediately
in my current DevOps role, where I deploy containerized applications to production servers.

**3. "Tell me about a time you worked on a team, and there was disagreement or a challenge."**
*(S)* On the FlowGuard team, we had four people covering different layers — data, dashboards, AI,
and analytics — and early on it wasn't always clear where one person's work ended and another's began.
*(T)* As the data engineer, I needed our data model to be something the AI engineer and the
dashboard analyst could both build on without constantly reworking it.
*(A)* I proposed we agree on the core data contracts (like what a "prediction" or "intervention"
record looked like) before building further, and documented them so everyone was working from the
same source of truth.
*(R)* This cut down on rework later in the project and meant the dashboards and the optimization
model were pulling from consistent, reliable data by the time we demoed the platform.

**4. "Tell me about a mistake you made and what you learned."**
*(S)* Early in the Cyber Shujaa program, I once moved straight into building a model on a dataset
without spending enough time on data cleaning.
*(T)* I needed to produce a reliable analysis, but the results looked inconsistent.
*(A)* I went back, did a proper exploratory data analysis pass, found missing values and outliers
I'd skipped past, and cleaned the data before rebuilding the model.
*(R)* The corrected results were far more consistent, and it taught me to always treat data
cleaning and EDA as a required first step, not something to rush through — a habit I still apply.

**5. "Why are you interested in this role?" / "Why should we hire you?"**
Tailor this one to the specific company, but the throughline for Deborah: an engineering
background that makes her comfortable with technical systems, real hands-on DevOps and cloud
experience, and recent applied data/AI project work — someone who can sit close to both the data
and the infrastructure that delivers it.

---

## Technical / role-specific questions to expect

- "Walk me through how you'd clean a messy dataset before analysis."
- "What's the difference between a container and a virtual machine?" (relevant given her Docker experience)
- "How would you explain a data insight to someone non-technical?" (tie back to writing the FlowGuard
  business case for a CFO/board audience)
- "What tools have you used for data visualization, and when would you choose Power BI vs. Tableau?"

## Tips for the recording

- Keep answers to 60–90 seconds each — long enough to show depth, short enough to hold attention.
- Say the numbers slowly and clearly (46/50, 87 to 56 minutes, KES 14.82M) — specific numbers build credibility.
- It's fine to pause and think before answering; better than rushing into a weak answer.
- End answers with the result/impact, not just the action — interviewers remember outcomes.
