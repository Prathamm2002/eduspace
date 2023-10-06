<h1 align="center">
    EDUSPACE
</h1>

<h3 align="center">
Unlock a transformative learning experience with our platform, offering personalized training, adaptive assessments, real-time proctoring, a vibrant social learning community, video conferencing, gamification elements, course progress tracking, and personalized study schedules.
</h3>

<br>

# About

EduSpace is a web-based application built using the MERN (MongoDB, Express.js, React.js, Node.js) stack. We also aim to add Machine Learning Techniques in the future for personalized assesments to train students throrughly.

## Features

- **User Roles:** The system supports three user roles: Admin, Teacher, and Student. Each role has specific functionalities and access levels.

<!-- - **Admin Dashboard:** Administrators can add new students and teachers, create classes and subjects, manage user accounts, and oversee system settings. -->

- **Adaptive Assessments:** Bayesian KnowledgeTracing: Estimate the probability that a student has mastered a particular skill.

- **Attendance Tracking:** Teachers can easily take attendance for their classes, mark students as present or absent, and generate attendance reports.

- **Performance Assessment:** Teachers can assess students' performance by providing marks and feedback. Students can view their marks and track their progress over time.

- **Real Time Proctoring:** Use of Clustering Algorithms to track unusal mouse movements and Gaze Tracking to estimate the direction of gaze from eye images.

- **Data Visualization:** Students can visualize their performance data through interactive charts and tables, helping them understand their academic performance at a glance.

- **Social Learning Community:** Suggest relevant threads to users based on their discussions. Also, Development of Moderation Algorithmsto flag content.

- **Video Conferencing:** Web Real-Time Communication(WebRTC) used for establishing peer-to-peer connections and facilitating real-time audio and video sharing.

## Technologies Used

- Frontend: React.js, Material UI, Redux
- Backend: Node.js, Express.js
- Database: MongoDB
- Video Conferencing and Integration: WebRTC
- Proctoring : OpenCV(face recognition) & Gaze Tracking(Mouse Movements)
- Machine Learning : Python, Tensorflow

<br>

# Installation

```sh
git clone https://github.com/Yogndrr/MERN-School-Management-System.git
```
Open 2 terminals in separate windows/tabs.

Terminal 1: Setting Up Backend 
```sh
cd backend
npm install
npm start
```

Terminal 2: Setting Up Frontend
```sh
cd frontend
npm install
npm start
```
Now, navigate to `localhost:3000` in your browser. 
The Backend API will be running at `localhost:5000`.

<br>

# Deployment
* Render - server side
* Netlify - client side

