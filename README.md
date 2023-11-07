# appointment_demo

* Project Structure

lib
├── main.dart
├── config
│   ├── app_config
│   │   ├── app_config.dart
│   │   ├── app_config_model.dart
│   │   ├── app_config_model_ext.dart
│   │   └── app_config_provider.dart
│   └── theme
│       ├── theme.dart
│       ├── dark_theme.dart
│       ├── light_theme.dart
│       ├── xxxxx_theme.dart
│       ├── custom_theme.dart
│       ├── theme_model.dart
│       ├── theme_model_ext.dart
│       └── theme_provider.dart
├── database
│   ├── database.dart
│   ├── database_service.dart
│   └── database_provider.dart
├── extensions
│   ├── date
│   │   └── date_ext.dart
│   ├── string
│   │   └── string_ext.dart
│   ├── ...
│   └── extensions.dart
├── modules
│   ├── module1
│   │   ├── view
│   │   │   └── module1_view.dart
│   │   ├── model
│   │   │   ├── module1_model.dart
│   │   │   └── module1_model_ext.dart
│   │   ├── provider
│   │   │   └── module1_provider.dart
│   │   └── components
│   │       ├── component1
│   │       │   ├── component1.dart
│   │       │   ├── component1_1.dart
│   │       │   └── ...
│   │       └── ...
│   └── ...
├── components
│   ├── component1
│   │   ├── component1.dart
│   │   ├── component1_1.dart
│   │   └── ...
│   └── ...
├── services
│   ├── service1.dart
│   └── ...
└── utils
    ├── constants.dart
    └── functions
        ├── shared_function1.dart
        └── ...
test
├── unit
│   ├── module1
│   │   └── module1_test.dart
│   └── ...
├── integration
│   ├── module1
│   │   └── module1_test.dart
│   └── ...
└── widget
    ├── module1
    │   └── module1_test.dart
    └── ...
