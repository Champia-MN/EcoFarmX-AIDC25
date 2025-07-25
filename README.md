#  EcoFarmX – Smart Automated Farming System

EcoFarmX is an IoT-enabled smart farming system built with Flutter and Firebase. It helps monitor and control agricultural environments in real-time, powered by a solar backup.

##  Features

-  Real-time Monitoring (Temp, Moisture, Humidity, Light, Fire)
-  Device Control (Pump, Lights, Sprinklers)
-  Solar Backup Monitoring
-  Firebase Authentication
-  Mobile App UI in Flutter

##  Project Structure

- `lib/screens` – UI pages like Dashboard, Control, Login
- `lib/widgets` – Custom buttons, cards, and indicators
- `lib/services` – Firebase and control service logic
- `lib/models` – Sensor and user data models
- `lib/utils` – Constants, themes

##  Setup Instructions

### Prerequisites:
- Flutter SDK
- Firebase Project
- Android Studio / VS Code

### Steps:

```bash
git clone https://github.com/yourusername/EcoFarmX.git
cd EcoFarmX
flutter pub get
flutter run

