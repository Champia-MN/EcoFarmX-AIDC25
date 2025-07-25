EcoFarmX/
│
├── android/                          # Native Android platform files
├── ios/                              # Native iOS platform files
├── lib/                              # Flutter source code
│   ├── main.dart                     # App entry point
│   ├── screens/                      # UI screens
│   │   ├── dashboard_screen.dart     # Realtime data dashboard
│   │   ├── device_control.dart       # Control irrigation/lights
│   │   ├── solar_monitor_screen.dart # Solar backup status
│   │   ├── login_screen.dart         # Login/Authentication
│   │   └── settings_screen.dart      # App settings
│   ├── widgets/                      # Reusable components
│   │   ├── sensor_card.dart
│   │   ├── control_button.dart
│   │   └── status_indicator.dart
│   ├── models/                       # Data models
│   │   ├── sensor_data.dart
│   │   └── user_model.dart
│   ├── services/                     # Firebase + Device services
│   │   ├── firebase_auth_service.dart
│   │   ├── sensor_data_service.dart
│   │   └── device_control_service.dart
│   └── utils/                        # Constants and helper functions
│       ├── app_constants.dart
│       └── theme_config.dart
│
├── assets/                           # Static assets
│   ├── images/
│   │   ├── logo.png
│   │   └── dashboard_bg.jpg
│   └── icons/
│       └── solar_panel.png
│
├── test/                             # Unit/widget tests
│   └── sensor_data_test.dart
│
├── firebase/                         # Firebase setup files
│   ├── google-services.json          # Android config
│   └── GoogleService-Info.plist      # iOS config
│
├── .gitignore                        # Git ignored files
├── pubspec.yaml                      # Flutter dependencies and assets
├── pubspec.lock                      # Locked versions
├── README.md                         # Project overview and setup
└── LICENSE                           # License (e.g., MIT)
