# CropSense AI

AI-Driven Decision Support for Climate-Resilient Smallholder Farming in Rwanda

link to video: https://drive.google.com/drive/u/0/folders/1ZB9uQpjgYYb1mhTxjDIFI-xhPSRw0smi
## Overview

CropSense AI is a mobile application designed to help smallholder farmers in Rwanda make informed decisions about crop selection, planting times, and farm management. The app provides AI-powered recommendations based on climate data, soil conditions, and historical farming data.

## Features

### Current Implementation

1. **Home Dashboard**
   - Real-time weather information
   - Quick action buttons for common tasks
   - Alerts and recommendations
   - Personalized crop suggestions

2. **Process Management**
   - Track cultivation stages
   - View detailed process information
   - Stage-by-stage guidance
   - Progress tracking

3. **Season Tracking**
   - Current season overview
   - Performance statistics
   - Historical data
   - Farmer achievements

4. **User Profile**
   - Farmer information management
   - Settings and preferences
   - Contact information

5. **AI Crop Advisor**
   - Personalized crop recommendations
   - Location-based suggestions
   - Soil type consideration
   - Season-specific advice

6. **Crop Health Scanner**
   - Disease detection guidance
   - Photo upload functionality
   - Common disease information
   - Treatment recommendations
  
  ## Tech Stack

- **Framework**: Flutter
- **Language**: Dart
- **UI**: Material Design 3
- **Fonts**: Google Fonts (Inter)
- **State Management**: StatefulWidget (can be upgraded to Provider/Riverpod later)

## Project Structure

```
lib/
├── main.dart                 # App entry point and navigation
├── screens/                  # All screen widgets
│   ├── home_screen.dart
│   ├── process_screen.dart
│   ├── season_screen.dart
│   ├── profile_screen.dart
│   ├── ai_advisor_screen.dart
│   └── crop_health_scanner_screen.dart
├── widgets/                  # Reusable widget components
│   ├── weather_card.dart
│   ├── quick_action_button.dart
│   ├── alert_card.dart
│   └── recommendation_card.dart
└── utils/                    # Utilities and constants
    └── colors.dart
```

## Getting Started

### Prerequisites

- Flutter SDK (3.0.0 or higher)
- Dart SDK (3.0.0 or higher)
- Android Studio / VS Code with Flutter extensions
- Android SDK / iOS SDK (depending on target platform)

### Installation

1. Clone the repository
2. Navigate to the project directory
3. Install dependencies:
   ```bash
   flutter pub get
   ```

4. Run the app:
   ```bash
   flutter run
   ```

### Running on Different Platforms

**Android:**
```bash
flutter run -d android
```

**iOS:**
```bash
flutter run -d ios
```

**Web:**
```bash
flutter run -d chrome
```
 # Images from the app
 <img width="296" height="456" alt="image" src="https://github.com/user-attachments/assets/8c0dbddc-6f8d-4212-bf18-a7fbe2c61736" />
 <img width="296" height="456" alt="image" src="https://github.com/user-attachments/assets/aa18c0c6-0365-4bf9-89be-bc0e68052657" />
 <img width="296" height="456" alt="image" src="https://github.com/user-attachments/assets/b703331e-f9cd-4dc4-beb0-4f3dccc97b7e" />
 <img width="310" height="553" alt="image" src="https://github.com/user-attachments/assets/0d039195-d74c-4337-b5af-428e5b030fc5" />
 <img width="310" height="553" alt="image" src="https://github.com/user-attachments/assets/0bd054b5-3794-4d14-a312-2a7a89e9e220" />
 <img width="310" height="553" alt="image" src="https://github.com/user-attachments/assets/21bd1b31-136e-43ce-a911-62e9ae4ccb54" />
 <img width="418" height="555" alt="image" src="https://github.com/user-attachments/assets/fc9151bf-66ba-446a-8fcd-17436cecc4f6" />
 <img width="309" height="544" alt="image" src="https://github.com/user-attachments/assets/7af1af68-f8bc-4fdb-a4ee-5f893ba60aca" />






 
