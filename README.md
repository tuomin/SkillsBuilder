# Skills Builder
Final project for the Building AI course. 

## Summary

Skills Builder helps people develop their skills and competencies to retain their market value in the changing job market. Skills Builder is using publicly available skills data to track the most important skills for a defined job in a defined industry. SkillsBuilder will identify based on user input, what kind of skills are associated with the job based on job ads and publicly available skills inventories. Skills builder will also categorise them based on relevance and suggest development ideas.


## Background

With the rapid development of AI, skills landscapes are changing faster than ever. Old skills get to be irrelevant and new skills emerge. It is very difficult to try and manage this with static skills inventories. People need to get to the skills and required learning information faster and more effectively.

* Problem 1: Static skills inventories - The jobs ads give a more up-to-date picture of what the market demands for skills.
* Problem 2: People have difficulty naming or 'recognizing' skills - The skills from jobs ads are first cleaned and then complemented and checked against with public, recognised skills inventories to ensure logical categories and groupings. 
* Problem 3: People do not know how to develop the needed skills - Generative AI is used to suggest development actions.


## How is it used?

The SkillsBuilder solution can be used via an app or website. The logical point of starting the analysis is when preparing for development discussions and/or learning events. To keep the process clean, usable and simple, the user gives minimal entry to start the process. 

** Step 1 - define 'search'
input 1: "Target job" - what is the job that the user is currently holding or targeting for?
input 2: Industry (optional) - if the user wants to narrow the search and target for a specific industry (eg. pharmaceutical or technology)?
input 3: Country (optional) - if the user wants to narrow the search and target for a specific country (eg. Finland or UK or maybe Europe)?

** Step 2 - ML will search the live skills Skills Builder inventory and will come up with top 20 skills categorised using simplified, custom version of public skills inventories. The skills library continues to the live  in production phase but the output are continuously monitored for quality and consistency. User can select between selected prioritisation criteria (e.g. "Fortune 500", "Start-ups" etc.)

** Step 3 - From the long,  prioritised list of skills, the user will select the skills she wants to develop this time. Optionally, user can also give the time they have for learning so that the output is realistic within the given timeframe. 

** Step 4 - Generative AI will be used produce and draft action plan based on the selected skills. The user can iterate the plan using predefined toggles. 

## Data sources and AI methods 
Where does your data come from? 
* LinkedIn and other Job Postings (via web scraping or APIs like SerpApi, terms to be investigated)
* European Skills, Competences, Qualifications and Occupations (ESCO)
* O*NET database (US Department of Labor)
* Possibly Kaggle Datasets (based on licencing and validity of data)
  https://www.kaggle.com/datasets/niyamatalmass/google-job-skills
  https://www.kaggle.com/datasets/atahmasb/amazon-job-skills
  https://www.kaggle.com/datasets/asaniczka/1-3m-linkedin-jobs-and-skills-2024 


## Challenges

Data privacy might be an issue if people enter information about jobs that they want to transition to. If the SkillBuilder is used internally in a company, the user entries may need to be encrypted so that future desires are kept secret (if the user wants to do that). It does not yet solve these problems, but of course could be iterated to address:
* Capabilities and Goals - How to align invididual development to company goals and strategic needs
* Follow-up - How to ensure that the learning and skills development actually happens? What is the role of the Manager as a coach for development?
Which limitations and ethical considerations should be taken into account when deploying a solution like this?

## What next?

I would need developers who are competent in scraping and cleaning/manipulating data. I would also need to study the licencing models and how the SkillBuilder could be integrated into company HRIS and other software (including Data lakes and warehouses). I would need to data governance topics and continuous maintenance for production. I would need to understand the technical architecture and computational requirements for cost analysis. What would be the human-in-the-loop solution for something like this?


## Acknowledgments

* sources of inspiration: https://www.kaggle.com/datasets/asaniczka/1-3m-linkedin-jobs-and-skills-2024 

