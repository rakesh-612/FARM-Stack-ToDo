
# FARM-Stack-ToDo

========================
Frontend Setup
========================

# Go to frontend folder
cd frontend

# Install React app
npm create vite@latest

Choose:
✔ React
✔ JavaScript (or TypeScript)

npm install

# Install dependencies
npm install axios react-icons

# Start frontend
npm start



========================
Backend Setup
========================

# Create virtual environment
python -m venv post-env

# Activate (Windows)
.\post-env\Scripts\activate

# Go to backend folder
cd backend

# Install dependencies
pip install "fastapi[all]" "motor[srv]" beanie aiostream python-dotenv

# Check installed packages
pip list

# Run server
uvicorn src.server:app --host 0.0.0.0 --port 8000 --reload

# Create requirements file
pip freeze > requirements.txt

# Run with Docker (for testing)
docker-compose up --build



Reference - https://youtu.be/PWG7NlUDVaA

