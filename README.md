# G-Scores

This is the instruction for web developer intern assignment at [Golden Owl](https://goldenowl.asia). You will build a simple web.

# Requirements
1. From the raw data file ([diem_thi_thpt_2024.csv](./dataset/diem_thi_thpt_2024.csv)) save it into the database with the appropriate structure

2. Your application should have at least features in [Must have](#must-have), things in [Nice to have](#nice-to-have) is optional (but yeah, it's attractive if you have).

### Must have:
- The conversion of raw data into the database must be coded and located in this source code. (**hint**: recommend use migration and seeder)
- Each subject will have 1 object.
- Write a feature to check score from registration number input
- Write a feature report
    -   There will be 4 levels including: >=8 points, 8 points > && >=6 points, 6 points > && >= 4 points, < 4 points
    -   Statistics of the number of students with scores in the above 4 levels by subjects.
    -   Find the top student of block A including (math, physics, chemistry)
### Nice to have:

- Responsive design (look good on all devices: desktops, tablets & mobile phones).
- Smooth animations (just do what you think is good).
- Setup project use Docker.
- Deploy the application to go live.

# Technical Requirements

### Frontend
You can use any front-end library/framework like React, Angular, Vue, ... or just simple things with HTML + CSS + Javascript (JQuery).
- Fonts (optional);
  - [https://fonts.google.com/specimen/Rubik?query=Rubik](https://fonts.google.com/specimen/Rubik?query=Rubik)
- You can use some available interfaces such as: AdminLTe, TailAdmin...
  
### Backend: 
Choose one of your applied back-end libraries/frameworks: Laravel(PHP), Ruby on Rail, NestJS (NodeJs), Django (Python), ... or a structure that you come up with yourselt. 
Need form validation and logic tightening.
- OOP programming for object-oriented languages
- For JS intern you need to have: 
  * Use TypeScript (Type, Interface, Omit, Partial...)
  * React Hooks (useState, useEffect, useCallback...)
- Use ORM for interacting with DB
- DB: You can use postgreSQL, Mysql, mongoDB... to manage or cache the data. 

### Deployment
Some providers allow free deployment for the trial version  (note: Maybe some suppliers will update their policies and prices)

- Heroku - https://heroku.com - Deploying Front & Backend
- Vercel (Zeit) - https://vercel.com - Deploying Front & Backend apps at free of cost
- Fly - https://fly.io - Deploying Front & Backend apps at free of cost
- Deta - https://deta.sh - Deploying Node.js and Python apps and APIs. They support most web frameworks like Express, Koa, Flask, and FastAPI. They also provide a very fast and powerful NoSQL database for free.
- Heliohost - https://heliohost.org - PHP, Ruby on rails, perl, django, java(jsp)
- `...`
# Submission

After completing the assignment, please push the source code to remote repository (github/gitlab), then send us the link to your repository.

Don't forget to add `README.md` which includes guide to run your project locally and demo link.


**GOOD LUCK!!!**

![Your Code Work](./screenshots/meme.png)

# Contributors

- Edric Cao (from GO)
