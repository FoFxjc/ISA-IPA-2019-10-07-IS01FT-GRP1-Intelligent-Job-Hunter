# ISA-IPA-2019-10-07-IS01FT-GRP1-Intelligent-Job-Hunter
## SECTION 1 : PROJECT TITLE
## Intelligent Job Hunter - INTELLIGENT SOFTWARE AGENTS 

<div align=center>
<img src="Miscellaneous/logo.png"
     style="" />
</div>


---
## SECTION 2 : EXECUTIVE SUMMARY / PAPER ABSTRACT

Recently, every student in our institute of systems science has been shuttling between various interviews in order to find a good internship. Not only ISS students, almost everyone’s life will definitely experience the job hunting, especially near the period of graduation. According to the survey, as of 2016, the number of recent graduates in Singapore has reached 8 million. But it is undeniable that the entire job search process is very cumbersome, the process of scanning through multiple job postings to find relevant ones is time-consuming enough, let alone to write cover letters manually respectively for different job positions.

Although there are many cover letter generators already, but on the one hand, they only focus on the format of the resume and cover letter without content which need be typed in by customers own, on the other hand, they ignore the process of selection jobs before cover letter generation things and the process of job application after generations. Our team, consists of 4 ISS students, want to build an agent which can help us do the whole working flow of finding a job.

The system is the Intelligent Job Hunter (IJH). After the user registers with our system and uploads their personal information and existing resumes, our system will firstly extract the information from the existing resumes and save them into database for the comparation purpose in the next stage. In every wee hours of the morning, our system will automatically collect all of the job positions through email, compare those job positions to the information extracted before and select out those job positions that are suitable for the user and generate cover letters for all suitable positions respectively. In the morning, after these processes are completed, our system will send the selected job positions to user through WeChat, user can not only just select the job they want to apply in WeChat, but also can go to our website to check the cover letter generated and modify them. Then after user confirmed, our system will send emails to the hiring manager automatically.

To build the Intelligent Job Hunter, we designed a hybrid solution combining the web application and chatbot, using the Vue.js, Flask, WeChat Subscription, TagUI and Natural Language Process.

In this project, our team applied the knowledge and techniques acquired from the lectures and workshops into the reality business application scenario, and we would recommend our Intelligent Job Hunter to every student in our institute, hoping it can help them improve the job finding efficiency and quality, help them to find a better job



---
## SECTION 3 : CREDITS / PROJECT CONTRIBUTION

| Official Full Name  | Student ID (MTech Applicable)  | Work Items (Who Did What) | Email (Optional) |
| :------------ |:---------------:| :-----| :-----|
| LI XINLIN | A0198535N | Application Architect, RPA Development and Backend Development, Documentation, Video| e0402076@u.nus.edu |
| XU JIACHEN | A0198491M | Application Architect, Application Frontend and Backend Development, Documentation| e0402032@u.nus.edu |
| ZHANG ZHILIN | A0198519L | Application Architect, Chatbot and Backend Development, Documentation| e0402060@u.nus.edu |
| NRMALENDU PRAKASH | A0198447L | Application Architect,NLP Engine Development, Documentation| e0401988@u.nus.edu |

---
## SECTION 4 : VIDEO OF SYSTEM MODELLING & USE CASE DEMO
[![Watch the video](http://img.youtube.com/vi/PAedEATYn1E/0.jpg)](https://youtu.be/PAedEATYn1E)

---
## SECTION 5 : USER GUIDE


`<Github File Link>` : https://github.com/FoFxjc/ISA-IPA-2019-10-07-IS01FT-GRP1-Intelligent-Job-Hunter/blob/master/UserGuide/IJH_User_Guide.pdf

---
## SECTION 6 : PROJECT REPORT / PAPER

`<Github File Link>` : https://github.com/FoFxjc/ISA-IPA-2019-10-07-IS01FT-GRP1-Intelligent-Job-Hunter/blob/master/ProjectReport/ISA-CA-Project-Report.pdf

**Recommended Sections for Project Report / Paper:**
- Executive Summary
- Problem Description (Background Description and Business Analysis)
- Solution(System Architecture and Implementation)
- Conclusion(challenge and Overvome)

---
## SECTION 7 : Dataset Creation

`<Github File Link>` : https://github.com/FoFxjc/ISA-IPA-2019-10-07-IS01FT-GRP1-Intelligent-Job-Hunter/blob/master/System%20Codes/dataset_creation.zip

This script creates dataset of applicant work experiences  and job role and responsibility.

Place job_type.json and scrape_job_resume.py in a folder.

Navigate to this folder and run following command:

python scrape_job_resume.py

## SECTION 8 : MISCELLANEOUS

### logo.png
### Sample Cover Letter.pdf
### Sample Resume.pdf
