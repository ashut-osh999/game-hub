# YouTube Clone Platform

A comprehensive video sharing platform similar to YouTube with features for content creators, users, and administrators.

## Features

- User authentication and authorization
- Video upload and streaming
- Content creator dashboard
- Admin panel
- Analytics and monetization
- Responsive design
- And more...

## Prerequisites

- Node.js (v14 or higher)
- MongoDB
- AWS Account (for S3 storage)
- FFmpeg

## Setup Instructions

1. Clone the repository
2. Install dependencies:
   ```bash
   npm install
   cd client
   npm install
   ```

3. Configure environment variables:
   - Copy `.env.example` to `.env`
   - Update the values with your configuration

4. Start the development server:
   ```bash
   # Run backend server
   npm run dev
   
   # Run frontend client
   npm run client
   
   # Run both concurrently
   npm run dev:full
   ```

5. Access the application:
   - Frontend: http://localhost:3000
   - Backend API: http://localhost:5000

## Tech Stack

- Frontend: React.js, Redux, Tailwind CSS
- Backend: Node.js, Express.js
- Database: MongoDB
- Storage: AWS S3
- Video Processing: FFmpeg
- Authentication: JWT

## License

MIT
