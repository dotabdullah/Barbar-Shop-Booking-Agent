# Barbar-Shop-Booking-Agent
This project is an AI-powered Booking Workflow designed for a Barber Shop website chatbot. It automates the entire appointment booking process — from client submission to owner approval and email notifications — ensuring a smooth, real-time, and professional experience for both customers and the shop owner.

# 💈 AI-Powered Barber Shop Booking Workflow


## 🧠 Overview
This project is an **AI-powered Booking Workflow** designed for a **Barber Shop website chatbot**.  
It automates the complete appointment booking process — from collecting client details to owner confirmation and automated email notifications — providing a **smooth and professional experience** for both the customer and shop owner.

---

## ⚙️ How It Works

1. **Client Interaction via Chatbot**
   - The client provides:
     - Full Name  
     - Email Address  
     - Phone Number  
     - Desired Booking Date & Time  
   - Once all details are submitted, the chatbot replies instantly:
     > “Thank you for booking a slot! We’ll confirm your booking very soon.”

2. **Automatic Email to Shop Owner**
   - The system sends a booking notification email to the shop owner with all client details.
   - The owner can **approve** or **reject** the booking request.

3. **Automatic Client Notification**
   - Once the owner takes action:
     - ✅ Approved → Client receives a confirmation email.  
     - ❌ Rejected → Client receives a polite rejection email.

4. **Record Keeping**
   - Every booking (with approval/rejection status) is automatically logged in a **Google Sheet** named **“Client Booking Sheet”**.

---

## 🧩 Tools & Technologies

| Component | Purpose |
|------------|----------|
| **n8n (Workflow Automation)** | Core engine for booking automation |
| **Chatbot Integration** | Collects user booking data via website |
| **Google Sheets** | Stores and tracks all booking records |
| **Email Nodes** | Sends emails to both shop owner and clients |
| **Asia/Karachi Timezone** | Ensures accurate local booking time |

---

## 🕒 Workflow Logic

Client Chat → Collect Details → Confirm Message → 
Send Email to Owner → Await Approval → 
Send Response to Client → Log Record in Google Sheet

---

## 🧠 Key Features

- ✅ Fully Automated Booking System  
- 💬 Smart Chatbot Interaction  
- 💌 Dynamic Email Notifications  
- 🧾 Google Sheets Integration  
- 🌍 Local Timezone Accuracy (Asia/Karachi)  
- 🔁 Real-time Owner-Client Communication  

---

## 🌍 Ideal Use Cases

This automation is ideal for small service-based businesses such as:

- Barber Shops  
- Hair Salons  
- Beauty Clinics  
- Personal Trainers  
- Home Services  

It saves time, reduces manual errors, and ensures instant communication between client and owner.

---

## 🚀 Future Enhancements

- 💳 Add Payment Gateway Integration (Stripe / PayPal)  
- 📱 Include SMS Notifications for Bookings  
- 📊 Create Admin Dashboard for Analytics  
- 🤖 Add AI for Smart Slot Recommendation  

---

## 📁 Project Structure

📦 Barber-Booking-Workflow
 ┣ 📜 README.md
 ┣ 🖼️ Banner Image
 ┣ ⚙️ Workflow (n8n JSON Export)
 ┗ 📊 Client Booking Sheet (Google Sheet Integration)

---

## 📞 Contact

**Developer:** Abdullah Shahzad  
**Email:** support@xpertswp.com  
**Website:** [https://xpertswp.com](https://xpertswp.com)

💡 *If you need a custom automation workflow or chatbot integration for your business — Let’s collaborate!*

