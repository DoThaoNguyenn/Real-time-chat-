# Real-time Chat Application

A modern real-time chat application built with Next.js, Nest.js, and WebSocket.

## Features

- Real-time messaging using WebSocket
- JWT authentication
- Modern UI with Tailwind CSS and shadcn/ui
- Smooth animations with Framer Motion
- PostgreSQL database with Prisma ORM

## Tech Stack

### Frontend
- Next.js 14
- TypeScript
- Tailwind CSS
- shadcn/ui
- Framer Motion
- Socket.io Client

### Backend
- Nest.js
- WebSocket
- JWT Authentication
- Prisma ORM
- PostgreSQL

## Prerequisites

- Node.js (v18 or higher)
- PostgreSQL
- npm or yarn

## Getting Started

1. Clone the repository:
```bash
git clone https://github.com/yourusername/real-time-chat.git
cd real-time-chat
```

2. Install dependencies for both frontend and backend:
```bash
# Install backend dependencies
cd backend
npm install

# Install frontend dependencies
cd ../frontend
npm install
```

3. Set up environment variables:
   - Copy `.env.example` to `.env` in both frontend and backend directories
   - Update the variables with your configuration

4. Set up the database:
```bash
cd backend
npx prisma generate
npx prisma db push
```

5. Start the development servers:

Backend:
```bash
cd backend
npm run start:dev
```

Frontend:
```bash
cd frontend
npm run dev
```

The application will be available at:
- Frontend: http://localhost:3000
- Backend: http://localhost:3001

## Project Structure

```
real-time-chat/
├── frontend/          # Next.js frontend application
│   ├── src/
│   ├── public/
│   └── package.json
├── backend/          # Nest.js backend application
│   ├── src/
│   ├── prisma/
│   └── package.json
├── .gitignore
└── README.md
```

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the LICENSE file for details. 