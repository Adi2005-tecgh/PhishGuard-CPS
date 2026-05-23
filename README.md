# PhishGuard-CPS: Phishing Website Detection Using ML & Cisco Packet Tracer

## 📌 Overview

PhishGuard-CPS is a cybersecurity project that combines **Machine Learning**, **Flask Web Application**, and **Cisco Packet Tracer network simulation** to demonstrate phishing website detection and phishing attack workflow in a Cyber-Physical System (CPS) environment.

The project simulates real-world phishing scenarios involving **Attacker, Victim, Admin, DNS Server, Email Server, Legitimate Server, and Phishing Server**.

---

## 🚀 Features

- ML-based phishing URL detection using **Gradient Boosting Classifier**
- Real-time phishing website classification
- Flask-based web interface
- Cisco Packet Tracer phishing attack simulation
- Attacker → Victim → Admin workflow
- Email communication simulation
- DNS monitoring and domain resolution
- Security dashboard for admin monitoring
- Warning popup & threat level alerts
- URL reporting and admin response system

---

## 🛠️ Technologies Used

### Machine Learning
- Python
- Scikit-learn
- Pandas
- NumPy
- Gradient Boosting Classifier

### Web Development
- Flask
- HTML
- CSS
- JavaScript

### Network Simulation
- Cisco Packet Tracer
- Router
- Switch
- DNS Server
- Email Server
- Web Servers

### Communication Protocols
- TCP/IP
- HTTP / HTTPS
- DNS
- Ethernet

---

## 🧠 ML Module Working

1. User enters suspicious URL.
2. Feature extraction performed:
   - URL Length
   - Number of Dots
   - HTTPS Presence
   - Special Characters
   - Subdomains
   - IP Address Usage
3. Features converted to numerical form.
4. Gradient Boosting model predicts:
   - **1 → Legitimate Website**
   - **-1 → Phishing Website**
5. Warning message displayed if phishing detected.

---

## 🌐 Cisco Packet Tracer Workflow

1. Attacker sends phishing email.
2. Victim receives suspicious link.
3. DNS resolves domain.
4. Victim accesses website.
5. System identifies phishing activity.
6. Warning popup displayed.
7. Victim reports malicious website to Admin.
8. Admin monitors attack using Security Dashboard.
9. Admin takes action and sends response.

---

## 🏗️ Project Components

- **Attacker_PC** → Sends phishing emails
- **Victim_PC** → Receives suspicious links
- **Admin_PC** → Monitors security incidents
- **Switch** → Connects network devices
- **Router** → Handles routing between networks
- **Email_Server** → Email communication
- **DNS_Server** → Domain name resolution
- **Legit_Server** → Safe genuine website
- **Phishing_Server** → Fake phishing website simulation

---

## 🛡️ Security Measures

- ML-based URL Detection
- DNS Monitoring
- Network Segmentation
- User Alert System
- HTTPS Verification
- Access Control Concepts



## 📂 Installation

Clone repository:

```bash
git clone https://github.com/Adi2005-techg/PhishGuard-CPS.git
```

Move into project folder:

```bash
cd PhishGuard-CPS
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Run Flask application:

```bash
python app.py
```

---

## 📈 Future Scope

- Deep Learning models (CNN/LSTM)
- Browser extension integration
- Enterprise firewall integration
- Cloud phishing detection API
- Real-time threat intelligence

---

## 👨‍💻 Team Members

- Aditya Sonakanalli
- Samiksha Hubale
- Aditi Nalawade

---

## 📜 License

This project is developed for **academic and educational purposes**.
