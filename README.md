# Pypad

Pypad is a web application that integrates a Laravel 10 backend, a React frontend, and an OpenAI service app. The project consists of three main components, each housed in its own submodule within the repository. Additionally, the project utilizes Redux for state management in the frontend and includes C4 model diagrams to illustrate the system architecture.

## Table of Contents

- [Project Structure](#project-structure)
- [Setup Instructions](#setup-instructions)
- [Backend (Laravel 10)](#backend-laravel-10)
- [Frontend (React)](#frontend-react)
- [OpenAI Service App (Node.js)](#openai-service-app-nodejs)
- [API Documentation](#api-documentation)
- [C4 Model Diagrams](#c4-model-diagrams)

## Project Structure

The repository contains the following submodules:

- `backend-laravel`: The Laravel 10 backend application.
- `frontend-react`: The React frontend application.
- `openai-service-app`: A Node.js application that handles OpenAI API requests.

Additionally, the repository includes a folder named `c4-models` which contains C4 model diagrams (Level 1 and Level 2).

## Setup Instructions

### Cloning the Repository

To clone the repository with all its submodules, use the following command:

\`\`\`bash
git clone --recurse-submodules <repository-url>
\`\`\`

### Backend (Laravel 10)

1. Navigate to the backend directory:

\`\`\`bash
cd backend-laravel
\`\`\`

2. Install dependencies:

\`\`\`bash
composer install
\`\`\`

3. Copy the example environment file and modify it according to your setup:

\`\`\`bash
cp .env.example .env
\`\`\`

4. Generate an application key:

\`\`\`bash
php artisan key:generate
\`\`\`

5. Run the database migrations:

\`\`\`bash
php artisan migrate --seed
\`\`\`

6. Start the development server:

\`\`\`bash
php artisan serve
\`\`\`

### Frontend (React)

1. Navigate to the frontend directory:

\`\`\`bash
cd frontend-react
\`\`\`

2. Install dependencies:

\`\`\`bash
npm install
\`\`\`

3. Start the development server:

\`\`\`bash
npm start
\`\`\`

### OpenAI Service App (Node.js)

1. Navigate to the OpenAI service app directory:

\`\`\`bash
cd openai-service-app
\`\`\`

2. Install dependencies:

\`\`\`bash
npm install
\`\`\`

3. Copy the example environment file and modify it with your OpenAI API key:

\`\`\`bash
cp .env.example .env
\`\`\`

4. Start the server:

\`\`\`bash
npm start
\`\`\`

## API Documentation

The API endpoints are documented using Postman. You can view the full documentation [here](https://documenter.getpostman.com/view/24751453/2sA3kYjzyW#22503bba-7791-4548-992d-53b0650feb8d).

## C4 Model Diagrams

The repository includes C4 model diagrams to illustrate the system architecture. The diagrams are located in the `c4-models` folder and include:

- `c4-level1.png`: Level 1 Context Diagram
- `c4-level2.png`: Level 2 Container Diagram
