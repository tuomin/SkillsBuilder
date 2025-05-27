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

** Step 2 - ML will come up with top 20 skills categorised using simplified, custom version of public skills inventories. The skills library continues to the live  in production phase but the output are continuously monitored for quality and consistency. User can select between selected prioritisation criteria (e.g. "Fortune 500", "Start-ups" etc.)

** Step 3 - From the long,  prioritised list of skills, the user will select the skills she wants to develop this time. Optionally, user can also give the time they have for learning so that the output is realistic within the given timeframe. 

** Step 4 - Generative AI will produce and draft action plan based on the selected skills. The user can iterate the plan using predefined toggles. 


```
def main():
   countries = ['Denmark', 'Finland', 'Iceland', 'Norway', 'Sweden']
   pop = [5615000, 5439000, 324000, 5080000, 9609000]   # not actually needed in this exercise...
   fishers = [1891, 2652, 3800, 11611, 1757]

   totPop = sum(pop)
   totFish = sum(fishers)

   # write your solution here

   for i in range(len(countries)):
      print("%s %.2f%%" % (countries[i], 100.0))    # current just prints 100%

main()
```


## Data sources and AI methods
Where does your data come from? Do you collect it yourself or do you use data collected by someone else?
If you need to use links, here's an example:
[Twitter API](https://developer.twitter.com/en/docs)

| Syntax      | Description |
| ----------- | ----------- |
| Header      | Title       |
| Paragraph   | Text        |

## Challenges

What does your project _not_ solve? Which limitations and ethical considerations should be taken into account when deploying a solution like this?

## What next?

How could your project grow and become something even more? What kind of skills, what kind of assistance would you  need to move on? 


## Acknowledgments

* sources of inspiration: https://www.kaggle.com/datasets/asaniczka/1-3m-linkedin-jobs-and-skills-2024 

