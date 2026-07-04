# 🎯 Smart Queue Tracker

A **modern web-based Queue Management System** developed using **Python (Flask)**, **MongoDB**, **HTML**, **CSS**, and **JavaScript**. The application streamlines queue management by allowing users to generate queue tokens, monitor their position in real time, and helping staff efficiently manage customer flow through an intuitive dashboard.

---

## 🚀 Overview

The **Smart Queue Tracker** is designed to minimize waiting time and improve customer service in places such as **hospitals, banks, government offices, clinics, and service centers**.

Users can generate a digital queue token and track their current position, while staff can manage the queue by serving, completing, or cancelling tokens through a dedicated dashboard. The system provides a simple, responsive, and user-friendly interface, making queue management more organized and efficient.

This project demonstrates practical implementation of **full-stack web development**, integrating a Flask backend with MongoDB for data storage and a responsive frontend for an enhanced user experience.

---

## ✨ Features

### User Side
- Generate and track tokens in real-time  
- Live countdown for active tokens  
- View token status (Active / Completed / Cancelled)  

### Staff Side
- Secure login system  
- Dashboard showing all tokens for the day  
- Update token statuses (Done / Cancelled)  
- View analytics: active tokens, completed tokens, average wait time, fastest service  

### System
- Persistent storage using MongoDB  
- Responsive front-end with Bootstrap and animations  
- Works on desktop and mobile browsers  

---

## 🧠 Tech Stack

| Layer      | Technologies                                    |
|------------|-------------------------------------------------|
| Frontend   | HTML5, CSS3, JavaScript, Bootstrap, Animate.css |
| Backend    | Python Flask                                    |
| Database   | MongoDB                                         |

---

## ⚙️ Installation & Setup

1️⃣ Clone the Repository
```bash
git clone https://github.com/YOUR_USERNAME/SmartQueue.git
cd SmartQueue

2️⃣ Install Dependencies
pip install -r requirements.txt

3️⃣ Start MongoDB

Ensure MongoDB is running locally, or update your connection string in app.py.

4️⃣ Run the Flask App
python app.py

5️⃣ Open in Browser

Visit: http://127.0.0.1:5000


### 🧩 Project Structure
SmartQueue/
├── app.py                 # Flask main application
├── requirements.txt       # Python dependencies
├── templates/             # HTML templates
│   ├── index.html         # Home / User login
│   ├── staff.html         # Staff dashboard
│   ├── token.html         # Token display
├── static/                # CSS, JS, images
│   ├── background.jpg
│   ├── style.css
│   ├── script.js
└── README.md              # Project documentation

📊 Future Enhancements

Staff performance analytics dashboard

SMS/email notifications for users

Multi-counter or multi-branch support

Cloud deployment on Render, AWS, or PythonAnywhere

🤝 Contributing

Contributions are welcome!

Fork the repository

Create your feature branch:

git checkout -b feature/AmazingFeature


Commit your changes:

git commit -m "Add AmazingFeature"


Push the branch:

git push origin feature/AmazingFeature


Open a Pull Request

🪪 License

This project is licensed under the MIT License. See the LICENSE file for details.
