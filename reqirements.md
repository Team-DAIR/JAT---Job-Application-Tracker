# Software Requirements

## Vision

This website will supply users with an easy-to-use interface to help them keep track of their job search in a detailed and organized way, help with motivation, and give some helpful resources for the job seeker.
This will solve the pain point of keeping track of job applications using only a google or excel spreadsheet. Tracking it this way is not visually pleasing, and more importantly, it's hard to visualize your success rate based on different factors.
It will not only help users be more organized in keeping track of their job applications, but it can also help them see what strategies and methods are more likely to lead them to a job offer, which can help them find a job faster the next time they're looking.

## Scope / Functional Requirements

#### - What this product will do (Minimum Viable Product):
  -   Users will be able to create an account where their job search data will be saved. They can login and logout.
  -   Users can add jobs they've applied for via a form. The data from the form inputs will be saved to a database.
  -   Users can update the jobs they've added to the database. Add points of contact, update status, add more info, etc.
  -   Home page will have a daily motivation to keep spirits up, and some testimonials of the website's users
  -   Users can see a dashboard with their job search data: list of jobs applied for and current status, graph showing how many jobs applied to on which days, etc.

#### - Stretch Goals:
  - Add a sections where users can see/add reviews about specific companies (either working there or the application/interview process)
  - Add a leaderboard section so users can see how many jobs other users have applied for/at which companies
  - Add an interactive message board where users can ask questions to other users and/or have discussions about best practices, etc.

#### - What this product will NOT do:
  - This will not be a mobile app

## Data Flow

![data flow](https://user-images.githubusercontent.com/107962287/219827460-835e4716-5211-45a2-a8da-feda103ba130.png)


## Non-Functional Requirements

**- Usability:**
  - First-time users should be able to understand what the website does, and how to use it.
**- Testability:**
  - Test the CRUD functionality by verifying information in the database based on user actions
  - Test that the daily affirmation is correctly rendering content from an API
  - Test that the sample job posting links render and function properly (as well as the video about best practices)
  - Test that data visualizations are displaying properly based on user's job search data
