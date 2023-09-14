# Workterm Report 3
**By:** *Connor Schulz* <br>
**Last Updated *(yyyy/mm/dd)*:**   *2023/09/13*

<br>

## 📌 Abstract

This report will outline the experience that I gained during my third co-op work term (second at System1). This report will provide context to the reader about the employer and job, and present my goals with the steps I took in order to achieve them. 

<br>

## ℹ️ Employer Info

During this work term, I was employed by System1, the company behind the most dynamic Responsive Acquisition Marketing Platform. They are easily recognized by the well-known brands that they own, such as:
- [Startpage](https://www.startpage.com/) 
- [Answers.com](https://www.answers.com/)
- [Info.com](https://info.com/)
- [CouponFollow](https://couponfollow.com/)
- [HowStuffWorks](https://www.howstuffworks.com/)
- [Mapquest](https://www.mapquest.com/)
- and [more](https://system1.com/what-we-do#brands)

They are a rapidly growing company with over 500 employees, spread out across 5 locations (including one in Guelph) and many more working remotely.

They also contribute to the computer science community by conducting and publishing research in data science as well as creating a variety of open-source software. 

<br>

## 🏆 Goals

The three goals that I chose for this work term were:

1. Learn CI/CD workflows to improve the Jenkins build, deploy, and test jobs. <br>

   The motivation behind this goal stemmed from a small period between projects that provided my team time to tackle adhoc tasks. Choosing this as a goal in junction with volunteering to take on the task allowed me to learn experience with Jenkins, Docker, and Groovy all at once. This is both extremely challenging to do in a short period of time, making it a strong work-term goal. 

   I began with taking a smaller task to stream-line my teams release pipeline into a single job. This small task allowed me to gain the basics with Groovy scripting and Jenkins configuration. The completion of which, provided me with the foundation to take on the larger task of automating lighthouse audits.

   To accomplish lighthouse, I had to create a NodeJS script that called the API. once I had this working locally, I had to dockerize it and create a Jenkins job to run it. This was a challenge as I had never worked with Docker before, but I was able to learn the basics and get it working. In extension to this, I added a call to our AWS SNS which routed the results of the audit to our Slack channel. This was also a great learning opportunity as it was my first experience implementing AWS services into a project.

   Overall, this goal was a success. Not only did I improve the CI/CD workflows, but I gained a ton of exposure to new technologies in the process.

   <br>

2. Gain familiarity with React to contribute to the front end. <br>

   At the start of my work term, my team was wrapping up a project that required a lot of frontend work to be completed. As the frontend was written in React, I had to quickly learn the framework in order to effectively contribute.

   In my first week I was already able to carry on small tasks to completion. This was a great start to grasping the basics of React. As the first couple weeks went by, I was taking on larger tasks, and was becoming a stronger contributor.

   At the end of this project, I had become so familiar that I was finding strange bugs on top of my regular tasks. I also made some suggestions to the designer on changes that would improve the user experience which ended up making it into the final product.

   The confidence, accuracy, and efficiency of my React work by the end of the project is evident that this goal was a massive success. 
   
   <br>

3. Improve metrics tracking and graphing. <br>

   This goal was chosen as it was another great opportunity to learn something completely new while providing an extremely valuable service to the company. Luckily, I was able to take on this type of work multiple times over the term. 
   
   One of my tasks was to create a Grafana dashboard to track basic metrics on a new project that the team had started. This was my first time working with Grafana. I had to be careful while configuring the dashboard to ensure that the presented data was accurate and meaningful. Through careful research into the tool and great suggestions from colleagues, I was able to create and optimize a dashboard that was both visually appealing and informative.


<br>

## 📃 Job Description

For this term I worked in System1's innovation team, which is responsible for researching and developing innovative ideas. Over the term, I worked on a variety of projects, including:
- Improving the CI/CD pipeline
- Working on a React frontend for a website
- Creating multiple metrics dashboards
- Automating lighthouse tests on releases
- Refactoring a monolithic application into microservices


As the team switched projects frequently, I was able to gain experience with a variety of technologies and learn new skills quickly. Some new technologies that I learned were:
- React
- Docker
- Grafana
- Lighthouse API
- Groovy
- AWS SNS + Lambda

<br>

## 🏁 Conclusions

Overall, my second term at System1 was beyond successful. I was able to expand my horizons by learning new technologies and taking on fresh challenges. The constant support and guidance from my entire team allowed me to solve complex problems that I would have never thought I was capable of prior to this past May.

I was able to achieve all of my goals, take on new responsibilities, and gain confidence in my ability to contribute and participate in a professional environment.

I currently am working part-time while i'm in school where I hope to continue to learn and grow as a developer and plan on returning to System1 for my next co-op term.

<br>

## 💌 Acknowledgments

I would like to praise my entire team for supporting me through all the new challenges and learning experiences that I faced this term. I would also like to thank my manager for allowing me to expand the variety of work that I did and for helping me grow as a developer.

Beyond the scope of my team, I'd like to express gratitude toward my office manager and the rest of the Guelph office for making the work environment fun, friendly, and welcoming.
