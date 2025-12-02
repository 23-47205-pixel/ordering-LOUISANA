A comprehensive web-based ordering system for a fictional donut shop called "Donut Bliss". This system features three distinct user roles with different capabilities and interfaces.

🌟 Features
Multi-User System
Customer: Browse menu, place orders, track order status, view history

Staff: Manage and update order statuses

Admin: Full system control including menu management and user administration

Customer Features
User registration and login

Browse complete donut menu with images and descriptions

Add items to cart with quantity control

Multiple delivery options (Pickup, Grab, FoodPanda)

Multiple payment methods (Cash, GCash, PayMaya)

Order tracking with visual status indicator

Order history with detailed tracking

About Us and Mission & Vision pages

Staff Features
View all customer orders

Update order status through workflow:

Confirmed → Preparing → Ready → Picked Up/Delivered → Completed

Cancel orders when needed

View About Us and Mission & Vision pages

Admin Features
Complete order overview with all customer orders

Menu management (add, edit, delete items)

User management (add, edit, delete users)

System configuration pages

🛠️ Technologies Used
HTML5: Structure and content

CSS3: Styling with custom variables and responsive design

JavaScript: Dynamic functionality and interactivity

Font Awesome: Icons for enhanced UI

Unsplash: Default donut images

Responsive Design: Works on mobile, tablet, and desktop

🚀 Getting Started
Prerequisites
Modern web browser (Chrome, Firefox, Safari, Edge)

No additional installation required

How to Use
Open index.html in your web browser

Start at the login page with three user types

Default Login Credentials
Customer Accounts
Username: customer1 | Password: customer1

Username: customer2 | Password: customer2

Staff Account
Username: staff | Password: staff1234

Admin Account
Username: admin | Password: admin1234

Customer Registration
Password must be at least 8 characters

Must contain both letters and numbers

Cannot be all numbers

📱 Key Functionalities
Ordering Process
Browse menu items with images and descriptions

Add items to cart with quantity controls

Select delivery method (pickup/delivery)

Choose payment method

Place order (cart automatically clears after order)

Track order status in real-time

Order Status Flow
Confirmed → Order received and confirmed

Preparing → Donuts being prepared in kitchen

Ready → Order ready for pickup/dispatch

Picked Up → Customer has collected order

On the Way → Order being delivered

Completed → Order successfully fulfilled

Cancelled → Order cancelled by staff/customer

Failed → Delivery failed

Admin Capabilities
Add new menu items with image upload

Edit existing menu items

Delete menu items

Add new users with different roles

Edit user information

Delete users

View complete order statistics

🎨 Design Features
Color Scheme
Primary: Blue theme (#4a90e2)

Secondary: Light blue (#87ceeb)

Accent: Muted blue (#6ab0de)

Clean, modern interface with consistent styling

Responsive Design
Mobile-first approach

Collapsible sidebar on mobile

Adjustable grid layouts

Touch-friendly buttons

UI Components
Toast notifications for user feedback

Animated cart icon

Order tracking visualization

Interactive tables with action buttons

Form validation

Image preview for uploads

📁 Project Structure
text
donut-bliss/
│
├── index.html          # Main application file
├── README.md           # This documentation file
└── logo.jpg            # Brand logo (if available)
🔧 Code Organization
CSS Structure
Root variables for consistent theming

Organized by page sections

Responsive breakpoints at 768px and 480px

Animation keyframes for interactions

JavaScript Structure
Menu items data (20+ donut varieties)

Orders data with sample orders

Users data with default accounts

Modular functions for different user roles

Event listeners for interactive elements

Data Management
In-memory data storage (resets on page refresh)

Cart management with local storage simulation

Order status updates in real-time

🎯 Key Features for Each Role
Customer
Intuitive shopping experience

Real-time cart updates

Order confirmation with details

Visual order tracking

Order history with status

Staff
Clean order management interface

Quick status updates

Clear order information display

Simple navigation

Admin
Comprehensive dashboard

Data management tools

System configuration options

Complete oversight capabilities

🐛 Known Limitations
Data resets on page refresh (no persistent storage)

Image uploads use base64 encoding (not ideal for production)

No server-side validation

Limited error handling for edge cases

📈 Future Enhancements
Backend Integration

Database for persistent storage

User authentication with sessions

Image upload to server

Enhanced Features

Email notifications

Order modification

Discount codes and promotions

Customer reviews and ratings

Business Features

Sales reporting and analytics

Inventory management

Staff scheduling

Customer loyalty program

Mobile App

Native iOS/Android applications

Push notifications

Geolocation for delivery tracking

🤝 Contributing
This is a demonstration project. For production use, consider:

Adding proper backend implementation

Implementing user authentication

Adding database persistence

Enhancing security measures

📄 License
This project is for educational and demonstration purposes.

🙏 Acknowledgments
Font Awesome for icons

Unsplash for images

Modern web standards and browser capabilities

