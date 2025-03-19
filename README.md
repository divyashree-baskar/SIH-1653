# Smart India Hackathon Workshop
# Date:19/03/2025
## Register Number:212224040081
## Name:Divyashree B
## Problem Title
SIH 1653: Web based Selector-Applicant Simulation Software
## Problem Description
Background: Recruitment and Assessment Centre (RAC) under DRDO, Ministry of Defence carries out interviews for applications received against advertised vacancies and for promotion to next higher grade for scientific manpower inducted within DRDO. Description: The process of interviewing is a challenging task. An unbiased objective interviewing process helps identify the right talent. The basic process of an interview involves posing a set of questions by an interviewer and thereafter evaluating responses from candidates. Thus, the questions asked should be relevant and match the area/ expertise of the applicant and the responses should also be of relevance w.r.t. the question asked. Expected Solution: The proposed solution should provide experts as well as candidates a real life Board Room experience, starting with initial ice-breaking questions leading to in-depth techno-managerial (depending on the level of candidate) questions. It shall also be able to provide a quantifiable score for experts as well as the candidate for the relevancy of questions w.r.t. the area/ expertise of the applicant. Similarly, candidate responses should also be graded for relevancy w.r.t. the question asked, finally assisting in arriving at an overall score for the subject knowledge of the candidate and thus his/ her suitability against the advertised post.

## Problem Creater's Organization
Ministry of Defence

## Idea
This project is a simple Web-Based Selector-Applicant Simulation Software built using Flask for the backend and HTML/CSS for the frontend. It allows applicants to submit their details, including name, qualification, and years of experience, while selectors can view the list of submitted applicants. The project consists of a Flask application (app.py), two HTML templates (index.html for applicant submission and applicants.html for viewing applicants), and a basic CSS file (style.css) for styling. The application stores applicant data in an in-memory list and displays it dynamically. It is easy to run locally by installing Flask, running python app.py, and accessing http://127.0.0.1:5000/ for submission or http://127.0.0.1:5000/applicants to view the applicants. This lightweight project is ideal for small-scale hiring simulations and can be expanded with additional features like resume uploads, ranking systems, and AI-based filtering. It is designed to be uploaded to GitHub as a simple, beginner-friendly demonstration of a selector-applicant workflow.


## Proposed Solution / Architecture Diagram
Steps to Implement the Solution:
1.Set Up Flask: Install Flask and create a simple server to handle form submissions.
2.Create an Applicant Form: A webpage where users can enter their name, qualification, and experience and submit the form.
3.Store Submitted Data: Use a Python list to temporarily store applicant details.
4.Display Applicant List: Create a selector dashboard where all submitted applications can be viewed.
5.Style the Pages: Apply basic CSS for better UI.
6.Run the Application: Start the Flask server and test the functionality locally.

## Use Cases
![image](https://github.com/user-attachments/assets/fdce8183-e397-4663-a4f7-1516d69d1239)



## Technology Stack
Frontend:
1.React.js / Vue.js / Angular (Dynamic UI)
2.TailwindCSS / MUI (Styling)
3.Socket.io / WebRTC (Real-time interactions)
Backend:
1.Node.js (Express) / Django / Spring Boot (Server)
2.PostgreSQL / MongoDB (Database)
3.OAuth 2.0 / JWT (Authentication)
AI & Simulation:
1.TensorFlow / OpenAI API (AI evaluation)
2.Three.js / Unity WebGL (3D interactions)
Deployment & DevOps:
1.AWS / Firebase / Vercel (Hosting)
2.Docker + Kubernetes (Scalability)
3.GitHub Actions / Jenkins (CI/CD)


## Dependencies
Frontend:
1.react / vue / angular – UI framework
2.tailwindcss / material-ui – Styling
3.redux / zustand / vuex – State management
4.socket.io-client / webrtc – Real-time interactions
Backend:
1.express / django / spring-boot – Server framework
2.jsonwebtoken (JWT) / passport – Authentication
3.socket.io / fastapi – Real-time updates
4.postgres / mongoose (MongoDB) – Database ORM
AI & Simulation:
1.tensorflow / pytorch – AI evaluation
2.openai / langchain – AI-based chatbot
3.three.js / babylon.js – 3D interactions
Deployment & DevOps:
1.docker / kubernetes – Containerization
2.vercel / firebase / aws-sdk – Hosting
3.github-actions / jenkins – CI/CD automation

