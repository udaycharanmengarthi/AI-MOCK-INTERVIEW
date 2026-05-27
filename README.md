# AI Mock Interview Platform

An AI-powered mock interview platform built using React, Node.js, Express, MongoDB, and Gemini API.

The platform helps users practice interviews by generating role-based interview questions from uploaded resumes and conducting an interactive interview experience.

---

## Features

- Resume upload
- Role-based interview generation
- Difficulty selection
- AI-generated interview questions
- Voice and text answer support
- Interactive interview flow
- Interview history tracking
- Authentication system

---

## Tech Stack

### Frontend
- React.js
- Vite
- CSS

### Backend
- Node.js
- Express.js
- MongoDB
- JWT Authentication

### APIs & Services
- Google Gemini API (AI-generated questions)
- Murf API (voice support)

---

## Project Structure

```txt
AI-MOCK-INTERVIEW/
│
├── client/     # Frontend
├── server/     # Backend
│
└── README.md
```

---

## Installation

### 1. Clone Repository

```bash
git clone https://github.com/udaycharanmengarthi/AI-MOCK-INTERVIEW.git
```

### 2. Move into project

```bash
cd AI-MOCK-INTERVIEW
```

---

## Install Dependencies

### Frontend

```bash
cd client
npm install
```

### Backend

```bash
cd ../server
npm install
```

---

## Environment Variables

Create a `.env` file inside the `server` folder.

Example:

```env
PORT=5000

MONGODB_URI=your_mongodb_connection_string

JWT_SECRET=your_secret_key
JWT_EXPIRES_IN=7d

GEMINI_API_KEY=your_google_gemini_api_key

MURF_API_KEY=your_murf_api_key

CLIENT_URL=http://localhost:5173
```

---

## API Setup

### 1. Google Gemini API

1. Visit:

```txt
https://aistudio.google.com/apikey
```

2. Create an API key

3. Add it to `.env`

```env
GEMINI_API_KEY=your_api_key
```

---

### 2. Murf API

1. Visit:

```txt
https://murf.ai/
```

2. Create an account

3. Generate an API key

4. Add it to `.env`

```env
MURF_API_KEY=your_api_key
```

---

### 3. MongoDB Setup

1. Create a free MongoDB Atlas account

```txt
https://www.mongodb.com/cloud/atlas
```

2. Create a cluster

3. Create a database user

4. Whitelist IP address

5. Copy connection string

Add it to `.env`

```env
MONGODB_URI=your_connection_string
```

---

## Run the Project

### Start Backend

```bash
cd server
node server.js
```

### Start Frontend

```bash
cd client
npm run dev
```

---

## Local URLs

Frontend:

```txt
http://localhost:5173
```

Backend:

```txt
http://localhost:5000
```

---

## Future Improvements

- Better AI feedback system
- More interview categories
- Resume scoring
- Improved UI/UX
- Analytics dashboard

---

## Author

**Uday Charan Mengarthi**
