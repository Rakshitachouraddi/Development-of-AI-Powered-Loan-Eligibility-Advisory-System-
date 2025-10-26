🔹 **Intelligent Loan Eligibility Predictor**

Evaluates approval chances using ML algorithms with inputs like income, liabilities, and repayment history.

🔹**Smart Conversational Advisor**
Engages users through natural text and voice conversations, providing guidance on loan options and financial planning.

🔹**Transparent AI Insights**

Delivers clear reasoning for each decision with SHAP-based explanations, enhancing trust in the predictions.

🔹 **Automated Report Generator**

Produces professional, downloadable PDF summaries with eligibility outcomes, supporting data, and actionable insights.

🔹**Interactive User Experience**
Seamless web interface with real-time responses, document upload support, and voice-enabled interaction.

**WATCH THE DEMO VIDEO HERE**
🎥 [Watch the project demo here](https://drive.google.com/file/d/1IHeVr_hUyV4-YISmCmHpO4GVmG79gu2R/view?usp=sharing)


## 🚀** Live Deployment**

[![View Deployment](https://img.icons8.com/fluency/96/rocket.png)](https://ai-credit-underwriting-system.onrender.com)

> Click the rocket above to open the live app 🌐
>
# Local Setup & Run Instructions

## 1. Backend Setup

```bash
# Navigate to the backend folder
cd backend

# Create and activate a virtual environment
# On Windows:
python -m venv venv
venv\Scripts\activate

# Install dependencies (ensure Tesseract OCR is installed on your system)
pip install -r requirements.txt

# Run the server (this will also train the AI model)
python -m uvicorn app.main:app --reload
# Open a NEW terminal and navigate to the frontend folder
cd web_frontend

# Start the simple web server on port 8001
python -m http://localhost:8001.
