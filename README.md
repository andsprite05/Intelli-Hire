# Intelli-Hire
Intelli-Hire as a project I made at Harvard Summer School as part of the course CSCI-14A: Web Applications/Data Analysis.

The inspiration for this project stemmed when I noticed that my mother would have difficulty hiring reliable and experienced candidates for her startup. I saw an opportunity to apply my recently gained skills to help my mother. I took the guidance of my professors at Harvard to create a web application that would interview candidates and help recruiters select the most suitable contenders for a job based on an AI algorithm. I deployed the first prototype of this application in my mother’s company and was thrilled when she found it to be a useful tool in her hiring process.

This prototype is just the beginning of many additions that I have planned to incorporate into our project. First I am going to add a feedback portion for the applicants that either did not pass the skills test or did not get chosen for the job. I want to partner with non-profits that provide courses and lessons for each of the candidates to expand their knowledge. I will also create a data visualization based upon the popularity of the job offerings and how many applicants there are, for the recruiters to view. This will help the recruiters know what they need to do to grasp the attention of more applicants and help Intelli-Hire manage the amount of eligible applicants for the job. It will ultimately lead to a list of the top applicants to choose. Later on I want to expand this application into a social media platform in order for the candidates to communicate with each other and help each other through the process.

# THE PROBLEM
Finding good talent is not an easy task - recruiters have to sift through hundreds of resumes, profiles, and meet with dozens of candidates before a good hire is made.

# MY SOLUTION
With Intelli-Hire, I am turning hiring into an automated process where candidate selection is done with the least amount of effort by the recruiter. Intelli-HIre will save time, find the best candidate, and provide feedback to those who do not make the cut so that they can be more prepared for future roles they apply to.

Recruiters are able to post new job requirements and customize the criteria for candidate selection to their needs. The Intelli-Hire system provides a base template with sample interview questions. The recruiter is able to reach all candidates applying for the job through Intelli-Hire and receives a ranked list of candidates best suited for the job based on interview results. Intelli-Hire also provides visualisations to show the recruiter the applicant pool and other statistics regarding candidate performance in the screening process.

Candidates are able to create a user profile to showcase their work experience and history to recruiters and fellow candidates. They are also able to view and apply to job postings where they will be provided a set of interview questions from the recruiter to fill out and submit. They are ranked for the job and receive custom feedback on areas to improve based on their interview answers.

Interview process starts with a basic assessment to qualify the candidate along to the next step of the process. All candidates have to pass the basic assessment with a score of 70% or higher. 
2nd round is the skills test where Intelli-Hire tests the candidate in skills needed for the job. This test is based on technical skills as well as interpersonal skills. All candidates need to pass this test with a score of 60% or higher to qualify for the last round. 
Last round is a job-specific interview where the questions are provided by the recruiter. These are open ended question answers according to what the recruiter entered into the application. All candidates who made it to this round are judged according to the keywords they used in their answers and the system will rank them accordingly. The recruiter will be provided with the answers and the system ranking to make an informed decision. All tests will be timed and monitored using video and browser activity.

# DATA MODEL
![image](https://github.com/user-attachments/assets/e0d58de0-e636-4f41-954b-eb1f097dec6b)

# BACKEND ARCHITECTURE
Intelli-Hire has a complex backend architecture in order to ensure that it has matched the best jobs to each candidate and recommended the top applicants to each employer. I had to gather data from the web based upon what resumes are fit for each job through machine learning in order to find the commonalities and create a decision tree to ensure that the hiring process is more accurate throughout time. As well as making the hiring process easier for companies, Intelli-Hire is able to provide feedback to the applicants based upon their skills. During the application process, each of the candidates will take a skill test based upon the skills they need to know for the job. Through the data that is gathered in their responses, Intelli-Hire can match each of the applicants that do not make the cut with a certain course or curriculum that can benefit them in the future. 

# DEMO
https://drive.google.com/file/d/1JwDxZ3boKHaY9ZqnDRk-p0406dai5oFw/view?usp=drive_link
