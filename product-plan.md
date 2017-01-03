# Capstone Product Plan
The second deliverable for the capstone is your product plan.

## Product Plan Components
1. __Problem Statement__: I would like to build an app that will provide a registry of Adies and staff, a job board, and a company roster to facilitate the communication processes currently in place. 

1. __Market Research__: Outline the key insights from your research, including:  

  **Competitors:**  
  - Apps such as Tassl, Hivebrite, 360Alumni, and the ever-popular Almabase
  - These apps tend to handle functions such as job boards, mentor matching, email and social media integration, and analytics
  - They are known in their communities for their intuitive and elegant designs, ease-of-use, searchability, and accessibility  
  
  **Competitor Problems:**  
  - To get an alumni app with all the desired features, customer support, ease of use, and seamless integration, prepare to pay through the nose (Almabase seems to be leading in app satisfaction, but it also costs $3600 a year, which would drain money from a nonprofit like Ada)
  - Competitors like Hivebrite not only charge, but they don't have a single woman on their team, and that lack of diversity/missing perspective could negatively impact an app's UX and design (particularly for a school like Ada)  
  
  **How Lovelace Fits:**  
  - Lovelace would not only simplify Ada's internal communications and provide basic information for visitors, but it is written in a language shared by its alumni and instructors and features can be added to it as needed
  
1. __User Personas__: A summary of your main target user group(s). What are their key characteristics? How do those characteristics factor into project/app/idea?  

  **Target Users:**
  - Are digitally active, but range from digital native to late-adopter (the app should have a clean interface and be easy to use and streamlined)
  - Folks involved with Ada Developers Academy (the job board would be a good feature - students will be searching for work after graduating, and if Adies currently employed would like to put a heads-up out in order to get resumes then this would be a good place to put out feelers)
  - Range in age from 20s to 60s (the app should have a neutral color palate and should offer responsive design for viewing on a variety of devices from smartphone to desktop)
  - Identify as women, non-binary, and/or genderqueer (the app should have gender-neutral language and its tone must be inclusive and self-aware)
  - Staff work for a nonprofit and are managing heavy loads (the app should allow students to view past students' tech stacks for capstones, make initial contact with their mentors, and locate Adies who interned at companies they are curious about to take stress off of staff)  
  
1. __Trello Board__: [Lives Here](https://trello.com/b/aZiOHW9j/lovelace)  

  
1. __Technology selections__:  

  **Back-end**
  + [Ruby on Rails](http://rubyonrails.org/)
  + [AWS](https://aws.amazon.com/) Web Server
  + [PostgreSQL](https://www.postgresql.org/) Database
  + Faker Gem (fake data for testing/seeding)
  + Paperclip Gem (image management)  

  **Front-end**
  + [React](https://facebook.github.io/react/) UI Library
  + [Foundation](https://foundation.zurb.com/) CSS Framework
  + [JavaScript](https://www.javascript.com/)
  + [jQuery](https://jquery.com/)
  + Kaminari Gem (pagination)  

  **Infrastructure**
  + [AWS](https://aws.amazon.com/websites/) Hosting
  + [Jenkins](https://jenkins.io/) Automated Build Deployment
  + [Sentry](https://sentry.io/welcome/) Real-time crash reporting  

  **Security**
  + [Let's Encrypt](https://letsencrypt.org/) TLS/SSL Certificate Authority
  + [Stormpath](https://stormpath.com/) User Management, Authorization, and OAuth 2.0
  + [Cloudsploit](https://cloudsploit.com/) Automated AWS Security & Configuration Monitoring
  + [Brakeman Gem](https://github.com/presidentbeef/brakeman) OR [Dawnscanner Gem](https://github.com/thesp0nge/dawnscanner) OS static analysis tool which checks RoR apps for security vulnerabilities
  
1. __Wireframes__: [Live Here](https://goo.gl/photos/hf4nV2WWU9GnW89L9)
