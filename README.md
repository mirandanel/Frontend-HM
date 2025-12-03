# FRONTEND URL = https://frontend-hm-7afd.vercel.app/
# BACKEND URL =  https://hotelmanangementapi-2.onrender.com
 Hotel Management System
A modern, responsive hotel management web application for managing rooms, guests, and bookings with an elegant user interface.

Features
📊 Dashboard
Real-time statistics overview

Recent bookings, guests, and rooms display

Interactive tab system for easy navigation

🏨 Room Management
Add, edit, and delete rooms

Room types: Single, Double, Suite, Deluxe

Status tracking (available/occupied)

Price management per night

👥 Guest Management
Add, edit, and delete guest profiles

Contact information storage (name, email, phone)

Guest history tracking

📅 Booking Management
Create, edit, and delete bookings

Integrated guest and room selection

Date validation and conflict prevention

Booking status tracking (booked, checked-in, checked-out, cancelled)

Tech Stack
Frontend: HTML5, CSS3, Vanilla JavaScript

Icons: Font Awesome 6.4.0

Fonts: Playfair Display & Inter from Google Fonts

Styling: Custom CSS with CSS variables for theming

Backend Integration Ready: Configured with API base URL

Installation & Setup
Clone or download the project files

Open index.html in a modern web browser

No additional dependencies required - works out of the box

Backend Integration
To connect to a backend API:

Update the API_BASE_URL in app.js:

javascript
const API_BASE_URL = 'https://your-backend-api-url.com';
Implement API calls in the existing functions (currently using sample data)

Project Structure
text
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
Usage Instructions
Adding a Room
Navigate to "Rooms" section

Click "Add New Room"

Fill in room details (number, type, price, status)

Click "Save Room"

Adding a Guest
Navigate to "Guests" section

Click "Add New Guest"

Enter guest information

Click "Save Guest"

Creating a Booking
Navigate to "Bookings" section

Click "Create New Booking"

Select guest and available room

Choose dates (check-out must be after check-in)

Set booking status

Click "Save Booking"

Editing/Deleting Items
Click the "Edit" button on any item to modify

Click the "Delete" button to remove (with confirmation)

Responsive Design
The application is fully responsive and works on:

Desktop computers

Tablets

Mobile phones

Mobile features:

Collapsible navigation menu

Optimized tables for small screens

Touch-friendly buttons and forms

Customization
Theme Colors
Modify CSS variables in style.css:

css
:root {
    --primary-color: #1a365d;
    --secondary-color: #c9a96e;
    --accent-color: #2d3748;
    /* ... other variables */
}
Adding Room Types
Edit the room type dropdown in both index.html and app.js to add new room categories.

Browser Compatibility
Chrome (recommended)

Firefox

Safari

Edge

Opera

Future Enhancements
Potential features to add:

Backend API integration

User authentication

Payment processing

Reporting and analytics

Email notifications

Room cleaning schedule

Inventory management

License
© 2023 Grand Luxe Hotel. All rights reserved.

Support
For issues or questions:

Check browser console for errors

Ensure JavaScript is enabled

Verify date formats are valid

Clear browser cache if needed
