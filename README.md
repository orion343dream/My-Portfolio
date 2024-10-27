🌟 Personal Portfolio Website
A modern, responsive personal portfolio website built to showcase my projects, skills, and professional journey in software engineering.
Show Image
✨ Features

🎯 Clean and intuitive user interface
📱 Fully responsive design for all devices
🚀 Fast loading and optimized performance
🎨 Dynamic theme switching (Light/Dark mode)
📊 Project showcase with filtering options
📝 Integrated blog section
📬 Contact form with email integration

🛠️ Built With

Frontend

React.js
Tailwind CSS
Framer Motion
React Icons


Backend

Node.js
Express.js
MongoDB


Deployment

Vercel (Frontend)
Heroku (Backend)



🚀 Getting Started
Prerequisites

Node.js (v14.0.0 or higher)
npm or yarn
MongoDB (for backend)

Installation

Clone the repository

bashCopygit clone https://github.com/your-username/portfolio.git
cd portfolio

Install dependencies

bashCopy# Install frontend dependencies
cd client
npm install

# Install backend dependencies
cd ../server
npm install

Set up environment variables

bashCopy# In the server directory, create a .env file
MONGODB_URI=your_mongodb_uri
PORT=5000
EMAIL_SERVICE=your_email_service
EMAIL_USERNAME=your_email_username
EMAIL_PASSWORD=your_email_password

# In the client directory, create a .env file
REACT_APP_API_URL=http://localhost:5000

Run the development server

bashCopy# Run frontend (in client directory)
npm run dev

# Run backend (in server directory)
npm run dev
📁 Project Structure
Copyportfolio/
├── client/                # Frontend React application
│   ├── public/           # Public assets
│   ├── src/
│   │   ├── components/   # Reusable components
│   │   ├── pages/        # Page components
│   │   ├── styles/       # Global styles
│   │   └── utils/        # Utility functions
│   └── package.json
│
└── server/               # Backend Node.js application
    ├── controllers/      # Route controllers
    ├── models/          # Database models
    ├── routes/          # API routes
    └── package.json
🔧 Configuration
Modify config.js in both client and server directories to customize:

Theme colors
API endpoints
Database configurations
Email service settings

📝 Available Scripts
In the client directory:
bashCopynpm run dev          # Start development server
npm run build        # Build for production
npm run test         # Run tests
npm run lint         # Run linting
In the server directory:
bashCopynpm run dev          # Start development server
npm run start        # Start production server
npm run test         # Run tests
🚀 Deployment
Frontend Deployment (Vercel)

Connect your GitHub repository to Vercel
Configure build settings:

Build Command: npm run build
Output Directory: dist
Install Command: npm install



Backend Deployment (Heroku)

Create a new Heroku application
Configure environment variables in Heroku dashboard
Deploy using Heroku CLI or GitHub integration

🤝 Contributing

Fork the repository
Create your feature branch (git checkout -b feature/AmazingFeature)
Commit your changes (git commit -m 'Add some AmazingFeature')
Push to the branch (git push origin feature/AmazingFeature)
Open a Pull Request

📜 License
This project is licensed under the MIT License - see the LICENSE file for details.
👏 Acknowledgments

React.js
Tailwind CSS
Framer Motion
Node.js

📧 Contact
Dilusha Sandaruwan - sadaruwan.optimous@gmail.com
Project Link:https://github.com/orion343dream/My-Portfolio
