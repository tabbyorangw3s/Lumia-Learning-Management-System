# Lumia by Sophia 🌸

**Lumia by Sophia** is a modern, aesthetic, and feature-rich Android Learning Management System and Smart Study/Flashcard application built with **Jetpack Compose** and **Material 3**.

---

## ✨ Key Features

1. **Custom Authentication & Onboarding (`AuthScreen.kt`)**
   - Seamless tab-switching between **Log In** and **Create Account**.
   - Input validation, password masking with show/hide toggle, and a **"Continue as Guest"** quick entry mode.
   - Convenient **"Autofill Credentials"** chip for quick testing.

2. **Dashboard & Deck Management (`HomeScreen.kt`)**
   - Personalized greeting banner: *"✨ Welcome back, [User Name] — Ready to master your decks?"*
   - Real-time **Study Streak Tracker** (`🔥`) and **XP Gamification Counter** (`⭐`).
   - Search bar to filter decks instantly by title or description.
   - Floating Action Button to create custom study decks or use quick templates.

3. **Smart Deck Details & Quick Import (`DeckDetailScreen.kt`)**
   - View all flashcards in a selected deck with status chips (`New`, `Reviewing`, `Mastered`).
   - **Quick Import Parser**: Instantly paste multiline notes formatted as `Question - Answer` or `Question: Answer` to bulk-import flashcards.
   - Manual card creation with question, answer, and optional hints.

4. **Active Recall Study Mode (`StudyScreen.kt`)**
   - Smooth 3D card-flip animation (`Question` ↔ `Answer` with hint support).
   - Active recall text input field with smart instant match feedback (`"✨ Spot on! Your answer matches!"`).
   - Leitner-style rating buttons (`Forgot`, `Hard`, `Good`, `Easy`) that update card mastery scores in real-time.
   - Celebratory completion summary screen.

---

## 🛠️ Tech Stack & Architecture

- **UI Toolkit:** Jetpack Compose & Material 3 (Aesthetic Pink Theme with custom Vibrant Rose `#E91E63`, Soft Blush `#FCE4EC`, and Dusty Mauve `#AD1457` palette).
- **Architecture:** MVVM (Model-View-ViewModel) with unidirectional data flow using Kotlin `StateFlow`.
- **Local Persistence:** Room Database with Kotlin Coroutines (`Dispatchers.IO`) and Flow reactive queries.
- **Navigation:** Jetpack Compose Navigation with safe arguments and backstack clearing for secure auth flows.

---

## 🚀 Getting Started

1. Open the project in **Android Studio**.
2. Sync project with Gradle files.
3. Run the app on an Android Emulator or physical device (Min SDK 26, Target SDK 35).
