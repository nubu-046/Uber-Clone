# Uber Clone

A full-stack Uber Clone application built with MERN stack (MongoDB, Express.js, React.js, Node.js) featuring real-time ride tracking and management.

## Features

- Real-time ride tracking
- Interactive maps integration
- User and Captain (Driver) authentication
- Responsive design for all devices
- Real-time updates using Socket.IO
- Live location tracking
- Ride management system
- Protected routes for users and captains

## Tech Stack

### Frontend
- React.js
- Tailwind CSS
- Socket.IO Client
- Context API for state management
- Vite as build tool

### Backend
- Node.js
- Express.js
- MongoDB
- Socket.IO
- JWT Authentication

## Project Structure

```
├── Backend/
│   ├── controllers/      # Request handlers
│   ├── models/          # Database models
│   ├── routes/          # API routes
│   ├── services/        # Business logic
│   ├── middlewares/     # Custom middlewares
│   └── db/             # Database configuration
├── frontend/
│   ├── src/
│   │   ├── components/  # Reusable UI components
│   │   ├── context/     # React Context providers
│   │   ├── pages/       # Application pages
│   │   └── assets/      # Static assets
```

## Getting Started

### Prerequisites
- Node.js
- MongoDB
- npm or yarn

### Installation

1. Clone the repository
```bash
git clone https://github.com/nubu-046/Uber-Clone.git
cd Uber-Clone
```

2. Install Backend Dependencies
```bash
cd Backend
npm install
```

3. Install Frontend Dependencies
```bash
cd frontend
npm install
```

4. Start the Backend Server
```bash
cd Backend
npm start
```

5. Start the Frontend Development Server
```bash
cd frontend
npm run dev
```

## Key Components

- **Real-time Tracking**: Implemented using Socket.IO for live location updates
- **Authentication System**: Separate authentication for users and captains
- **Interactive Map**: Location search and ride tracking interface
- **Ride Management**: Complete flow from ride request to completion
- **Protected Routes**: Secure routes for both users and captains

## Available Pages

### User Side
- Home Page
- User Login/Signup
- Ride Booking Interface
- Live Tracking Page

### Captain (Driver) Side
- Captain Login/Signup
- Captain Home
- Ride Management Interface
- Active Ride Interface

## Features in Detail

1. **User Features**
   - Search for pickup and drop-off locations
   - View estimated fare
   - Track assigned captain
   - View ride history
   - Real-time ride tracking

2. **Captain Features**
   - Accept/Reject ride requests
   - Navigate to pickup location
   - Start/End rides
   - View earnings and ride history

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgements

- Maps integration powered by Google Maps API
- Real-time communication using Socket.IO
- UI components styled with Tailwind CSS


