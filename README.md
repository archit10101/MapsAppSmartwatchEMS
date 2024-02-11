# Smartwatch EMS Maps App

This project is a smartwatch application designed for GPS navigation. It utilizes Mapbox services to provide accurate mapping and navigation functionalities. The app sends Bluetooth signals to low-energy Bluetooth devices whenever a turn is approaching and when the turn is completed. This app can be easily customized to adapt to various tasks using Arduino or similar microcontrollers.

## Features

- **GPS Navigation**: Provides accurate GPS navigation between specified locations.
- **Bluetooth Integration**: Sends Bluetooth signals to low-energy devices for turn alerts during navigation.
- **Mapbox Support**: Utilizes Mapbox services for accurate mapping and navigation functionalities.

## Installation

Follow these steps to install the application:

1. **Set Up Mapbox Access Token**:
   - Create a file named `mapbox_access_token.xml` in `res/values`.
   - Add your public Mapbox token as a string in `mapbox_access_token.xml`.
   - Replace `CHANGE THIS TO THE PUBLIC MAPBOX TOKEN` with your public Mapbox token.

2. **Update Gradle Properties**:
   - In `gradle.properties`, replace the Mapbox token with your secret access token.

3. **Run the Project**: 
   - Build and run the project to start using the app.

## Disclaimer

This application is provided as-is without any warranty. Use it responsibly and at your own risk.

## Author

Created by Archit Tamhane.

---

For any inquiries or contributions, please contact the repository owner. Enjoy navigating with the Smartwatch EMS Maps App!
