CardioLens - AI Powered Retinal Heart Risk Analyzer
CardioLens is a Flask-based healthcare analytics tool that uses a Convolutional Neural Network (CNN) to predict cardiovascular risk from retinal images.

🚀 Key Features
AI Diagnostics: Automated heart risk prediction using Deep Learning.

Automated Alerts: Real-time diagnostic reports sent via Telegram Bot API.

Web Dashboard: User-friendly interface for image upload and result display.

🛠️ Technical Stack
Backend: Python (Flask)

AI/ML: TensorFlow, Keras (.h5 model)

Automation: Telepot (Telegram API)

Frontend: HTML5, CSS3

📂 Project Structure
app.py: Main server logic and AI integration.

templates/: HTML user interface files.

static/: CSS, images, and JavaScript assets.

requirements.txt: List of necessary Python libraries.

.gitignore: Prevents 218MB model and environment files from uploading.

⚙️ Installation
Install Libraries: pip install -r requirements.txt

Model File: The 218MB .h5 model is stored externally due to GitHub's 100MB limit.

Run App: python app.py
