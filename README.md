# 🔐 SecureAI WebApp

SecureAI is a secure e-commerce web application designed to protect users from phishing attacks and malware threats in real time using AI.

## 🚀 Live Demo

🔗 [SecureAI WebApp on Render](https://secureecom.onrender.com/)

## 📂 GitHub Repository

🔗 [https://github.com/SoniyaKodipunjula/SecureAIWeb](https://github.com/SoniyaKodipunjula/SecureAIWeb)

---

## 📌 Features

- ✅ Phishing URL Detection using a trained ML model
- ✅ File upload scanning with malware hash verification
- ✅ Flask backend with HTTPS enforced via Flask-Talisman
- ✅ User-friendly Bootstrap frontend
- ✅ Upload file size limited to 5MB to prevent DoS
- ✅ Deployed on Render with production config

---

## 🧪 Tech Stack

- **Frontend:** HTML, Bootstrap
- **Backend:** Flask, Flask-Talisman
- **AI Model:** scikit-learn, joblib
- **Security Tools Used:** Nessus, Nikto, OWASP ZAP

---

## 🗂️ Project Structure

```
SecureAIWeb/
│
├── app.py                  # Flask application backend
├── detector.py             # AI model and malware check logic
├── index.html              # Frontend UI
├── phishing_model.pkl      # Trained phishing detection model
├── malware_hashes.txt      # Known malware hash signatures
├── render.yaml             # Render deployment config
├── requirements.txt        # Python dependencies
├── README.md
└── docs/                   
    ├── SecureAI.pptx       # Detailed presentation with Data Flow Diagram
```

---

## ⚙️ Deployment (Render)

Render service uses `render.yaml` with:

```yaml
buildCommand: pip install -r requirements.txt
startCommand: python app.py
```

---

## 🛡️ Security Implementations

- Enforced HTTPS using Flask-Talisman
- No reflected XSS or SQL injection vulnerabilities (verified using ZAP/Nikto)
- 5MB upload limit to prevent denial-of-service attacks
- Clean input validation and secure file handling

---

## 📚 References

- Flask & Flask-Talisman Documentation
- OWASP ZAP, Nessus, Nikto
- [GitHub - SecureAIWeb](https://github.com/SoniyaKodipunjula/SecureAIWeb)

---

## 👩‍💻 Developed By

**Soniya Kodipunjula**  
Master’s in Computer Science  
University of North Texas