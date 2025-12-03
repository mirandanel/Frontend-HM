🏨**Hotel Management System**

A modern, responsive hotel management web application for managing rooms, guests, and bookings with an elegant user interface.

BASE URL

# FRONTEND URL = https://frontend-hm-7afd.vercel.app/

# BACKEND URL =  https://hotelmanangementapi-2.onrender.com

**Features**

📊 **Dashboard**

*Real-time statistics overview

*Recent bookings, guests, and rooms display

*Interactive tab system for easy navigation 

🏨 **Room Management**

Add, edit, and delete rooms

Room types: Single, Double, Suite, Deluxe

Status tracking (available/occupied)

Price management per night

👥**Guest Management**

Add, edit, and delete guest profiles

Contact information storage (name, email, phone)

Guest history tracking

📅 **Booking Management**

Create, edit, and delete bookings

Integrated guest and room selection

Date validation and conflict prevention

Booking status tracking (booked, checked-in, checked-out, cancelled)

**Tech Stack**

**Frontend: HTML5**, CSS3, Vanilla JavaScript

**Icons**: Font Awesome 6.4.0

**Fonts**: Playfair Display & Inter from Google Fonts

**Styling**: Custom CSS with CSS variables for theming

**Backend Integration Ready:** Configured with API base 

**Installation & Setup**

****Clone or download** the project files

**Open** index.html in a modern web browser

**No additional dependencies required** - works out of the box

**Backend Integration**

To connect to a backend API:

1. Update the API_BASE_URL in app.js:

const API_BASE_URL = 'https://your-backend-api-url.com';

2. Implement API calls in the existing functions (currently using sample data)

**Project Structure**

hotel-management-system/
│
├── index.html          # Main HTML file
├── style.css           # All styles and responsive design
├── app.js              # Core application logic
│
├── Features:
│   ├── Dashboard with real-time stats
│   ├── Room management
│   ├── Guest management
│   └── Booking management
│
└── Components:
    ├── Responsive navigation
    ├── Modal forms
    ├── Interactive tables
    ├── Notification system
    └── Confirmation dialogs

****Usage Instruction

Adding a Room**

**1**. Navigate to "Rooms" section

**2**. Click "Add New Room"

**3**. Fill in room details (number, type, price, status)

**4**. Click "Save Room"

