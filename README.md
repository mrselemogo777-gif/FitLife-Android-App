# FitLife-Android-App
Native Android fitness application built with Java and SQLite featuring user authentication, workout CRUD operations, and SMS delegation. 
# FitLife – Android Fitness Management App

FitLife is a native Android fitness application developed using Java and SQLite.  
The app enables users to securely register, log in, create and manage workouts, track completion status, and delegate workout plans via SMS.

Developed as part of CET343 – Advanced Android Mobile Development

---

##  Project Overview

FitLife was designed to demonstrate advanced native Android development principles, including:

- User authentication
- Local database persistence using SQLite
- CRUD operations
- Material Design implementation
- SMS integration using Android implicit intents

The application follows a structured MVC-inspired architecture and adheres to Android development best practices.

---

##  Core Features

### User Authentication
- User registration
- Secure login validation
- Duplicate username prevention
- Input validation and error feedback

###  Workout Management (CRUD)
- Create new workouts
- View all saved workouts
- Edit workout details
- Delete workouts with confirmation
- Toggle workout completion status

### SMS Delegation
- Send workout details via device SMS application
- Pre-filled workout content
- Uses Android implicit intent system

###  UI & UX
- Material Design 3 principles
- Responsive layouts using ConstraintLayout
- Consistent spacing and accessibility standards
- Smooth activity transitions

---

## Technologies Used

| Technology | Purpose |
|------------|----------|
| Java (1.8) | Core application logic |
| Android Studio | Development IDE |
| SQLite | Local data persistence |
| XML Layouts | UI design |
| Material Components | Modern UI styling |
| Android SDK (API 21–33) | Platform compatibility |

---

## Architecture

The application follows a modified MVC structure:

- **Model Layer:**  
  `DatabaseHelper.java`, `User.java`, `Workout.java`

- **View Layer:**  
  XML layout files

- **Controller Layer:**  
  Activity classes managing logic and UI interaction

This structure improves maintainability and separation of concerns.

---

##  Minimum Requirements

- Android 5.0 (API 21) or higher
- Android Studio 2022.3.1 or later

---

##  Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/YOUR_USERNAME/FitLife-Android-App.git
