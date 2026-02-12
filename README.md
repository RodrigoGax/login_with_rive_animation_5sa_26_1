# 🐻 Interactive Rive Login - Flutter

A modern, interactive login screen built with **Flutter** that leverages the power of **Rive** to create a dynamic user experience. The animation reacts to user input in real-time, making the authentication process engaging and fun.

---

## 🚀 Features

- **Interactive Character:** A functional Rive animation (The Bear) that tracks the user's input focus.
- **Gaze Tracking:** The character's eyes follow the cursor as you type your email.
- **Privacy Reaction:** The character covers its eyes ("Hands Up") when the user interacts with the password field.
- **State Feedback:** Visual cues for success or failure upon login attempts.
- **Responsive UI:** Clean design adapted to different screen sizes using `MediaQuery`.

---

## 🧠 Core Concepts

### What is Rive?

**Rive** is a real-time interactive design and animation tool that allows developers to create high-quality vector animations that run on any platform. Unlike static GIFs or videos, Rive animations are lightweight and can be manipulated via code at runtime.

### What is a State Machine?

A **State Machine** in Rive is a visual logic builder used to define the animation's behavior. It allows the character to transition between different states (e.g., _Idle_, _Checking_, _HandsUp_, _Success_, _Fail_) based on specific **inputs** (Booleans or Numbers) triggered by the Flutter code.

---

## 🛠 Technologies Used

- **Framework:** Flutter 3.x 💙
- **Language:** Dart 🎯
- **Animation Engine:** Rive Package (`rive`) 🎭
- **IDE:** Visual Studio Code / Android Studio

---

## 📂 Project Structure

The core logic of the application is organized as follows:

```text
lib/
├── main.dart             # Application entry point.
└── login_screen.dart     # Main UI containing the TextFields and RiveController logic.
assets/
└── animated_login_bear.riv # The Rive binary file containing the animation and State Machine.
```
