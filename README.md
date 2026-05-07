# InterMetriq — AI-Powered Interview Platform 🎙️🧠

InterMetriq is a full-stack AI interview platform designed to help users practice technical and behavioral interviews through real-time voice conversations, AI-generated feedback, and structured coaching workflows.

The platform simulates mock interviews using voice AI and evaluates candidate responses across multiple dimensions including communication, technical reasoning, confidence, and problem-solving ability.

Built as an end-to-end portfolio project using Next.js, Firebase, Vapi AI, Google Gemini and Anthropic Claude SDK integrations.

---

## 🚀 Live Demo

[View Live Application](https://inter-metric-interview-platform.vercel.app)

---

# 📌 Core Features

## ✅ AI-Powered Voice Interviews

Uses Vapi AI to simulate realistic interview conversations with real-time voice interaction.

Features include:

- AI interviewer voice sessions
- Real-time conversation flow
- Voice-based interview experience
- Interview state handling and session control

---

## ✅ AI Feedback & Scoring

After each interview session, the platform generates structured feedback across multiple categories:

- Communication
- Technical Knowledge
- Problem Solving
- Cultural Fit
- Confidence

Users receive:

- Overall interview score
- Strength analysis
- Improvement recommendations
- Structured coaching feedback

---

## ✅ AI Job Coach

Integrated AI coaching workflows allow users to:

- Generate interview questions
- Practice role-specific interviews
- Receive tailored preparation guidance
- Review suggested sample answers

---

## ✅ Cover Letter Generator

Includes AI-assisted cover letter generation workflows for job applications.

---

## ✅ Authentication & User Management

Firebase Authentication handles:

- User sign up
- Secure login
- Session management

Firestore stores:

- Interview history
- Feedback records
- User-generated sessions
- Coaching workflows

---

## ✅ Responsive UI

Built with Tailwind CSS for:

- Mobile responsiveness
- Clean dashboard layouts
- Fast client-side interactions
- Structured user workflows

---

# 🛠️ Tech Stack

| Technology | Purpose |
|---|---|
| Next.js 15 | Frontend framework |
| TypeScript | Type-safe development |
| Firebase Authentication | User authentication |
| Cloud Firestore | Backend database |
| Tailwind CSS | UI styling |
| Vapi AI | Real-time voice AI interviews |
| Google Gemini 2.5 | AI generation workflows |
| Anthropic Claude SDK | Structured AI responses |
| Vercel | Deployment and hosting |

---

# 📂 Project Structure

```text
app/            → Application routes and pages
components/     → Reusable UI components
constants/      → Static configuration and constants
lib/            → Utilities and helper functions
public/         → Static assets and branding files
types/          → TypeScript interfaces and types
