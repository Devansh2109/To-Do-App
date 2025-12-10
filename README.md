# Todo App

A modern, full-stack Todo application built with FastAPI and React, featuring a premium dark mode UI.

## Tech Stack

- **Backend:** FastAPI (Python)
- **Frontend:** React (TypeScript), Chakra UI
- **Styling:** Custom Dark Theme with Glassmorphism effects

## Project Structure

- `back/`: Backend API server code
- `front/frontend/`: Frontend React application source code

## Setup & Installation

### Prerequisites

- Python 3.8+
- Node.js & npm

### 1. Backend Setup

Navigate to the backend directory and start the server:

```bash
cd back

# Create virtual environment (optional but recommended)
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

# Install dependencies
pip install fastapi uvicorn

# Run the server
python main.py
```

The API will be running at `http://localhost:8000`.

### 2. Frontend Setup

Navigate to the frontend directory and start the development server:

```bash
cd front/frontend

# Install dependencies
npm install

# Start the dev server
npm run dev
```

The application will be available at `http://localhost:5173`.

## Features

- **Create Todos:** Quickly add new tasks to your list.
- **Update Todos:** Edit existing tasks with a modal interface.
- **Delete Todos:** Remove completed tasks.
- **Modern UI:** Features a sleek dark theme, glassmorphism cards, and smooth animations.
