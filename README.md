# Audio Stream App

## Overview
The Audio Stream App is designed for real-time voice streaming, allowing users to amplify their voice through a connected speaker. This is particularly useful in scenarios where you need to address a large audience without the availability of a traditional microphone and speaker setup. By utilizing this app, you can connect your Android device to a speaker via Bluetooth (or any other audio output method) and broadcast your voice using the phone's microphone.

## Features
- Real-time audio streaming from the microphone to a connected speaker.
- Simple user interface with start and stop controls for streaming.

## Prerequisites
- Android Studio Arctic Fox | 2020.3.1 or newer.
- Android SDK with a compile SDK version of 34.
- A physical Android device or an emulator running at least Android 7.0 (API level 24).

## Setup
1. **Clone the repository:**
   ```bash
   git clone https://github.com/iman-zamani/Audio-Stream-App.git
   ```

2. **Open the project in Android Studio:**
   - Launch Android Studio.
   - Choose "Open an Existing Project".
   - Navigate to the directory where you cloned the project and select it.

3. **Connect your Android device via USB or set up an emulator:**
   - Ensure that USB debugging is enabled on your device.
   - Alternatively, set up an emulator through AVD Manager in Android Studio.

## Building the Project
1. **In Android Studio:**
   - Once the project is open, allow Android Studio to sync with Gradle files.
   - After synchronization, go to `Build > Make Project` to compile the project.

2. **Running the App:**
   - Select your connected device or emulator from the device dropdown menu in the toolbar.
   - Click on the run icon (a green triangle) or `Run > Run 'app'` to deploy the application on your device/emulator.

## Usage
1. **Grant Permissions:**
   - On the first launch, the app will request necessary permissions for recording audio. Please accept it to ensure the app functions properly.

2. **Start Streaming:**
   - Tap and hold the 'Record' button to start streaming your voice.
   - Your voice will be captured via the device's microphone and output through the connected speaker.

3. **Stop Streaming:**
   - Release the 'Record' button to stop streaming.

## Contributing
Contributions to the Audio Stream App are welcome! Please feel free to fork the repository, make your changes, and submit a pull request.

## License
This project is licensed under the MIT License - see the [LICENSE.md](LICENSE) file for details.
