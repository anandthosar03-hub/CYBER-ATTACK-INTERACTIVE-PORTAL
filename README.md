# 🔐 Cyber Attack Interactive Portal

An interactive web-based platform designed to demonstrate and explain different types of cyber attacks in a visual and educational way. This project helps learners understand how attacks work and how they can be mitigated safely.

---

## 🚀 Project Overview

The **Cyber Attack Interactive Portal** is a lightweight educational web application that simulates and explains various cyber attack vectors in an interactive format.

### 📚 Covered Topics

* Malware Attacks
* Ransomware
* SQL Injection
* Cross-Site Scripting (XSS)
* Email Spoofing
* Password Attacks (Dictionary Attack Simulation)
* Man-in-the-Middle (MITM)
* Distributed Denial of Service (DDoS)

---

## 🎯 Purpose

This project is built for:

* 🎓 Students learning cybersecurity
* 🧑‍🏫 Trainers and instructors
* 🧪 Lab demonstrations
* 🏫 College projects
* 🛡️ Cyber awareness programs

---

## 🧠 Key Features

* 🎯 Interactive tab-based UI
* 📊 Educational explanations for each attack
* 🧪 Simulated attack demonstrations
* 🎨 Clean and responsive design
* ⚡ Lightweight and fast execution
* 💻 Easy local deployment

---

## 🏗️ Project Structure

```
Cyber-Attack-Interactive-Portal/
│
├── index.php          # Main UI (HTML-based content)
├── style.css          # Styling and UI design
├── server.py          # Python HTTP server
├── README.md          # Documentation
└── .git/              # Git repository files
```

---

## ⚙️ Technologies Used

### Frontend

* HTML5
* CSS3
* Google Fonts (Inter, Orbitron)

### Backend

* Python 3
* Built-in `http.server` module

---

## 🔧 Working Mechanism

1. The Python server (`server.py`) starts a local HTTP server.
2. It serves `index.php` as the main page.
3. The `.php` file is treated as static HTML (no PHP execution).
4. The frontend displays attack modules using interactive UI tabs.
5. CSS enhances visuals and responsiveness.

---

## ▶️ Installation & Setup

### Step 1: Clone the Repository

```bash
git clone https://github.com/anandthosar03-hub/cyber-attack-portal.git
cd cyber-attack-portal
```

### Step 2: Run the Server

```bash
python server.py
```

### Step 3: Open in Browser

```
http://localhost:8001
```

---

## ⚠️ Important Notice

* This project is for **educational purposes only**
* No real cyber attacks are performed
* All simulations are safe and controlled

---

## 🔒 Security Considerations

* No database connection → minimal attack surface
* No real exploitation code
* Runs locally (recommended)
* Not suitable for public deployment without improvements

### If deploying publicly, implement:

* Input validation
* Authentication system
* Backend security layers
* HTTPS configuration

---

## 📌 Use Cases

* Cybersecurity workshops
* Ethical hacking training
* Academic projects
* Awareness campaigns
* Beginner penetration testing learning

---


## ⭐ Support & Contribution

If you like this project:

* ⭐ Star this repository
* 🍴 Fork it
* 🛠️ Contribute improvements

---


**🚀 Build. Learn. Secure.**
