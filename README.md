# StudentToolkit — Android Academic Productivity & GPA Forecasting Suite

<div align="center">

[![Daily Streak](https://img.shields.io/badge/Daily%20Streak-Active%20%F0%9F%94%A5-brightgreen?style=flat-square&logo=github)](https://github.com/abdussatarkhan)
[![Software Portfolio](https://img.shields.io/badge/Portfolio-Software%20Engineering%20%26%20Systems-0e75b6?style=flat-square&logo=github)](https://github.com/abdussatarkhan)
[![Author: Abdussatar](https://img.shields.io/badge/Author-Abdussatar-24292e?style=flat-square&logo=github)](https://github.com/abdussatarkhan)

</div>

[![CI](https://github.com/abdussatarkhan/student-toolkit/actions/workflows/ci.yml/badge.svg)](https://github.com/abdussatarkhan/student-toolkit/actions)
[![Kotlin](https://img.shields.io/badge/Kotlin-1.9+-7F52FF?style=for-the-badge&logo=kotlin&logoColor=white)](https://kotlinlang.org/)
[![Jetpack Compose](https://img.shields.io/badge/Jetpack_Compose-Material_3-4285F4?style=for-the-badge&logo=jetpackcompose&logoColor=white)](https://developer.android.com/jetpack/compose)
[![Android](https://img.shields.io/badge/Android-SDK_34-3DDC84?style=for-the-badge&logo=android&logoColor=white)](https://developer.android.com/)
[![Room Database](https://img.shields.io/badge/Storage-Room_SQLite-07405E?style=for-the-badge&logo=sqlite&logoColor=white)](https://developer.android.com/training/data-storage/room)

> **A native Android academic productivity application engineered in Kotlin and Jetpack Compose featuring Material 3 theming, an on-device AI academic assistant, Pomodoro focus timer, semester GPA/CGPA forecasting engine, and assignment deadline organizer backed by Room SQLite database.**

---

## 🏛️ System Architecture

```mermaid
graph TD
    ComposeUI[Jetpack Compose Material 3 UI Screens] --> ViewModel[Android ViewModels & StateFlow]
    ViewModel --> GPAService[GPA & CGPA Weighted Calculation Engine]
    ViewModel --> AIAssistant[On-Device AI Academic Advisor]
    ViewModel --> RoomRepo[Room Repository & Local DAOs]
    RoomRepo --> SQLiteDB[(On-Device SQLite Database)]
```

---

## 🌟 Key Features & Capabilities

- **📱 100% Native Jetpack Compose**: Modern declarative Android UI featuring dynamic Material Design 3 theming, fluid animations, and dark mode support.
- **🎓 Semester GPA / CGPA Forecasting**: Real-time grade point average computation supporting customizable university credit hour weighting systems and target grade simulations.
- **⏱️ Focus Pomodoro & Task Manager**: Integrated productivity timer with audible session alerts, priority assignment tracking, and exam countdowns.
- **🔒 Offline-First Room SQLite Persistence**: Robust local database architecture with Room DAOs and Kotlin Coroutines ensuring 100% offline availability with zero data leakage.

---

## 🚀 Quickstart & Setup

### Prerequisites
- [Android Studio Hedgehog (2023.1.1) or newer](https://developer.android.com/studio)
- Android SDK 34
- JDK 17+

### 1. Clone the Repository
```bash
git clone https://github.com/abdussatarkhan/student-toolkit.git
cd student-toolkit
```

### 2. Build the Project

**Option A: Using Android Studio**
1. Open Android Studio and select **Open**.
2. Select the cloned `student-toolkit` folder.
3. Allow Gradle to sync dependencies and click **Run (Shift+F10)** on an emulator or physical device.

**Option B: Using Gradle CLI**
```bash
# On Linux / macOS:
./gradlew assembleDebug

# On Windows:
.\gradlew.bat assembleDebug
```
The compiled APK will be located at `app/build/outputs/apk/debug/app-debug.apk`.

---

## 🖥️ Application & Operational Interface

<p align="center">
  <img src="screenshots/01_dashboard_preview.png" alt="StudentToolkit Academic Productivity Preview" width="95%" />
</p>

> [!TIP]
> You can also explore [`dashboard.html`](dashboard.html) directly in any modern browser for a standalone interface walkthrough.

---

## 🗺️ Roadmap & Upcoming Enhancements

- [x] Kotlin & Jetpack Compose modern Material 3 UI
- [x] Weighted GPA/CGPA computation engine
- [x] Local Room SQLite persistence for offline use
- [ ] Cloud backup and sync with Google Drive
- [ ] Class timetable schedule widget for Android Home Screen
- [ ] Push notification alerts for upcoming assignment deadlines

---

## 👨‍💻 Author & Contact

Built and maintained by **Abdussatar** ([@abdussatarkhan](https://github.com/abdussatarkhan)).  
For technical discussions, collaboration, or queries, feel free to reach out via [LinkedIn](https://www.linkedin.com/in/abdus-satar-5150813b5/) or [GitHub](https://github.com/abdussatarkhan).

---

## 📜 License

This project is licensed under the **MIT License** — see the LICENSE file for details.

---

<div align="center">

### 👨‍💻 Maintained by [Abdussatar (@abdussatarkhan)](https://github.com/abdussatarkhan)
Part of the **[Abdussatar Software Engineering & Systems Portfolio](https://github.com/abdussatarkhan)**.

⭐ If you find this project valuable, consider dropping a star! ⭐

</div>
