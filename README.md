# Quiz App 🧠🎯

A feature-rich Flutter quiz application with Firebase integration, Riverpod state management, and GoRouter navigation.

## Features ✨

- **Authentication**: Firebase Auth for secure user login/signup
- **Quiz Categories**: Multiple categories with grid view selection
- **Random Quiz**: Start a random quiz from any category
- **Timed Questions**: Timer for quiz
- **Results Screen**: Detailed score breakdown
- **User Profile**: Personal stats 
- **State Management**: Riverpod for efficient state handling
- **Navigation**: GoRouter for smooth routing
- **Persistence**: SharedPreferences for session management

## Tech Stack 🛠️

- **Flutter**: 3.x
- **Firebase**: 
  - Authentication
  - Firestore (for questions and user data)
- **State Management**: Riverpod
- **Navigation**: GoRouter
- **Local Storage**: SharedPreferences
- **Dependency Injection**: Riverpod providers
- **UI**: Custom animations and responsive design

### Project Structure
```
lib/
  core/
    constants/
    utils/
    widgets/
  features/
    auth/              # auth data, providers, views, guards
    home/              # home screen providers & view
    profile/           # profile screen view
    quiz/              # quiz data/models/repos/providers/views
    splash/            # animated splash, widgets, providers
  firebase_options.dart
  main.dart            # app entry
  router.dart          # routes with go_router
```

### 🔧 Installation Steps

1. **Clone the repository**

```bash
git clone https://github.com/tej-2229/Quiz-App.git
```

2. **Install packages**

```bash
flutter pub get
```

3. **Run the app**
```bash
flutter run
```









