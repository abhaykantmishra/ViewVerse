# 🎥 Short Video Sharing & Streaming Platform

A full-stack short video sharing and streaming platform inspired by modern social video apps. Users can upload, stream, like, comment, and save short videos for later. Built for performance, scalability, and a seamless user experience.

---

## 🚀 Features

- 📤 Upload Short Videos  
- 🎬 Watch Videos Seamlessly  
- ❤️ Like & 💬 Comment on Videos  
- 💾 Save Videos for Later  
- 🔐 Secure JWT-Based Authentication  
- 👤 User Profile Creation & Editing  
- 📁 Cloud Storage Integration (Cloudinary)  
- 🧾 RESTful API Architecture  
- 🧹 Modern, Responsive UI with TailwindCSS  

---

## 🧩 Tech Stack & Why It Was Used

### 🔧 Frontend

| Tech         | Description |
|--------------|-------------|
| **React.js** | Used for building the user interface using component-based architecture. Offers a fast and interactive user experience. |
| **Vite**     | A blazing-fast frontend build tool that drastically reduces development server startup time and provides optimized builds. |
| **TailwindCSS** | Utility-first CSS framework used to design responsive and modern interfaces quickly without writing custom CSS. |

### ⚙️ Backend

| Tech         | Description |
|--------------|-------------|
| **Node.js** | A JavaScript runtime used for building fast, scalable backend services. |
| **Express.js** | Lightweight web framework for Node.js, used to create the REST API endpoints efficiently. |
| **MongoDB** | NoSQL database used to store users, videos, comments, likes, etc., making it easier to handle unstructured video-related data. |
| **Mongoose** | ODM (Object Data Modeling) library that simplifies interaction with MongoDB through schemas and models. |
| **JWT (JSON Web Tokens)** | Used for stateless authentication. It securely transmits user identity between frontend and backend. |
| **Bcrypt.js** | Used to hash passwords before storing them in the database, enhancing user security. |
| **Cloudinary** | Cloud-based image and video storage solution used to handle heavy media content offloaded from the server. |
| **Multer** | Middleware for handling `multipart/form-data`, especially for video file uploads. Ensures secure and optimized file handling. |

---

## 📁 Folder Structure

├── frontend/ # React.js + Vite + Tailwind

└── backend/         # Node.js + Express + MongoDB

---

##  Architecture diagram

![arch dia](https://www.mermaidchart.com/raw/39bfb2aa-d482-45c6-8a84-97578d8fdcc0?theme=light&version=v0.1&format=svg)

---


## 🎯 Future Roadmap
- 🔔 Real-Time Notifications

- 📊 Analytics Dashboard for Creators

- 🧵 Threads / Replies on Comments

- 🌍 Explore Page Based on Location/Interests

- 📱 Mobile PWA Support

## 🤝 Contributing
```bash
Have an idea to improve the platform? Open an issue or submit a pull request. All contributions are welcome!
```
