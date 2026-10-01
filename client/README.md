# Project Name

> An AI-powered full-stack web app that lets signed-in users generate content with AI, save it to their personal library, and optionally publish it for others to see and like.



## Features

- User authentication and account management with **Clerk**
- AI text generation powered by **Google Gemini**
- AI image generation and editing via **Clipdrop**
- Image upload and hosting with **Cloudinary**
- Serverless PostgreSQL storage with **Neon**
- Personal library of saved creations
- Publish creations publicly and like other users' work

## Tech Stack

| Layer          | Technology                     |
| -------------- | ------------------------------ |
| Frontend       | Node.js, npm (Vite dev server) |
| Backend        | Node.js                        |
| Database       | Neon (PostgreSQL)              |
| Authentication | Clerk                          |
| AI services    | Google Gemini API, Clipdrop API |
| Media storage  | Cloudinary                     |

## Project Structure

```
.
├── client/    # Frontend application
└── server/    # Backend API
```

## Prerequisites

- [Node.js](https://nodejs.org/en/download/) (includes npm)
- A code editor such as [VS Code](https://code.visualstudio.com/)
- Free accounts for each of the services below

## Getting Started

> **Important:** Always start the **server first**, then the **client**.

### 1. Set up external services

Create an account and get your keys from each of the following:

| Service    | Purpose                | Link                                       |
| ---------- | ---------------------- | ------------------------------------------ |
| Neon       | PostgreSQL database    | https://neon.com                           |
| Cloudinary | Image storage          | https://cloudinary.com/users/register_free |
| Clerk      | Authentication         | https://clerk.com/                         |
| Clipdrop   | AI image API           | https://clipdrop.co/apis                   |
| Gemini     | AI text/generation API | https://aistudio.google.com/apikey         |

### 2. Run the server

1. Open the project folder in VS Code.
2. Open the `server` folder in the integrated terminal.
3. Add the required environment variables for the server.
4. Install dependencies:

   ```bash
   npm install
   ```

5. Start the server:

   ```bash
   npm run server
   ```

### 3. Run the client

Make sure the server is running first.

1. Open the `client` folder in the integrated terminal.
2. Add the required environment variables for the client.
3. Install dependencies:

   ```bash
   npm install
   ```

4. Start the development server:

   ```bash
   npm run dev
   ```

