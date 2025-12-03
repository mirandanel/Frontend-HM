

# Hotel Management System

🏨 Hotel Management System

A modern, responsive hotel management web application for managing rooms, guests, and bookings with an elegant and intuitive user interface.

🔗 BASE URL
🌐 FRONTEND URL

➡ https://frontend-hm-7afd.vercel.app/

🛠 BACKEND URL (API BASE URL)

➡ https://hotelmanangementapi-2.onrender.com


## ✨ Features

### 📊 **Dashboard**
- ✅ Real-time statistics overview
- ✅ Recent bookings, guests, and rooms display  
- ✅ Interactive tab system for easy navigation

### 🏨 **Room Management**

| Action            | Method | Endpoint         | Body                              |
| ----------------- | ------ | ---------------- | --------------------------------- |
| Get all rooms     | GET    | `/api/rooms`     | —                                 |
| Get a single room | GET    | `/api/rooms/:id` | —                                 |
| Create room       | POST   | `/api/rooms`     | `{ number, type, price, status }` |
| Update room       | PUT    | `/api/rooms/:id` | `{ number, type, price, status }` |
| Delete room       | DELETE | `/api/rooms/:id` | —                                 |

- ✅ Add, edit, and delete rooms
- ✅ Room types: Single, Double, Suite, Deluxe
- ✅ Status tracking (available/occupied)
- ✅ Price management per night

### 👥 **Guest Management**

| Action       | Method | Endpoint          | Body                     |
| ------------ | ------ | ----------------- | ------------------------ |
| Get guests   | GET    | `/api/guests`     | —                        |
| Get guest    | GET    | `/api/guests/:id` | —                        |
| Create guest | POST   | `/api/guests`     | `{ name, email, phone }` |
| Update guest | PUT    | `/api/guests/:id` | `{ name, email, phone }` |
| Delete guest | DELETE | `/api/guests/:id` | —                        |

- ✅ Add, edit, and delete guest profiles
- ✅ Contact information storage (name, email, phone)
- ✅ Guest history tracking

### 📅 **Booking Management**

| Action         | Method | Endpoint            | Body                                             |
| -------------- | ------ | ------------------- | ------------------------------------------------ |
| Get bookings   | GET    | `/api/bookings`     | —                                                |
| Get booking    | GET    | `/api/bookings/:id` | —                                                |
| Create booking | POST   | `/api/bookings`     | `{ guestId, roomId, checkIn, checkOut, status }` |
| Update booking | PUT    | `/api/bookings/:id` | `{ guestId, roomId, checkIn, checkOut, status }` |
| Delete booking | DELETE | `/api/bookings/:id` | —                                                |

- ✅ Create, edit, and delete bookings
- ✅ Integrated guest and room selection
- ✅ Date validation and conflict prevention
- ✅ Booking status tracking (booked, checked-in, checked-out, cancelled)

## 🛠️ Tech Stack

### **Frontend**
- HTML5
- CSS3
- Vanilla JavaScript
- Font Awesome 6.4.0 (Icons)
- Google Fonts (Playfair Display & Inter)

### **Backend**
- Node.js
- Express.js
- MongoDB (or your database)

### **Styling**
- Custom CSS with CSS variables for theming
- Responsive design
- Modern UI components

# 🚀 Installation & Setup

**Option 1: Local Development**
```bash
##Clone the repository
git clone https://github.com/yourusername/hotel-management-system.git

#Navigate to project directory
cd hotel-management-system

#Open in browser
open index.html



Option 2: Direct Access
Simply open index.html in any modern web browser.

📁 Project Structure

hotel-management-system/
│
├── index.html              # Main HTML file
├── style.css               # All styles and responsive design
├── app.js                  # Core application logic
│
├── assets/                 # Images, icons, etc.
│   └── screenshots/        # Application screenshots
│
├── Features:
│   ├── 📊 Dashboard with real-time stats
│   ├── 🏨 Room management
│   ├── 👥 Guest management
│   └── 📅 Booking management
│
└── Components:
    ├── Responsive navigation
    ├── Modal forms
    ├── Interactive tables
    ├── Notification system
    └── Confirmation dialogs


📸 **Screenshots**


