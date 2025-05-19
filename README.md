# QuickDoc - Doctor Appointment Booking System

**QuickDoc** is a full-stack web application designed to streamline the process of scheduling and managing medical appointments. With three dedicated portals for Admins, Patients, and Doctors, the system enhances healthcare accessibility, reduces administrative workload, and ensures a seamless booking experience.

## 🚀 Overview

Access to quality healthcare is a fundamental need, and scheduling medical appointments efficiently is crucial for both patients and doctors. Traditional booking methods often suffer from long wait times, miscommunication, and scheduling conflicts.

QuickDoc solves these challenges by offering:
- A user-friendly digital platform
- Real-time appointment scheduling
- Secure online payments
- Efficient management of doctors, patients, and appointments

## 🔍 Features

### 🔸 Admin Portal
- Manage doctor profiles and specialties
- Oversee patient records and appointment schedules
- Monitor system activity and ensure operational efficiency

### 🔸 Patient Portal
- Search for doctors by name or specialty
- Book appointments in available time slots
- Secure online payment integration via Razorpay

### 🔸 Doctor Portal
- Manage appointment requests (accept/reject)
- Track schedules and earnings
- View patient history (if permitted)

## 🛠️ Tech Stack

| Technology        | Purpose                                         |
|-------------------|--------------------------------------------------|
| **React**         | Front-end development for dynamic UI            |
| **MySQL**         | Structured data storage (users, transactions)   |
| **MongoDB**       | Flexible NoSQL storage (doctor/patient records) |
| **Razorpay**      | Payment gateway integration                     |

## 🧠 Future Enhancements
- AI-powered appointment recommendations
- Telemedicine (video call) integration
- Automated reminders via email/SMS
- Admin analytics dashboard

## 📦 Installation & Setup

```bash
# Clone the repository
git clone https://github.com/arjunajaygit/hms-main-main.git
cd hms-main-main

# Install dependencies
npm install

# Set up environment variables (.env)
# Add Razorpay keys, DB URLs, etc.

# Run the development server
npm start

