# Reflexa - AI-Powered Journal App

<div align="center">
  <img src="./assets/images/adaptive-icon.png" alt="Reflexa Logo" width="120" height="120" style="border-radius: 20px"/>
</div>

## Overview

Reflexa is an AI-powered journaling app that helps users track their emotions and mental well-being. The app uses advanced emotion analysis to understand the user's emotional state from their journal entries, providing insights and patterns over time.

## Features

### 📝 Smart Journaling
- **AI Emotion Analysis**: Automatically detects emotions from your journal entries
- **Image Support**: Attach images to your entries
- **Rich Text Formatting**: Express yourself with formatted text
- **Voice-to-Text**: Dictate your thoughts (coming soon)

### 🔒 Privacy & Security
- **Private Entries**: Secure entries with biometric authentication or PIN
- **Encrypted Storage**: Your data stays private and secure
- **Selective Sharing**: Choose what to share and keep private

### 📊 Emotional Insights
- **Emotion Tracking**: Visual representation of your emotional journey
- **Multiple Chart Types**: View your data through:
  - Line charts
  - Bar charts
  - Pie charts
  - Progress bars
- **Time-based Analysis**: Track patterns daily, weekly, monthly, or yearly

### 🔍 Smart Search
- **Advanced Filters**: Search by:
  - Emotions
  - Date ranges
  - Bookmarks
- **Full-text Search**: Find specific entries easily

### 📱 User Experience
- **Dark/Light Mode**: Comfortable viewing in any lighting
- **Haptic Feedback**: Enhanced interaction experience
- **Customizable Settings**: Personalize your experience
- **Streak Tracking**: Stay motivated with daily journaling streaks

## Installation

### Prerequisites
- Node.js (v16 or higher)
- npm or yarn
- Expo CLI
- Android Studio (for Android development)
- Xcode (for iOS development, macOS only)

### Setup
1. Clone the repository:
   ```bash
   git clone https://github.com/Aditya-Nagurkar/reflexa.git
   cd reflexa
   ```

2. Install dependencies:
   ```bash
   npm install
   # or
   yarn install
   ```

3. Start the development server:
   ```bash
   npm start
   # or
   yarn start
   ```

### Building for Production

#### Android
```bash
eas build --profile preview --platform android
```

#### iOS
```bash
eas build --profile production --platform ios
```

## Tech Stack

- **Framework**: React Native with Expo
- **State Management**: Zustand
- **Navigation**: Expo Router
- **UI Components**: Custom components with native styling
- **Storage**: AsyncStorage with Zustand persist
- **Charts**: React Native Chart Kit
- **Icons**: Lucide React Native
- **Authentication**: Expo Local Authentication

## Project Structure

```
reflexa/
├── app/                   # Main application screens
│   ├── (tabs)/           # Tab-based navigation screens
│   ├── entry/            # Journal entry related screens
│   └── settings/         # Settings screens
├── assets/               # Static assets (images, fonts)
├── components/           # Reusable React components
├── constants/            # App-wide constants
├── services/            # External services and APIs
├── store/               # State management
├── types/               # TypeScript type definitions
└── utils/               # Utility functions
```

## Contributing

We welcome contributions! Please feel free to submit a Pull Request.

## Developers

- [Aditya Joshi](https://github.com/Adityaj08)
- [Aditya Nagurkar](https://github.com/Aditya-Nagurkar)
- [Ashutosh Mathapati](https://github.com/Ashutosh-Mathapati)
- [H M Dhanush](https://github.com/Dhanushiremath)
- [Snehalkumar](https://github.com/snehal1616)


## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

Special thanks to all contributors and the open-source community for making this project possible. 