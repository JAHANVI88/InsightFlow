# 🚀 InsightGlow AI



> AI-Enhanced Real-Time Collaborative Workspace Platform



![Next.js](https://img.shields.io/badge/Next.js-15-black)

![TypeScript](https://img.shields.io/badge/TypeScript-blue)

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-Database-blue)

![Gemini](https://img.shields.io/badge/Gemini-AI-orange)



## 📖 Overview



InsightGlow AI is a real-time collaborative workspace designed for teams to create, edit, and manage documents while leveraging Generative AI assistance.



The platform combines live collaboration, team workspaces, AI-powered writing assistance, cloud storage, and role-based access control into a single productivity ecosystem.



---



## ✨ Features



### 🤝 Real-Time Collaboration

- Multi-user document editing

- Live cursors

- Presence indicators

- Instant synchronization



### 💬 Collaboration Tools

- Comments

- Mentions

- Activity Tracking

- Team Discussions



### 🤖 AI Writing Assistant

- Content Generation

- Document Summarization

- Grammar Correction

- Content Rewriting



### 🔐 Security & Access Control

- Role-Based Access Control (RBAC)

- Workspace Permissions

- Secure Authentication



### ☁️ Cloud Storage

- AWS S3 Integration

- File Upload & Sharing

- Secure Document Storage



### 📜 Version Management

- Version History

- Change Tracking

- Restore Previous Versions



---



## 🛠 Tech Stack



### Frontend

- Next.js

- React.js

- TypeScript

- Tailwind CSS



### Backend

- Next.js API Routes

- Node.js



### Database

- PostgreSQL

- Prisma ORM



### Real-Time Infrastructure

- Liveblocks



### Authentication

- Clerk



### AI

- Google Gemini API



### Cloud

- AWS S3

- Vercel



---



## 🏗 Architecture



```text

User

 │

 ▼

Next.js Frontend

 │

 ▼

Liveblocks WebSocket Layer

 │

 ▼

Real-Time Collaboration

 │

 ├── Comments

 ├── Mentions

 ├── Presence

 └── Synchronization

 │

 ▼

Gemini AI Assistant

 │

 ▼

Document Processing

 │

 ▼

PostgreSQL + Prisma

 │

 ▼

AWS S3 Storage

```



---



## 🚀 Getting Started



### Clone Repository



```bash

git clone https://github.com/JAHANVI88/insightglow-ai.git

cd insightglow-ai

```



### Install Dependencies



```bash

npm install

```



### Configure Environment Variables



```env

DATABASE_URL=

NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=

CLERK_SECRET_KEY=

GEMINI_API_KEY=

AWS_ACCESS_KEY=

AWS_SECRET_KEY=

AWS_BUCKET_NAME=

LIVEBLOCKS_SECRET_KEY=

```



### Run Development Server



```bash

npm run dev

```



---



## 📂 Project Structure



```text

InsightGlow-AI

│

├── app

├── components

├── hooks

├── lib

├── prisma

├── middleware

├── public

├── services

├── utils

└── types

```



---



## 🔮 Future Enhancements



- AI Meeting Notes Generator

- Collaborative Whiteboard

- Enterprise SSO

- Voice Commands

- AI Knowledge Base

- Real-Time Translation



---



## 📈 Resume Impact



- Built a real-time collaborative workspace using Liveblocks.

- Implemented RBAC and secure authorization workflows.

- Integrated Gemini AI for content generation and summarization.

- Developed cloud storage infrastructure with AWS S3.

- Engineered scalable multi-user collaboration features.



---



## 👩‍💻 Author



**Jahanvi Bagjani**



- LinkedIn: https://linkedin.com/in/jahanvi-bagjani-400390314

- GitHub: https://github.com/JAHANVI88



⭐ Star this repository
