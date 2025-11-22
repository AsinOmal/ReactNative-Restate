---

# React Native Real Estate App

[![React Native](https://img.shields.io/badge/React%20Native-Mobile-blue?logo=react)](https://reactnative.dev/)
[![Expo](https://img.shields.io/badge/Expo-SDK%2052-black?logo=expo)](https://expo.dev/)
[![Appwrite](https://img.shields.io/badge/Appwrite-Backend-pink?logo=appwrite)](https://appwrite.io/)
[![License](https://img.shields.io/badge/License-MIT-green)](LICENSE)

A full-stack real estate app with Google sign-in, dynamic property listings, and user profiles. Built with Expo SDK 52, Appwrite, Tailwind CSS, NativeWind, and TypeScript to keep the project clean and scalable.

---

## 📦 Features

- **Google sign-in** for quick access
- **Home page** with recent and recommended listings, search, and filters
- **Explore page** to browse all property types
- **Property details page** with images and key data
- **Profile page** for user info and settings
- **Centralized data fetching** with a simple useQuery-like approach
- Extra improvements in structure and component reuse

---

## ⚙️ Tech Stack

### **Expo**

### **React Native**

### **Appwrite**

### **TypeScript**

### **NativeWind**

---

## 🛠️ Getting Started

### ✅ Prerequisites

Make sure you have:

- Git
- Node.js
- npm
- An Android/iOS emulator or a physical device

---

### 🚀 Installation

#### 1. **Clone the repository**

```bash
git clone https://github.com/AsinOmal/ReactNative-Restate.git)
cd react_native-restate
```

#### 2. **Install dependencies**

```bash
npm install
```

#### 3. **Set up environment variables**

Create a file named **.env.local** in the project root and add:

```
EXPO_PUBLIC_APPWRITE_ENDPOINT=https://cloud.appwrite.io/v1
EXPO_PUBLIC_APPWRITE_PROJECT_ID=
EXPO_PUBLIC_APPWRITE_DATABASE_ID=
EXPO_PUBLIC_APPWRITE_GALLERIES_COLLECTION_ID=
EXPO_PUBLIC_APPWRITE_REVIEWS_COLLECTION_ID=
EXPO_PUBLIC_APPWRITE_AGENTS_COLLECTION_ID=
EXPO_PUBLIC_APPWRITE_PROPERTIES_COLLECTION_ID=
```

Fill in your Appwrite values from your Appwrite project dashboard.

#### 4. **Start the app**

```bash
npx expo start
```

You can open the app in:

- a development build
- an Android emulator
- an iOS simulator
- Expo Go (limited sandbox)

Edit files inside the **app** folder to start building.

---

## 🔑 Environment Variables

All Appwrite values must go into `.env.local`:

- API endpoint
- Project ID
- Database ID
- Collection IDs

These values come from your Appwrite console.

---

## 🚀 Deployment

Expo provides a straightforward workflow:

**Build for production:**

```bash
npx expo run:android --variant release
```

```bash
npx expo run:ios --configuration Release
```

You can also build with **EAS**:

```bash
eas build -p android
eas build -p ios
```

Upload the generated builds to the Play Store or the App Store.

---

## 🤝 Contributing

1. Fork the repository
2. Create a branch (`git checkout -b feature-name`)
3. Commit your changes
4. Push the branch
5. Open a pull request

---

## 📜 License

This project is licensed under the MIT License.

---
