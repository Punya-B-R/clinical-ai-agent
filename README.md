# 🩺 Dr. Sage - AI-Powered Medical Assistant

A Streamlit-based medical AI assistant powered by Google's Gemini AI for analyzing medical queries, images, and prescriptions.

## Features

- 🩺 Symptom analysis and medical information
- 📄 PDF prescription/text analysis
- 🖼️ Medical image interpretation
- ⚠️ Safety-focused responses with professional consultation reminders

## Local Setup Guide
### 1. **Install Python 3.9+**  
   Download from [python.org](https://www.python.org/downloads/) then verify:
   ```bash
   python --version
   ```

### 2. Clone the Repository
   ```bash
   git clone <repository-url>
   cd <repository-folder-name>
   ```

### 3. Set Up Virtual Environment
   ```bash
   python -m venv venv
   venv\Scripts\activate # Windows
   source venv/bin/activate # macOS/Linux
   ```

### 4. Install Dependencies
   ```bash
   pip install --upgrade pip
   pip install -r requirements.txt
   ```
### 5. Configure API Key
   - In project root, create a new file named `.env`
   - Get key from [Google AI Studio](https://aistudio.google.com/app/apikey)  
   - Add to `.env`:
     ```text
     GEMINI_API_KEY="YOUR_API_KEY"  # Paste your key here
     ```
     
### 6. Run the Application
   ```bash
   streamlit run app.py
   ```
   The application will start running at http://localhost:8501.
