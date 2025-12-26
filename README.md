Online Quiz Website 🚀

A fully functional Online Quiz Web Application with separate Admin and User roles.  
Built using HTML, CSS, JavaScript and deployed on AWS (S3 + CloudFront + API Gateway + Lambda + DynamoDB).

---

## 🔗 Live Demo
👉 https://d3eikew7ssit3.cloudfront.net

## ✨ Features

### 👤 User
- User login (temporary email-based)
- Dashboard with quiz access
- Timed quiz interface
- Question navigation panel
- Auto-submit on time completion
- Result page with score calculation
- Result history stored locally

### 🛠️ Admin
- Admin login (temporary credentials)
- Add new quiz questions
- View all questions
- Delete questions
- Questions stored in DynamoDB

---
## 🧩 Project Structure
├── index.html # Role selection (Admin / User)
├── admin-dashboard.html # Admin panel
├── user-dashboard.html # User dashboard
├── quiz.html # Quiz interface
├── result.html # Result page

## 🏗️ Tech Stack

### Frontend
- HTML5
- CSS3
- Vanilla JavaScript

### Backend (Serverless)
- AWS API Gateway
- AWS Lambda (Node.js)
- AWS DynamoDB

### Hosting & CDN
- Amazon S3 (Static website hosting)
- Amazon CloudFront (Global CDN)

---

## 🔐 Authentication (Temporary)

### user
user@quiz.com


---

## 📦 Deployment Flow

1. Frontend hosted on **Amazon S3**
2. Content delivered via **CloudFront**
3. Quiz APIs handled by **API Gateway**
4. Business logic in **Lambda**
5. Data stored in **DynamoDB**

## 🚀 How to Run Locally

1. Download or clone the repository
2. Open `index.html` in a browser
3. Use the temporary credentials to explore Admin/User flows

## 🧠 Future Enhancements

- Real user authentication (AWS Cognito)
- Admin result analytics
- Leaderboard
- Mobile-first UI improvements
- Database-backed user history
- 
## 👨‍💻 Author

Nitin Kumar  
B.Tech (ECE)  
Cloud & Web Development Enthusiast
