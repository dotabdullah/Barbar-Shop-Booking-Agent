# 💈 AI Barber Shop Booking Automation Workflow (n8n)

This project is an **AI-powered Barber Shop Booking System** built using **n8n** — designed to automate appointment bookings, notifications, and record management for barber shops and small businesses.

---

## 🧠 Project Overview

The **AI Barber Booking Workflow** allows customers to chat naturally with an AI assistant to book appointments.  
It automatically saves client data, sends notifications, and keeps both the **shop owner** and the **client** updated — without any manual effort.

This workflow integrates:
- AI Chatbot (Google Gemini Model)
- Google Sheets for data storage
- Gmail for email notifications
- WhatsApp messages for instant owner alerts

---

## ⚙️ Workflow Structure

### 1️⃣ Barber Shop Chatbot
- Collects client booking details (Name, Email, Phone, Service, Date & Time)
- Validates time between **10 AM – 11 PM Pakistan Time**
- Saves booking record to **Google Sheet**
- Sends confirmation to the client
- Notifies the shop owner via **Email**

### 2️⃣ Send Latest Booking to Owner on WhatsApp
- Automatically triggers when a new booking is added in the Google Sheet
- Sends WhatsApp notification with booking details to the owner in real-time

---

## 💡 Features

✅ AI-powered booking chatbot  
✅ Automated email notifications to owner  
✅ Real-time WhatsApp alerts  
✅ Google Sheet record-keeping  
✅ Timezone awareness (Asia/Karachi)  
✅ Simple and professional customer experience  
✅ Fully scalable for other businesses  

---

## 🏗️ Workflow Components

| Component | Description |
|------------|-------------|
| **Webhook Node** | Receives user data from website chatbot |
| **AI Agent Node (Gemini Model)** | Handles natural conversation with client |
| **Simple Memory Node** | Retains session memory between messages |
| **Google Sheets Node** | Stores all booking data |
| **Gmail Node** | Sends formatted booking emails to the shop owner |
| **WhatsApp Node** | Sends instant alerts when a new record is added |

---

## ✂️ Available Services

| Service | Description | Price |
|----------|--------------|-------|
| **The Golden Shave** | Hot towel, straight razor, facial massage, oils & aftershave balm | $55 |
| **The Master Cut** | Expert haircut tailored to style, with precise neck shave & styling | $45 |
| **Beard Sculpting** | Line up, trim, shaping with clippers and premium oils & balms | $35 |

---

## 🧭 Use Cases

This workflow is not limited to barber shops — it can be adapted for:

- 💆‍♂️ **Salons & Spas** – Manage client bookings effortlessly  
- 🏥 **Clinics & Therapists** – Automate appointment reminders  
- 🎓 **Coaches & Trainers** – Collect and manage client sessions  
- 🏡 **Home Services** – Streamline scheduling and notifications  

---

## 🧑‍💻 User Manual

### 🪄 Step 1: Client Interaction
The chatbot greets the client and asks for:
- Full Name  
- Email  
- Phone Number  
- Service Type  
- Preferred Date & Time (10 AM – 11 PM)

### 🪄 Step 2: Booking Confirmation
After collecting all data, the chatbot replies:
> ✅ Thank you for booking a slot with us. We’ll confirm your appointment very soon.

### 🪄 Step 3: Notification to Owner
- The shop owner receives an **email** with all booking details.
- The booking record is added to the **Google Sheet**.
- A **WhatsApp message** is automatically sent to the owner.

### 🪄 Step 4: Record Management
All booking data is stored safely in the “Client Booking Sheet” for tracking and reporting.

---

## 🕒 Working Hours
> **10:00 AM – 11:00 PM (Asia/Karachi timezone)**  
All bookings outside this window are politely declined.

---

## 🧰 Tech Stack

- **n8n** (Workflow Automation)
- **Google Gemini AI Model**
- **Google Sheets API**
- **Gmail API**
- **WhatsApp API**
- **Webhook Integration**

---

## 📽️ Project Presentation

This project was first published a month ago and now re-introduced with a **video demonstration**.  
Special thanks to **Sir Zafar Iqbal** 🙏 for encouraging us to face the camera confidently and showcase our skills to the world.

---

## 🚀 Call to Action

If you want a **custom AI booking chatbot** for your salon, clinic, or any service-based business —  
I can help you build it using **n8n** and **AI automation tools**.

📩 **Let’s connect!**  
Email: yourname@email.com  
LinkedIn: [Your LinkedIn Profile](https://linkedin.com)  
Website: [Your Portfolio or Company Website](https://yourwebsite.com)

---

### ⭐ Don’t forget to star this repository if you found it useful!  
> “Automate your business. Save time. Serve smarter.”  


---

## 📞 Contact

**Developer:** Abdullah Shahzad  
**Email:** support@xpertswp.com  
**Website:** [https://xpertswp.com](https://xpertswp.com)

💡 *If you need a custom automation workflow or chatbot integration for your business — Let’s collaborate!*

