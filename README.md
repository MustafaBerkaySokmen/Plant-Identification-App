# Plant Identification App

## Overview
The **Plant Identification App** is a Flutter-based mobile application that uses the device camera and an API to identify plants from images. The app captures an image of a plant's organ (e.g., leaf) and sends it to the PlantNet API for identification, returning the scientific name of the plant.
![Description of the image](plantn.png)

## Features
- Captures images using the device camera.
- Sends images to the PlantNet API for plant identification.
- Displays the scientific name of the identified plant.
- Handles errors and provides feedback if identification fails.

## Installation
To run this project, ensure you have the following installed:
- **Flutter SDK**
- **Dart SDK**
- A device or emulator for testing

### Steps:
1. **Clone the repository:**
   ```bash
   git clone https://github.com/yourusername/plant-identification-app.git
   ```
2. **Navigate to the project directory:**
   ```bash
   cd plant-identification-app
   ```
3. **Get Flutter dependencies:**
   ```bash
   flutter pub get
   ```
4. **Connect a device or emulator** and ensure it is running.
5. **Run the app:**
   ```bash
   flutter run
   ```

## Usage
1. **Open the app** on your device or emulator.
2. **Point the camera** at a plant leaf or organ you wish to identify.
3. **Capture the image** using the floating action button.
4. The app sends the image to the PlantNet API and returns the scientific name of the identified plant.
5. If identification fails, an appropriate error message is displayed.

## Example Output
```
Identification success: Quercus robur (English Oak)
```
Or:
```
No results found.
```

## API Usage
The app uses the **PlantNet API** for plant identification. Ensure you have a valid API key and update the `api-key` parameter in the code:
```dart
https://my-api.plantnet.org/v2/identify/all?api-key=YOUR_API_KEY
```

## License
This project is licensed under the **MIT License**.

## Contributions
Contributions are welcome! To contribute:
1. Fork the repository.
2. Create a new branch (`feature-new-feature`).
3. Commit and push your changes.
4. Open a pull request.

## Contact
For any questions or support, please open an issue on GitHub.

