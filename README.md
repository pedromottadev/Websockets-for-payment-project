
# 💳 Real-Time Payment Notification System

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.11-blue?style=for-the-badge&logo=python" />
  <img src="https://img.shields.io/badge/Flask-2.3.0-black?style=for-the-badge&logo=flask" />
  <img src="https://img.shields.io/badge/Socket.IO-5.3.6-green?style=for-the-badge&logo=socketdotio" />
  <img src="https://img.shields.io/badge/SQLAlchemy-3.1.1-red?style=for-the-badge&logo=sqlite" />
  <img src="https://img.shields.io/badge/Pytest-Testing-yellow?style=for-the-badge&logo=pytest" />
</p>

---

##  Overview

This project implements a **real-time payment notification system** using **WebSockets with Flask-SocketIO**.  
It allows instant updates whenever a payment is processed, combining **Flask**, **SQLAlchemy**, and **Socket.IO** to deliver a responsive and scalable architecture.  

The project also supports **QR Code generation** for payments and includes **comprehensive testing** using **Pytest** for unit/integration tests and **Postman** for HTTP endpoint validation.  

---

##  Features

-  **Real-Time Notifications** using WebSockets (Flask-SocketIO)  
-  **Payment Handling** with instant updates  
-  **HTTP Endpoints** fully testable via Postman  
-  **QR Code Generation** (powered by `qrcode` + `Pillow`)  
-  **Frontend with HTML + CSS**  
-  **Independent Testing** using Pytest  
-  **Database Integration** with SQLAlchemy  

---

## 🛠 Tech Stack

- **Backend:** Flask (Python)  
- **Real-Time Engine:** Flask-SocketIO  
- **Database ORM:** SQLAlchemy  
- **Frontend:** HTML + CSS  
- **Testing:** Pytest & Postman  
- **Utilities:** qrcode, Pillow  

---

## 📦 Requirements

All dependencies are pinned to specific versions for stability:  

```txt
Flask==2.3.0
qrcode==7.4.2
pillow==10.2.0
Flask-SocketIO==5.3.6
Flask-SQLAlchemy==3.1.1
pytest
