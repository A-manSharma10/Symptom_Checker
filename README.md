echo ^
# 🩺 Symptom Checker App^
^
A Django web app that lets users input symptoms and receive basic diagnosis suggestions. Perfect for showcasing full-stack development in your portfolio.^
^
## 🚀 Getting Started^
^
### 📦 Prerequisites^
- Python 3.8+^
- Git^
- VS Code or any editor^
^
### 🔧 Setup Instructions^
^
1. **Clone the repository**^
   git clone https://github.com/yourusername/symptom-checker.git^
   cd symptom-checker^
^
2. **Create and activate a virtual environment**^
   python -m venv venv^
   venv\Scripts\activate   (on Windows)^
   source venv/bin/activate (on Mac/Linux)^
^
3. **Install dependencies**^
   pip install -r requirements.txt^
^
4. **Create a `.env` file**^
   Add this in your project root:^
   SECRET_KEY=your-secret-key^
   DEBUG=True^
   ALLOWED_HOSTS=127.0.0.1,localhost^
^
5. **Run migrations**^
   python manage.py migrate^
^
6. **Start the server**^
   python manage.py runserver^
^
7. Open http://127.0.0.1:8000 in your browser.^
^
## ✨ Features^
- Input symptoms via form^
- Basic rule-based logic^
- HTML + Django templates^
- Admin panel enabled^
^
## 🗂 Project Structure^
symptom-checker/^
├── symptom_checker/          (project config)^
├── symptom_checker_app/      (your app)^
├── templates/^
├── manage.py^
├── .env                      (you add this)^
└── README.md^
^
## 🧪 Testing^
- Try different symptoms^
- Test validation by submitting blank form^
- Extend diagnosis logic in views.py^
^
## 📄 License^
MIT — for educational/demo use^
^
## 🙌 Acknowledgments^
Thanks Django & OpenAI for tech support^
> README.md
