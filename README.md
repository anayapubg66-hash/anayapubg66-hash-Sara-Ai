# SARA AI — Android starter project

This is a starter Android Studio project for an Urdu voice assistant.

## Included in this first starter
- Urdu speech input through Android's speech-recognition activity (internet/service availability may be required).
- Urdu text-to-speech using the Urdu voice installed on the phone.
- A manual **Baat suno** button to start listening.
- A basic example command to open YouTube.
- A spoken response when a command is not yet supported.

## Important limitations
- This starter does **not** implement an always-listening background wake word. The phrase “Sara, baat suno” is recognized only after the user taps the button and starts speech recognition.
- Reliable always-on wake-word detection needs a dedicated on-device keyword engine and a foreground microphone service. Android and Infinix battery/privacy controls can stop background listening; a normal app cannot secretly or continuously use the microphone.
- Sending messages and placing calls are not implemented yet. Those features should show the selected contact and message and ask for confirmation before sending or calling.
- Urdu voice quality depends on the Urdu voice installed in Android's Text-to-Speech settings. If no Urdu voice is installed, install one from the phone's speech/voice settings.

## Build an APK
1. Install Android Studio on a computer.
2. Open this folder in Android Studio.
3. Let Gradle sync. The project uses Android Gradle Plugin 8.9.2 and compile SDK 36.
4. Build > Build Bundle(s) / APK(s) > Build APK(s).
5. Android Studio will show the generated APK location.

This source project is not itself an APK. It must be built in Android Studio.
