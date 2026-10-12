# 💈 Barbershop Management System

A web application for managing barbershop appointments with intelligent scheduling, conflict validation, and real-time availability.

---

## 📌 Project Overview

This project is a web-based system designed to help barbershops manage appointments efficiently.

It replaces manual scheduling with an automated system that:
- prevents time conflicts
- considers service duration
- improves organization and customer experience

---

## 🎯 Features

- Create appointments (booking)
- View appointments filtered by date
- Update appointments (reschedule)
- Delete appointments (cancel)
- Intelligent time-slot blocking based on:
  - service duration
  - existing bookings
  - business hours constraints
- Dynamic UI that updates available time slots

---

## 🧠 Business Rules Implemented

- Service duration affects availability
- No overlapping appointments allowed
- Business hours: 08:00 – 18:00
- Appointments restricted to working days
- Time slots dynamically disabled when unavailable

---

## 🛠 Technologies 

- **Frontend:** HTML, CSS, JavaScript
- **Backend:** Python (Flask)
- **Database:** SQLite
- **Server:** Gunicorn (for deployment)

---

## 📂 Project Structure

/templates      → HTML files  
/static         → CSS and JS  
app.py          → Flask application  
barbearia.db    → SQLite database  
requirements.txt

---

## 🚀 How to Run

```bash
# Clone repository
git clone https://github.com/prgalhardo/barbershop-management-system.git

# Install dependencies
pip install -r requirements.txt

# Run application
python app.py
```

## 📸 Preview

![Sistema de Agendamento](images/relatorio/figura_5_tela_final.png)