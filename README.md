# flutternew

A new Flutter project.

## Getting Started

firebase init Firebase db connect use
This project is a starting point for a Flutter application.

A few resources to get you started if this is your first Flutter project:

- [Lab: Write your first Flutter app](https://docs.flutter.dev/get-started/codelab)
- [Cookbook: Useful Flutter samples](https://docs.flutter.dev/cookbook)

For help getting started with Flutter development, view the
[online documentation](https://docs.flutter.dev/), which offers tutorials,
samples, guidance on mobile development, and a full API reference.

sudo apt-get install clang cmake ninja-build pkg-config libgtk-3-dev liblzma-dev

#Enable API and services find "Android device location" and this is enable access for google console
#Phone OTP Verify In Flutter : Follow Link https://github.com/proglabs/flutter_firebase_auth
flutter pub add firebase_auth
flutter pub add fluttertoast
flutter pub add firebase_core
curl -sL https://firebase.tools | bash
dart pub global activate flutterfire_cli
export PATH="$PATH":"$HOME/.pub-cache/bin"
dart pub global activate flutterfire_cli
firebase login
firebase projects:list
flutterfire configure --project=beauty-28838
#Firebase configuration file lib/firebase_options.dart generated successfully with the following Firebase apps: 
flutterfire --version
keytool -list -v -alias androiddebugkey -keystore ~/.android/debug.keystore
#keystore Password:android  && https://developers.google.com/android/guides/client-auth?authuser=0&hl=en
#Key generate sha256 sha1 add in fireace project fingerprint

Issuer: C=US, O=Android, CN=Android Debug
Serial number: 1
Valid from: Tue Jul 05 15:19:56 IST 2022 until: Thu Jun 27 15:19:56 IST 2052
Certificate fingerprints:
         SHA1: F3:9E:4F:76:E7:F9:61:63:B5:4A:88:6B:92:2A:FE:6A:F3:98:A4:BD
         SHA256: 6A:2D:DE:13:2C:83:7E:B0:F5:06:6E:01:88:32:7C:B1:50:27:5F:26:53:58:C6:05:5E:21:DB:F8:52:DB:01:FD
Signature algorithm name: SHA1withRSA (weak)
Subject Public Key Algorithm: 2048-bit RSA key
Version: 1



Visit this URL on this device to log in:
https://accounts.google.com/o/oauth2/auth?client_id=563584335869-fgrhgmd47bqnekij5i8b5pr03ho849e6.apps.googleusercontent.com&scope=email%20openid%20https%3A%2F%2Fwww.googleapis.com%2Fauth%2Fcloudplatformprojects.readonly%20https%3A%2F%2Fwww.googleapis.com%2Fauth%2Ffirebase%20https%3A%2F%2Fwww.googleapis.com%2Fauth%2Fcloud-platform&response_type=code&state=476731879&redirect_uri=http%3A%2F%2Flocalhost%3A9005



