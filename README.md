# Cheap School Data Project

## Project Structure

- **backend/**: Contains the server-side code.
- **frontend/**: Contains the client-side code.
- **docker/**: Contains Docker configuration files.
- **migrations/**: Contains database migration files.
- **auth/**: Contains authentication system code.
- **payment/**: Contains payment integration code.
- **docs/**: Contains all documentation.

## Description
This project includes a complete setup for a school data system, leveraging Node.js and Express for the backend and React for the frontend. Docker is used for containerization, and the system includes features such as database migrations, an authentication system, and payment integration.

## Getting Started
To get started with the project, follow the steps below:

1. **Clone the repository**
   ```bash
   git clone https://github.com/asackey1565-maker/cheap-school-data.git
   cd cheap-school-data
   ```
2. **Set up the backend**
   Navigate to the `backend` directory and install the dependencies:
   ```bash
   cd backend
   npm install
   ```
3. **Set up the frontend**
   Navigate to the `frontend` directory and install the dependencies:
   ```bash
   cd frontend
   npm install
   ```
4. **Build and run the Docker containers**
   Use Docker Compose to run the application:
   ```bash
   docker-compose up
   ```
5. **Access the application**
   Open your browser and go to `http://localhost:3000` to access the frontend.

## Documentation
Detailed documentation for each component can be found in the `docs/` directory.