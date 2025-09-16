# Finance App Commet

A modern, full-stack personal finance management application built with React, Node.js, and MongoDB.

## Features

- 📊 Dashboard with financial overview
- 💰 Transaction tracking and categorization
- 🏦 Account management
- 📈 Spending analytics and reports
- 📱 Responsive design for mobile and desktop
- 🔐 Secure authentication and authorization

## Tech Stack

**Frontend:**
- React.js
- React Router
- Axios for API calls
- CSS3/SCSS for styling

**Backend:**
- Node.js
- Express.js
- JWT Authentication
- bcrypt for password hashing

**Database:**
- MongoDB
- Mongoose ODM

## Project Structure

```
finance-app-commet/
├── frontend/          # React frontend application
├── backend/           # Node.js backend API
├── database/          # Database schemas and migrations
├── .gitignore         # Git ignore file
└── README.md          # Project documentation
```

## Getting Started

### Prerequisites

- Node.js (v14 or higher)
- MongoDB (local installation or MongoDB Atlas)
- Git

### Installation

1. Clone the repository:
```bash
git clone https://github.com/shehzadaliqadri/finance-app-commet.git
cd finance-app-commet
```

2. Install backend dependencies:
```bash
cd backend
npm install
```

3. Install frontend dependencies:
```bash
cd ../frontend
npm install
```

4. Set up environment variables:
   - Copy `.env.example` to `.env` in the backend folder
   - Configure your MongoDB connection string
   - Set JWT secret and other required variables

5. Run the application:

   **Backend (from backend folder):**
   ```bash
   npm run dev
   ```

   **Frontend (from frontend folder):**
   ```bash
   npm start
   ```

6. Open [http://localhost:3000](http://localhost:3000) to view the app in your browser.

## Development

- Backend API runs on `http://localhost:5000`
- Frontend development server runs on `http://localhost:3000`
- MongoDB connection should be configured in backend `.env` file

## Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Contact

Shehzad Ali Qadri - [@shehzadaliqadri](https://github.com/shehzadaliqadri)

Project Link: [https://github.com/shehzadaliqadri/finance-app-commet](https://github.com/shehzadaliqadri/finance-app-commet)
