# 💰 Billionaire App – Flutter

A simple Flutter application that simulates growing your bank balance by pressing a button.  
The app demonstrates **state management**, **persistent storage using SharedPreferences**, and **clean widget separation**.

---

## 📱 App Overview

The **Billionaire App** allows users to:
- View their current bank balance
- Add money with a single button tap
- Persist balance data even after closing the app

This project is ideal for beginners learning **Flutter state**, **local storage**, and **UI composition**.

---

## ✨ Features

- 💵 Add money to balance with a button
- 💾 Persistent balance using `SharedPreferences`
- 📊 Formatted currency display
- 🌙 Dark Material 3 theme
- 🧩 Clean separation of widgets
- 🚀 Beginner-friendly Flutter project

---

## 🧠 Concepts Used

- Stateful & Stateless Widgets
- `setState()` for UI updates
- `SharedPreferences` for local storage
- Widget composition
- Flutter layout with `Column` & `Expanded`
- Currency formatting using `intl`

---

## 📂 Project Structure

```text
lib/
├── add_money_button.dart   # Button widget to add money
├── balance_view.dart       # Displays formatted balance
└── main.dart               # App entry point & state logic
```
---
## 🧩 Main Functionality
### 💰 Add Money
- Adds 500 to the balance on each button press 
- Updates UI instantly 
- Saves balance locally using SharedPreferences

### 💾 Persistent Storage
- Balance is saved locally 
- App restores last saved balance on restart
---


### Step 1: Clone the Repository
```bash
git clone https://github.com/MuaazTasawar/Billionare-App.git
cd billionare_app
```
### Step 2: Install Dependencies
```bash
flutter pub get
```
### Step 3: Run the App
```bash
flutter run
```
---
## 🎯 Learning Purpose
```text
This app is created for educational purposes, helping developers learn:
 - Flutter state management 
 - Local data persistence 
 - Reusable widgets
 - UI updates with setState()
```
---
## 📄 License
```text
Distributed under the MIT License. See LICENSE for more information.
```
---
#### Note: This app is for learning purposes only and does not represent real financial data.
---