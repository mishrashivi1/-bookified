📚 AI Book Companion

Voice-first AI platform that lets users have real-time conversations with their books using advanced speech synthesis and conversational AI.


✨ Overview

AI Book Companion is a full-stack web application that transforms PDF books into interactive, voice-enabled AI experiences.

Users can:

Upload books

Chat with them using real-time voice

Choose different AI voice personas

Generate summaries

View conversation transcripts

Manage their personal digital library

This project demonstrates modern full-stack architecture using real-time voice AI, vector embeddings, authentication, and scalable database design.

⚙️ Tech Stack

Frontend: Next.js 16, TypeScript, Tailwind CSS, Shadcn UI

Authentication: Clerk

Database: MongoDB + Mongoose

Voice AI Engine: Vapi

Text-to-Speech: ElevenLabs

Embeddings: Google Gemini API

Storage: Vercel Blob

Code Quality: CodeRabbit

🔥 Key Features
📄 PDF Upload & Processing

Extracts text from PDFs

Smart chunking for contextual retrieval

Embedding-based semantic search

🎙️ Real-Time Voice Conversations

Natural back-and-forth voice interaction

Low latency via Vapi

Human-like speech using ElevenLabs

🎭 AI Voice Personas

Multiple voice personalities

High-quality voice previews

🧠 Smart Summaries

Chapter-level summaries

Concept explanation on demand

📝 Auto-Generated Transcripts

Full conversation logs

Stored securely per user

📚 Library Management

Personal dashboard

Search & organize uploaded books

🔐 Authentication & Access Control

Secure login with Clerk

Protected routes

Scalable user management

🏗️ System Architecture

User uploads PDF

Text is extracted and chunked

Embeddings are generated using Gemini

Stored in MongoDB

During conversation:

Query is matched with relevant chunks

Context passed to AI

Voice response generated via Vapi + ElevenLabs

Transcript stored in database

🛠️ Installation & Setup
Prerequisites

Node.js

npm

MongoDB account

Clerk account

Vapi account

ElevenLabs API key

Google Gemini API key

Clone Repository
git clone url
cd ai-book-companion
Install Dependencies
npm install
Environment Variables

Create a .env file in the root directory:

NODE_ENV=development
NEXT_PUBLIC_BASE_URL=

# Clerk
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
CLERK_SECRET_KEY=

# MongoDB
MONGODB_URI=

# Vapi
NEXT_PUBLIC_VAPI_API_KEY=
VAPI_SERVER_SECRET=

# Google Gemini
GOOGLE_GEMINI_API_KEY=

# ElevenLabs
ELEVENLABS_API_KEY=

# Vercel Blob
BLOB_READ_WRITE_TOKEN=
Run Development Server
npm run dev

Open:

http://localhost:3000
📈 What This Project Demonstrates

Real-time AI integration

Voice-based UX architecture

Full-stack Next.js application design

Secure authentication flows

Scalable NoSQL database structure

Clean, reusable component architecture

🧠 Learning Outcomes

While building this project, I gained hands-on experience with:

Voice AI pipelines

Embedding-based retrieval systems

Production-grade authentication

Real-time API integrations

Modern UI component systems

🛡️ Future Improvements

Multi-language voice support

RAG optimization

Book recommendation engine

Subscription-based premium tier

Analytics dashboard


