# AI Chat Platform

A production-ready AI chatbot built with Next.js, Vercel AI SDK, PostgreSQL, and Auth.js.

The platform supports conversational AI, authentication, file uploads, persistent chat history, and streaming responses.

---

## Features

### Authentication

- User registration
- Login
- Guest sessions
- Secure authentication

### Conversational AI

- Streaming responses
- Multi-session chat history
- Persistent conversations

### File Uploads

- Upload documents
- Store files securely
- Associate files with conversations

### Data Persistence

- PostgreSQL database
- Drizzle ORM
- Chat history storage

### Modern UI

- Responsive design
- Real-time updates
- Dark mode support

---

## Architecture

```text
User
 │
 ▼
Next.js Frontend
 │
 ▼
API Routes
 │
 ▼
Vercel AI SDK
 │
 ▼
LLM Provider
 │
 ▼
Streaming Response
 │
 ▼
PostgreSQL
```

## Tech Stack

- Next.js 15
- React 19
- Vercel AI SDK
- Auth.js
- PostgreSQL
- Drizzle ORM
- Vercel Blob
