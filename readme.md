# Home Helps - Doorstep Services Platform 🏠

Home Helps is a comprehensive platform that connects users with service providers for doorstep services. The project consists of two main components:

1. **Mobile Application (User & Service Provider)** 📱
   - Repository: [home_helps_submission](https://github.com/theexpensiveinformatics/home_helps_submission.git)
   - Features for both service users and providers
   - Built with Flutter using GetX and Feature-First Architecture

2. **Web Analytics & Admin Panel** 💻
   - Repository: [home_helps_admin_submission](https://github.com/theexpensiveinformatics/home_helps_admin_submission.git)
   - Super admin dashboard for platform management
   - Built with Flutter Web

## Team 👥

Meet the talented developers behind Home Helps:

### Core Development Team

- **Patel Krushang** - Project Lead & Full Stack Developer
  - GitHub: [theexpensiveinformatics](https://github.com/theexpensiveinformatics)
  - Role: Architecture Design, Mobile App Development, Admin Panel

- **Rohit** - Mearn Developer
  - GitHub: [RayqRohit](https://github.com/RayqRohit)
  - Role: Web Developer

## Technology Stack 🛠️

- **Flutter** - UI Framework
- **Firebase** - Backend & Database
- **Gemini Studio** - AI Integration
- **GetX** - State Management
- **Feature First Architecture (MVC)** - Project Structure
- **GitHub** - Version Control

## Features ✨

### User Features 👤
- Authentication with Email Verification 🔐
- Fetching Nearby Services 🚀
- Book Services by providing Latitude, Longitude & Address 📍
- Timeline of Booked Services 📃

### Service Provider Features 👨‍🔧
- Create Services 🚀
- Manage Services 📈
- Provider Dashboard 📊

### Super Admin Panel Features 👑
- Revenue Dashboard 🤑
- Booked Services Analytics 📈
- Heat Map Integration 🗺️
- Request Management System 📨
- AI Playground with Gemini Integration ✨
- Service Hosting Management 🌐

## Project Structure (Mobile App) 📁

```
lib/
├── bindings/          # GetX bindings
├── common/            # Common utilities and widgets
├── data/             # Data layer (repositories, models)
├── features/         # Feature modules
│   ├── authentication/
│   │   ├── controllers/
│   │   ├── models/
│   │   └── screens/
│   ├── dashboard/
│   ├── help/
│   └── personalization/
├── utils/            # Utility functions
├── app.dart          # App configuration
├── firebase_options.dart
├── home_screen.dart
├── main.dart
├── map_testing.dart
└── navigation_menu.dart
```

## Installation Steps 🚀

### Prerequisites
- Flutter SDK (latest stable version)
- Android Studio / VS Code
- Git
- Firebase CLI
- Gemini Studio API Key

### Mobile App Setup
1. Clone the repository:
   ```bash
   git clone https://github.com/theexpensiveinformatics/home_helps_submission.git
   ```

2. Install dependencies:
   ```bash
   cd home_helps_submission
   flutter pub get
   ```

3. Configure Firebase:
   - Create a new Firebase project
   - Download `google-services.json` for Android
   - Download `GoogleService-Info.plist` for iOS
   - Place them in respective platform folders

4. Configure Gemini:
   - Add your Gemini API key in the configuration file

5. Run the app:
   ```bash
   flutter run
   ```

### Admin Panel Setup
1. Clone the repository:
   ```bash
   git clone https://github.com/theexpensiveinformatics/home_helps_admin_submission.git
   ```

2. Install dependencies:
   ```bash
   cd home_helps_admin_submission
   flutter pub get
   ```

3. Configure Firebase Web:
   - Add Firebase configuration to `firebase_options.dart`

4. Run the admin panel:
   ```bash
   flutter run -d chrome
   ```

## Screenshots 📸
[Add your application screenshots here]

## System Requirements 💻

### Mobile App
- Android 5.0 (API level 21) or higher
- iOS 11.0 or higher
- Flutter 3.0 or higher

### Admin Panel
- Any modern web browser
- Minimum 4GB RAM recommended
- Stable internet connection

## Contributing 🤝

1. Fork the repositories
2. Create your feature branch 
3. Commit your changes 
4. Push to the branch 
5. Open a Pull Request



## Acknowledgments 🙏
- Flutter Team
- Firebase
- Gemini Studio
- GetX Team
