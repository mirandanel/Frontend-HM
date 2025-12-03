

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

🚀 Installation & setup

 option 1: local development

  bash

  # Clone the repository
git clone https://github.com/yourusername/hotel-management-system.git

# Navigate to project directory
cd hotel-management-system

# Open in browser
open index.html


**Option 2: Direct Access**
Simply open index.html in any modern web browser.

📁 **Project Structure**
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

<img width="1340" height="693" alt="image" src="https://github.com/user-attachments/assets/ec491b06-a5db-41a1-9bad-f9ac889c1a7b" />

<img width="1366" height="679" alt="image" src="https://github.com/user-attachments/assets/6fadf59e-0d64-4423-b095-92d466a2c089" />

<img width="1338" height="729" alt="image" src="https://github.com/user-attachments/assets/cdbcf653-65aa-443f-b963-4a526185232e" />


📱 **Responsive Design**
The application is fully responsive and works on:

✅ Desktop computers

✅ Tablets

✅ Mobile phones

**Mobile features:**

Collapsible navigation menu

Optimized tables for small screens

Touch-friendly buttons and forms

Adaptive layouts

🎨 **Customization**

**Theme Colors**

Modify CSS variables in style.css:

:root {
    --primary-color: #1a365d;
    --secondary-color: #c9a96e;
    --accent-color: #2d3748;
    --light-color: #f8f9fa;
    --dark-color: #2d3748;
    --success-color: #38a169;
    --warning-color: #dd6b20;
    --danger-color: #e53e3e;
}

**Adding Room Types**

Edit the room type dropdown in both index.html and app.js to add new room categories.
**
🌐 **API Integration****

**Backend Setup**
Update the API_BASE_URL in app.js:

const API_BASE_URL = 'https://hotelmanangementapi-2.onrender.com';

✅ **Browser Compatibility**

✅ Chrome (recommended)

✅ Firefox

✅ Safari

✅ Edge

✅ Opera

**🔮 Future Enhancements**

User authentication & authorization

Payment processing integration

Advanced reporting & analytics

Email notifications system

Room cleaning schedule management

Inventory management

Multi-language support

Dark mode theme

**📞 Support**

For issues or questions:

Check browser console for errors

Ensure JavaScript is enabled

Verify date formats are valid

Clear browser cache if needed

Contact: your-email@example.com

**📄 License**

© 2023 Grand Luxe Hotel. All rights reserved







