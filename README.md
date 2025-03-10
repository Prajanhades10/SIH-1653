# Smart India Hackathon Workshop
# Date:10/3/2025
## Register Number: 24009412
## Name:PRAJAN.SS
## Problem Title
SIH 1653: Web based Selector-Applicant Simulation Software
## Problem Description
Background: Recruitment and Assessment Centre (RAC) under DRDO, Ministry of Defence carries out interviews for applications received against advertised vacancies and for promotion to next higher grade for scientific manpower inducted within DRDO. Description: The process of interviewing is a challenging task. An unbiased objective interviewing process helps identify the right talent. The basic process of an interview involves posing a set of questions by an interviewer and thereafter evaluating responses from candidates. Thus, the questions asked should be relevant and match the area/ expertise of the applicant and the responses should also be of relevance w.r.t. the question asked. Expected Solution: The proposed solution should provide experts as well as candidates a real life Board Room experience, starting with initial ice-breaking questions leading to in-depth techno-managerial (depending on the level of candidate) questions. It shall also be able to provide a quantifiable score for experts as well as the candidate for the relevancy of questions w.r.t. the area/ expertise of the applicant. Similarly, candidate responses should also be graded for relevancy w.r.t. the question asked, finally assisting in arriving at an overall score for the subject knowledge of the candidate and thus his/ her suitability against the advertised post.

## Problem Creater's Organization
Ministry of Defence

## Idea/Key Features

### IDEA:  
Develop an **AI-driven Interview Simulation System** to enhance the recruitment and assessment process at DRDO's RAC. The system will simulate a real-life boardroom experience, provide quantifiable scoring for questions and responses, and assist in evaluating candidates' suitability for advertised posts.

## Key Features:  
- ### 1. Candidate Profiling:
-  Automatically extract and analyze candidate details (resume, expertise, skills) to tailor the interview process.  
- ### 2.Dynamic Question Bank:
-  A repository of categorized questions (ice-breaking, technical, managerial) tailored to the candidate's profile.  
- ### 3.Real-Time Interview Simulation:
-  A virtual boardroom environment with interactive questioning and follow-up dialogue.  
- ### 4.AI-Based Evaluation:
- Use NLP to assess the relevance and accuracy of candidate responses.  
- ### 5.Quantifiable Scoring:
-  Assign scores for technical accuracy, managerial competence, and communication skills.  
- ### 6.Feedback and Reporting:
-  Generate detailed reports and feedback for candidates and interviewers.  
- ### 7.Decision Support:
-  Provide an overall score to assist in the final selection process.  

---

## Proposed Solution / Architecture Diagram

**Proposed Solution**:  
The system will consist of the following modules:  
 ### 1.Candidate Profiling Module: Extracts and analyzes candidate data.  
 ### 2.Question Bank Module: Dynamically selects questions based on the candidate's profile.  
 ### 3.Interview Simulation Module: Conducts the interview in a virtual boardroom environment.  
 ### 4.Evaluation Module: Uses NLP to evaluate responses and assign scores.  
 ### 5.Reporting Module: Generates feedback and reports for candidates and interviewers.  

**Architecture Diagram**:  
```
+-------------------+       +-------------------+       +-------------------+  
| Candidate Profiling|       | Question Bank     |       | Interview Simulation|  
| Module             |       | Module            |       | Module             |  
+-------------------+       +-------------------+       +-------------------+  
          |                         |                         |  
          v                         v                         v  
+---------------------------------------------------------------+  
|                        AI-Driven Evaluation Module             |  
|                        (NLP-Based Scoring)                     |  
+---------------------------------------------------------------+  
          |  
          v  
+-------------------+  
| Reporting Module  |  
| (Feedback & Score)|  
+-------------------+  
```

---

##  Use Cases/Use Case Diagram

### Use Cases:  
### 1.Candidate:  
   - Upload resume and application details.  
   - Participate in the virtual interview.  
   - Receive feedback and score.  

 ### 2.Interviewer**:  
   - Review candidate profiles.  
   - Conduct interviews using the simulation system.  
   - Evaluate responses and finalize scores.  

 ### 3.Admin:  
   - Manage the question bank.  
   - Monitor system performance.  
   - Generate reports and analytics.  

## Use Case Diagram:  
```
+-------------------+       +-------------------+       +-------------------+  
|    Candidate      |       |   Interviewer     |       |      Admin        |  
+-------------------+       +-------------------+       +-------------------+  
          |                         |                         |  
          | Upload Resume           | Review Profile          | Manage Question Bank  
          | Participate in Interview| Conduct Interview       | Monitor System  
          | Receive Feedback        | Evaluate Responses      | Generate Reports  
          |                         |                         |  
+---------------------------------------------------------------+  
|                     AI-Driven Interview System                  |  
+---------------------------------------------------------------+  
```

---

## Technology Stack / Tech Stack Overview

### Frontend:  
- **Framework**: React.js or Angular for a responsive and interactive user interface.  
- **WebRTC**: For real-time video and audio communication during the interview.  

### Backend:  
- **Framework**: Node.js with Express.js for server-side logic.  
- **Database**: MongoDB or PostgreSQL for storing candidate profiles, questions, and evaluation data.  

### AI/ML:  
- **NLP Libraries**: spaCy, NLTK, or Hugging Face Transformers for response evaluation.  
- **Machine Learning**: Scikit-learn or TensorFlow for candidate profiling and scoring.  

### Cloud Infrastructure:  
- **Hosting**: AWS, Azure, or Google Cloud for scalable deployment.  
- **Storage**: Cloud storage for interview recordings and documents.  

### DevOps:  
- **CI/CD**: Jenkins or GitHub Actions for automated deployment.  
- **Containerization**: Docker and Kubernetes for managing microservices.  

---

## Dependencies

### Technical Dependencies:  
- **NLP Libraries**: Availability of pre-trained models for text analysis.  
- **WebRTC**: Stable and low-latency video/audio communication.  
- **Cloud Services**: Reliable cloud infrastructure for hosting and storage.  

### Non-Technical Dependencies:  
- **Data Privacy Compliance**: Adherence to data protection regulations (e.g., GDPR, CCPA).  
- **User Training**: Training for interviewers and candidates to use the system effectively.  
- **Stakeholder Buy-In**: Support from DRDO's RAC for implementation and adoption.  

### Third-Party Dependencies:  
- **APIs**: Integration with resume parsing APIs (e.g., Sovren, HireAbility).  
- **Authentication**: OAuth or SSO for secure login.  

---

This structured approach ensures a comprehensive and scalable solution to address the challenges faced by DRDO's RAC in conducting unbiased and efficient interviews.



