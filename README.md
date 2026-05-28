# TodReg LMS - Learning Management System

A modern cloud-based online learning platform supporting live and recorded lessons, course management, assessments, AI-assisted learning, and analytics.

## Tech Stack

- **Frontend**: Next.js + TypeScript + React
- **Backend**: NestJS + PostgreSQL + Redis
- **Mobile**: Flutter
- **Infrastructure**: Docker + Kubernetes + AWS
- **Real-time**: WebRTC + Socket.io
- **AI**: OpenAI Integration

## Quick Start

### Prerequisites
- Node.js 18+
- Docker & Docker Compose
- PostgreSQL 14+
- Redis 7+

### Development Setup

```bash
# Start services
docker-compose up -d

# Frontend
cd frontend
npm install
npm run dev

# Backend (in another terminal)
cd backend
npm install
npm run start:dev
```

## Project Structure

```
todreg-lms/
├── frontend/              # Next.js web application
├── backend/               # NestJS backend services
├── mobile/                # Flutter mobile app
├── docker-compose.yml     # Local development setup
└── docs/                  # Documentation
```

## Features

- Live virtual classroom with HD video
- Course management system
- Assignment & assessment system
- Real-time messaging & communication
- Learning analytics & reporting
- AI-powered grading & tutoring
- Multi-tenant architecture
- Mobile apps (iOS/Android)
- Payment gateway integration
- Gamification & certificates

## License

MIT
