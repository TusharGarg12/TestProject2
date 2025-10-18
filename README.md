# 🧭 TripMate – Your Smart Travel Companion

TripMate is a modern Android application built with **Jetpack Compose** that helps travelers plan, manage, and enhance their trips using **AI assistance**, **budget awareness**, and **real-time location data**.  
It offers personalized trip suggestions, user authentication, and a clean, beautiful UI.

---

## ✨ Features

### 👤 Authentication
- Secure **Login / Signup** with Firebase Authentication  
- Supports **Google Sign-In** (optional)  
- Forgot and Reset password screens  

### 🏠 Home Screen
- Greets the user dynamically using their **name and current city**  
- Displays a **modern TopAppBar** with profile menu  
- Includes a **navigation drawer** for Profile, Trips, Settings, and Logout  

### 🧠 AI Trip Assistant
- Pops up a **smart AI dialog** that asks 5 quick questions  
- Dynamically uses the user’s **current location** and **budget** to provide tailored trip recommendations  
- Suggests **affordable travel plans**, accommodations, and activities based on budget range  
- Displays interactive **suggestion cards** (e.g., destination ideas, activities, and trip duration)

### 💰 Budget-Aware Recommendations
- Constantly analyzes user’s **budget** and **query preferences**  
- Adjusts suggestions dynamically (e.g., economical getaways, premium resorts, adventure trips, etc.)  
- Learns from user feedback for future recommendation refinement  

### 📍 Location Awareness
- Detects user’s **current city** using Android’s FusedLocationProviderClient and Geocoder  
- Dynamically updates UI greetings like “Enjoying your stay at Mumbai?”

### 🎨 Modern UI
- 100% built using **Jetpack Compose (Material 3)**  
- Adaptive, clean, and responsive design  
- Smooth transitions and intuitive layout hierarchy  

---

## 🛠️ Tech Stack

| Category | Tools / Libraries |
|-----------|-------------------|
| Language | Kotlin |
| UI | Jetpack Compose (Material 3, Accompanist) |
| Navigation | Jetpack Navigation Component |
| Authentication | Firebase Auth |
| Database (optional) | Firebase Firestore |
| Location | FusedLocationProviderClient + Geocoder |
| AI Logic | Rule-based or Gemini API (planned) |
| Icons | Material Icons / custom vector assets |
