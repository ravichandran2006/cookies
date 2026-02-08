# FoodTech AI - Biscuit Predictor

A Flask-based web application that predicts ingredient quantities needed for biscuit production using machine learning.

## Features
- AI-powered ingredient prediction
- Interactive web interface
- PDF report generation
- Responsive design

## Deployment Instructions

### Option 1: Deploy to Render (Recommended)

1. **Create a GitHub repository** and push your code:
   ```bash
   git init
   git add .
   git commit -m "Initial commit"
   git remote add origin <your-repo-url>
   git push -u origin main
   ```

2. **Sign up at [Render](https://render.com)**

3. **Create a new Web Service:**
   - Connect your GitHub repository
   - Select your repository
   - Render will auto-detect Python and use the `render.yaml` configuration
   - Click "Create Web Service"

4. **Your app will be live** at: `https://your-app-name.onrender.com`

### Option 2: Deploy to PythonAnywhere

1. **Sign up at [PythonAnywhere](https://www.pythonanywhere.com)**

2. **Upload your files** via Files tab

3. **Open a Bash console** and install requirements:
   ```bash
   pip install -r requirements.txt
   ```

4. **Configure Web App:**
   - Go to Web tab
   - Add a new web app
   - Choose Flask
   - Set source code path
   - Set working directory

5. **Reload your web app**

### Option 3: Deploy to Railway

1. **Sign up at [Railway](https://railway.app)**

2. **Create new project:**
   - Select "Deploy from GitHub repo"
   - Choose your repository
   - Railway auto-detects Python

3. **Add environment variables** if needed

4. **Deploy** - Railway handles the rest!

## Local Development

1. **Create virtual environment:**
   ```bash
   python -m venv .venv
   .venv\Scripts\activate  # Windows
   source .venv/bin/activate  # Mac/Linux
   ```

2. **Install dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

3. **Run the application:**
   ```bash
   python app.py
   ```

4. **Open browser:** `http://localhost:5000`

## Requirements
- Python 3.8+
- Flask
- scikit-learn
- pandas
- reportlab

## Model File
Ensure `foods.pkl` is in the root directory with your trained model.
