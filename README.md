# finance_tracker

A Finance Tracker App Project

## Getting Started

This project is a Flutter application for tracking finances.

## Project Structure

The project follows a standard Flutter project structure:

- **android:** Contains the Android-specific code and configurations.
- **ios:** Contains the iOS-specific code and configurations.
- **lib:** Contains the core Flutter application code, including UI and business logic.  The `lib` directory is further organized as follows:
    - **models:** Contains data models representing various entities like transactions, accounts, etc.
    - **providers:** Contains Riverpod providers for managing application state and logic.
    - **screens:** Contains the UI screens of the application, typically organized by feature or flow.
    - **services:** Contains services for interacting with external resources, such as databases or APIs.
    - **widgets:** Contains reusable UI components used throughout the app.
    - **main.dart:** The entry point of the Flutter application.


## Dependencies

This project uses the following key dependencies:

- **flutter:** The core Flutter framework.
- **path_provider:** For accessing and manipulating file paths on the device. This is likely used for storing data locally.
- **intl:** Provides internationalization and localization capabilities.
- **riverpod:** A state management solution.
- **hive:** A lightweight and fast NoSQL database for local data storage.
- **csv:** A library for parsing and generating CSV files.
- **fl_chart:** A charting library for visualizing financial data.


## Building and Running

To build and run the app, follow these steps:

1. **Install Flutter:**  Install the Flutter SDK ([https://docs.flutter.dev/get-started/install](https://docs.flutter.dev/get-started/install)).

2. **Clone the repository:**
```bash
git clone https://github.com/meirusfandi/finance_tracker.git
```

3. **Navigate to the project directory:**
```bash
cd finance_tracker
```

4. **Get dependencies:**
```bash
flutter pub get
```

5. **Run the app:**
```bash
flutter run
```


## Additional Resources

- [Lab: Write your first Flutter app](https://docs.flutter.dev/get-started/codelab)
- [Cookbook: Useful Flutter samples](https://docs.flutter.dev/cookbook)
- [Flutter documentation](https://docs.flutter.dev/)
