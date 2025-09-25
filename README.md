# Dice Roller App

A simple and elegant Flutter application that simulates rolling a dice with a beautiful gradient background. This project was created as part of a Flutter learning journey.

## 📚 About the Course

This project was developed while taking the Flutter & Dart course by Maximilian Schwarzmüller:

**[Flutter & Dart - The Complete Guide [2025 Edition]](https://www.udemy.com/course/learn-flutter-dart-to-build-ios-android-apps/?srsltid=AfmBOopSykzT5lpe_RCD---vIbasASrWQRTQms6bNvi6yCAJsPVqllYT&couponCode=MT250923G1)**

The course provides comprehensive training in Flutter and Dart for cross-platform mobile app development.

## Features

- 🎲 Realistic dice rolling animation
- 🌈 Beautiful gradient background
- 📱 Responsive design for all screen sizes
- ⚡ Smooth and fast performance
- 🎯 Simple and intuitive user interface

## Installation

### Prerequisites

- Flutter SDK (version 3.0 or higher)
- Dart SDK (version 2.17 or higher)
- An IDE (Android Studio, VS Code, or IntelliJ IDEA)
- An emulator or physical device for testing

### Steps

1. **Clone the repository**

   ```bash
   git clone https://github.com/arafatanam/Roll_Dice_App-Flutter.git
   cd dice-roller-app
   ```

2. **Get dependencies**

   ```bash
   flutter pub get
   ```

3. **Run the app**
   ```bash
   flutter run
   ```

## Project Structure

```
lib/
├── main.dart                 # Application entry point
├── gradient_container.dart   # Gradient background widget
├── dice_roller.dart         # Dice rolling functionality
└── styled_text.dart         # Custom text styling widget
```

## Key Files

### main.dart

- Application entry point
- Sets up MaterialApp with gradient background

### gradient_container.dart

- Creates customizable gradient backgrounds
- Includes a preset purple gradient option
- Centers the dice roller widget

### dice_roller.dart

- Handles dice rolling logic
- Manages state for dice images
- Provides roll button functionality

### styled_text.dart

- Custom text widget with predefined styling
- Ensures consistent text appearance throughout the app

## Usage

1. Launch the app
2. Tap the "Roll Dice" button to roll the dice
3. Watch as the dice image changes to a random number (1-6)
4. Continue rolling as many times as you like!

## Assets

Make sure you have dice images in your `assets/images/` directory named as:

- `dice-1.png`
- `dice-2.png`
- `dice-3.png`
- `dice-4.png`
- `dice-5.png`
- `dice-6.png`

## Dependencies

This project uses the following Flutter packages:

- `flutter/material.dart` - For Material Design components

## Development

### Building for production

```bash
flutter build apk --release
# or for iOS
flutter build ios --release
```

### Running tests

```bash
flutter test
```

## Course Learnings

This project demonstrates key Flutter concepts learned in the course:

- Widget-based architecture
- State management with StatefulWidget
- Custom widget creation
- Layout and styling
- Asset management
- Basic animations and interactions

---

**Enjoy rolling the dice!** 🎲

_Built with Flutter as part of an educational journey in mobile app development._
