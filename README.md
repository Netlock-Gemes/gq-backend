# Gamified Quiz

This is the backend application for the Quiz App. It provides API endpoints for user authentication, quiz management, and score submission.

## Features

- User authentication (login, registration).
- Manage quiz scores.
- Submit and retrieve high scores.

## Technologies Used

- Node.js
- Express.js
- MongoDB
- Mongoose
- JWT for authentication

## Getting Started

### Prerequisites

- Node.js and npm installed on your machine.
- MongoDB installed and running.

### Installation

1. Clone the repository:
    ```sh
    git clone https://github.com/your-username/quiz-app-backend.git
    ```
2. Navigate to the project directory:
    ```sh
    cd quiz-app-backend
    ```
3. Install dependencies:
    ```sh
    npm install
    ```

### Running the App

1. Create a `.env` file at the root of the project with the following environment variables:
    ```
    PORT=5000
    MONGODB_URI=your_mongodb_connection_string
    JWT_SECRET=your_jwt_secret
    ```
2. Start the server:
    ```sh
    npm start
    ```
3. The API will be available at [http://localhost:5000](http://localhost:5000).

## API Endpoints

- `POST /api/auth/register`: Register a new user.
- `POST /api/auth/login`: User login.
- `POST /api/auth/submit-score`: Submit a new quiz score.
- `GET /api/auth/scores`: Retrieve user scores.

## Project Structure

- `controllers/`: Contains controllers for handling requests.
- `models/`: Contains Mongoose models.
- `routes/`: Contains route definitions.
- `middlewares/`: Contains middleware functions (e.g., authentication).
- `server.js`: Entry point of the application.

## License

This project is licensed under the MIT License.
