# Randy Bites App

A full-stack food ordering and delivery application built with React, Node.js, and MongoDB.

## Project Structure

The project is organized into three main directories:

- `frontend/`: React-based customer-facing web application
- `admin/`: React-based admin dashboard for restaurant management
- `backend/`: Node.js/Express backend API server

## Features

- Customer Features:

  - Browse restaurant menu
  - Place food orders
  - Track order status
  - View order history
  - User authentication

- Admin Features:
  - Manage menu items
  - Process orders
  - View analytics
  - Manage restaurant settings

## Prerequisites

- Node.js (v14 or higher)
- MongoDB
- npm or yarn

## Getting Started

1. Clone the repository:

   ```bash
   git clone https://github.com/yourusername/randy-bites-app.git
   cd randy-bites-app
   ```

2. Install dependencies for all services:

   ```bash
   # Install frontend dependencies
   cd frontend
   npm install

   # Install admin dependencies
   cd ../admin
   npm install

   # Install backend dependencies
   cd ../backend
   npm install
   ```

3. Set up environment variables:

   - Create `.env` files in both frontend, admin, and backend directories
   - Follow the `.env.example` files for required variables

4. Start the development servers:

   ```bash
   # Start backend server
   cd backend
   npm run dev

   # Start frontend (in a new terminal)
   cd frontend
   npm run dev

   # Start admin (in a new terminal)
   cd admin
   npm run dev
   ```

## Development

- Frontend runs on: http://localhost:5173
- Admin dashboard runs on: http://localhost:5174
- Backend API runs on: http://localhost:3000

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the LICENSE file for details.
