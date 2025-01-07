# Project Name

This repository contains the **client-side code** (frontend) and the **API** (backend) for the project.

---

## Project Structure

### Client-Side Code (Frontend)
The client-side code is structured as follows:

/public # Public assets (images, icons, etc.) /src # Source files (React components, utilities, etc.) index.html # HTML entry point package.json # Project dependencies and scripts vite.config.js # Vite configuration file .gitignore # Files and folders to ignore in Git


### API Code (Backend)
The API folder contains:

server.js # Main server file package.json # Project dependencies and scripts vercel.json # Configuration file for deployment on Vercel .gitignore # Files and folders to ignore in Git


---

## Environment Variables

### Client-Side Environment Variables
- `VITE_SERVER_URL`: The URL of the backend server.

Create a `.env` file in the `client` folder and add:
VITE_SERVER_URL=http://localhost:4000


### API Environment Variables
- `OPENAI_API_KEY`: Your OpenAI API key for accessing AI-related features.

Create a `.env` file in the `api` folder and add:
OPENAI_API_KEY=your_openai_api_key


---

## Getting Started

### 1. Clone the Repository
To clone the repository, run:
```bash
git clone https://github.com/your-username/your-repo-name.git

Running the Project
Client (Frontend)
Open a terminal and navigate to the client folder:
bash
Copy code
cd client
Install dependencies:
bash
Copy code
npm install
Start the development server:
bash
Copy code
npm run dev
The frontend will be available at:
arduino
Copy code
http://localhost:5173/
API (Backend)
Open another terminal and navigate to the api folder:
bash
Copy code
cd api
Install dependencies:
bash
Copy code
npm install
Start the server:
bash
Copy code
npm start
The backend will be available at:
arduino
Copy code
http://localhost:4000/
Notes
Ensure you have Node.js and npm installed on your system before running the commands.
Replace your_openai_api_key with your actual OpenAI API key in the .env file for the API.
The frontend and backend URLs mentioned above are for local development.

