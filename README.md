# CS 3338 Final Project – Group 6  
## Sleep Fixer App

**Jira Project URL:**  
https://calstatela-cs3338-fall2025group6.atlassian.net/jira/software/projects/T6SFA/boards/233

---

## Team
- Dang Nguyen  
- Rafael Caldera  
- Yohei Oya  
- Yuanwei Chen  

---

## Overview
The **Sleep Fixer App** is a mobile application for iOS and Android that helps users gradually improve their sleeping habits. Users enter their current sleep schedule and desired sleep goals, and the app generates a personalized plan with incremental adjustments to guide them toward their target bedtime and wake time.

The app provides four main screens:

- **Create Plan**  
- **View Plans**  
- **AI Info**  
- **Dashboard**

Based on the user’s selected shift options, the app calculates and recommends optimal sleep schedules.

---

## System Architecture
The application workflow includes:

1. **User Input:** Users enter current sleep schedule and goals using time sliders.
2. **Plan Generation:** The app generates a customized sleep schedule using the selected shift options.
3. **Local Storage:** Data is stored locally using Hive, enabling offline access.
4. **Notifications:** Sends reminders 30 minutes before bedtime and morning check-ins.
5. **Progress Tracking:** Tracks streaks and generates weekly reports on the dashboard.
6. **AI Assistant:** Optional cloud-based AI trained on Harvard sleep studies.
7. **Cloud Backup:** Optional Firebase backup for syncing data and enabling social features.

---

## Features

### Mobile Application
- Sleep plan creation with time sliders  
- Two selectable shift options  
- Plan editing and deletion  
- Streak counter and weekly reports  
- Sleep journal  
- Smart insights and PDF export  
- AI assistant trained on Harvard sleep studies  
- Bedtime reminders and morning check-ins  
- Social features (anonymous sharing, monthly challenges, badges)  
- Home screen widgets  
- Multi-language support (English, Spanish, French)  
- Biometric app lock  

---

## Technologies Used

### Mobile Application
- Flutter  
- Dart  
- Provider  
- Hive  

### Backend
- Firebase  

### Libraries
- flutter_local_notifications  
- timezone  
- share_plus  
- pdf  
- home_widget  

---

## Installation and Access

### Requirements
- iOS 12.0+ or Android 5.0+  
- 100 MB free storage  
- Internet connection for AI features  

### Download Steps
1. Open the App Store (iOS) or Google Play Store (Android).  
2. Search **"Sleep Fixer App"**.  
3. Tap **Get/Install**.  
4. Grant notification and calendar permissions.  
5. Register or log in.  
6. Complete the initial sleep assessment.  
