
# BrandPeek – Mini Brand Discovery App

A **React Native app** built using **Expo** that simulates a *Brand Discovery experience*. This project was developed as part of the **React Native Internship Assignment**.

---

## 🎯 Objective
To create a polished mobile app with:
- Modular React Native folder structure.
- Gradient styling with a radial background.
- API integration for fetching and displaying brand data.
- Deployment using **ExpoGo** or APK.

---

## 📱 Features
- **Home Screen**
  - Radial gradient background (deep blue glow fading to near-black).
  - Header: *“Top Brands Today”*.
  - Displays a list of 5–10 brands (Name, Logo, One-liner description) fetched from an API.
  - Tap on a brand to view detailed info.

- **Brand Detail Screen**
  - Shows full brand details.
  - Includes a *Follow* button (non-functional).
  - Subtle gradient background for a clean UI.

---

## 📂 Folder Structure
```
/components      # Reusable UI components
/screens         # HomeScreen & BrandDetailScreen
/assets          # Images and icons
/services        # API calls and backend integration
/navigation      # App navigation setup
/constants       # Static constants and theme
/utils           # Helper functions
App.js           # Entry point
```

---

## 🎨 UI & Styling
- Gradient backgrounds implemented using:
  - **react-native-svg** with `<RadialGradient>`  
    OR  
  - **expo-linear-gradient** fallback.
- Clean and minimal UI with proper spacing, fonts, and visual hierarchy.
- Style inspired by [nurdd.club](http://www.nurdd.club).

---

## 🔗 API
- Data fetched from **MockAPI** or **Reqres**.
- Endpoints:
  - `GET /brands` → Fetch all brands
  - `GET /brands/:id` → Fetch brand details

---

## ✅ How to Run the Project
### 1. Clone the Repository
```bash
git clone <your-repo-link>
cd BrandPeek
```

### 2. Install Dependencies
```bash
npm install
```

### 3. Start the App
```bash
npx expo start
```
Scan the QR code using the **Expo Go** app (iOS/Android) to run the app.

---

## ✅ Submission Details
- **Backend Used**: MockAPI
- **Project Structure**: Modular with separate folders for screens, components, services, and assets.
- **Deployment**: Shared via ExpoGo link or APK.

---

## 🏆 Evaluation Criteria
- Clean and modular code structure.
- Proper API integration and error handling.
- Accurate gradient recreation.
- Responsive and visually appealing UI.

---

### 🔗 Live Preview
- **ExpoGo Link / QR Code**: *[Add here once deployed]*
- **GitHub Repo**: *[Add your repo link here]*
