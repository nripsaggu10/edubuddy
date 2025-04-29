# 🎓 EduBuddy – AI Mentor & Planner for Online Learners

EduBuddy is your personal AI-powered assistant to help you stay on track with online learning. Whether you're taking a course on platforms like Coursera, Udemy, or YouTube, EduBuddy generates a personalized study plan, resolves your doubts with AI, quizzes you from video transcripts, and connects you with peers for accountability. It's designed to enhance the self-learning experience by leveraging AI and smart scheduling.

---

## 🚀 Features

- 🗓️ **Smart Scheduler**  
  Automatically generates a weekly study plan based on your course content and your availability. It takes into account your workload, preferred study hours, and course duration to offer a tailored schedule.
  
- 🤖 **AI Tutor**  
  Ask any questions you have during your course, and EduBuddy will explain concepts using OpenAI’s GPT model combined with YouTube transcripts or course content.

- 🧠 **Quiz Generator**  
  Upload a course video or transcript, and EduBuddy automatically generates multiple-choice questions (MCQs) for revision. It helps you to test your knowledge and prepare for exams or certifications.

- 👥 **Peer Matcher**  
  Connect with other learners studying similar topics or courses. EduBuddy matches you with study buddies who can provide support, motivation, and peer accountability.

- 📈 **Progress Tracker**  
  Track your course progress in real-time. EduBuddy provides weekly reports on what you’ve studied, your progress percentage, and keeps you on track to finish your course.

---

## 🛠 Tech Stack

### Frontend

- **React.js** – A JavaScript library for building user interfaces. It's fast, component-based, and ideal for a dynamic user experience.
- **TypeScript** – Supersets JavaScript with static typing, providing better maintainability and fewer runtime errors.
- **Tailwind CSS** – A utility-first CSS framework that provides a highly customizable, responsive design system.
- **Supabase Auth** – For managing user authentication and database interaction with real-time updates.

### Backend

- **Java** – The backend is powered by Java, known for its robustness, performance, and scalability.
- **Spring Boot** – A framework that simplifies the development of Java-based backend applications. It makes the setup and configuration of APIs fast and seamless.
- **RESTful APIs** – Used to handle course scheduling, peer matching, and tracking user progress. Each interaction with the frontend is done via RESTful endpoints.

### AI Microservices

- **Python** – Python powers the AI services due to its extensive libraries for machine learning and natural language processing.
- **FastAPI** – A modern, fast web framework for building APIs with Python. It's ideal for serving machine learning models in production.
- **LangChain** – Used for chaining AI tools and models together in a flexible way. It can easily integrate OpenAI’s GPT model with various external APIs and databases.
- **OpenAI API** – Provides access to GPT models that help in answering learner queries, generating explanations, and producing quiz questions.
- **YouTube Data API** – Fetches video metadata such as captions, video length, and video content. We use `yt-dlp` to extract captions from videos.
- **yt-dlp** – A command-line program to download videos and extract metadata from YouTube and other platforms. It’s essential for fetching video transcripts from educational content.

### Database

- **Supabase** – Provides an open-source alternative to Firebase, offering a PostgreSQL database with easy-to-use authentication and real-time data sync. It’s used for storing user information, course data, and user progress.

---
