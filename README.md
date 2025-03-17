# 🚑 Fastlance - Ambulance Booking System

## Overview
Fastlance is an ambulance booking system designed to provide quick and efficient emergency medical services. It is built using **Python and Flask** for the backend and utilizes **MongoDB Atlas** as the database for managing ambulance bookings. The front-end is developed using **HTML, CSS, and JavaScript**, offering an intuitive interface for users.

## Features
- **User Registration & Login**: Secure authentication system for patients and emergency contacts.
- **Ambulance Booking**: Allows users to book an ambulance with real-time availability tracking.
- **Admin Panel**: Enables administrators to manage bookings and monitor ambulance dispatch.
- **Location Tracking**: Integration with maps for real-time ambulance tracking.
- **Emergency Alerts**: Sends notifications to users and hospitals upon booking.
- **Optimized Route Planning**: AI-powered traffic optimization for faster response times.

## Installation
Clone the repository and install the required dependencies:
```bash
git clone https://github.com/shreyachakote2004/Fastlance.git
cd Fastlance
pip install -r requirements.txt
```

## Usage
### 1. Start the Flask Server
```bash
python app.py
```
The application will be available at `http://localhost:5000`

### 2. Run the Front-End
Open `index.html` in a web browser or deploy it on a web server.

### 3. Access the Admin Panel
Login as an admin to manage bookings and monitor ambulance status.

## API Endpoints
- **`/register`** - User registration
- **`/login`** - User authentication
- **`/book-ambulance`** - Book an ambulance
- **`/admin/bookings`** - View and manage bookings (Admin access required)
- **`/track-ambulance/<booking_id>`** - Real-time tracking

## Database Structure
MongoDB Atlas is used to store:
- **User Data**: Name, contact details, medical history
- **Booking Data**: Request time, location, assigned ambulance
- **Ambulance Status**: Availability, location updates

## Future Enhancements
- **Mobile App Integration**
- **AI-based Emergency Predictions**
- **Voice Command Booking Support**

