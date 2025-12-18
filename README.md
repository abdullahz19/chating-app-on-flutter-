# Com Tool

Com Tool - A cross platform chat-application programmed using Flutter.
This project was created by Abdullah Zahoor.

This is a mobile chat application designed based on being environmentally friendly, efficient, free to use, user friendly, reliable, simple, and safe to use. To fill the need of a new simple mobile chat application that anyone can use to send messages to friends or colleagues. The creators’ goal is to create a simple yet efficient way to receive and send messages with or without wireless access for both IOS and Android devices.
This application will be free and will be completed by volunteers for a school project.



### Team

- Abdullah Zahoor



### Dependencies

  cupertino_icons: https://pub.dev/packages/cupertino_icons
  firebase_auth: https://pub.dev/packages/firebase_auth
  cloud_firestore: https://pub.dev/packages/cloud_firestore
  firebase_core: https://pub.dev/packages/firebase_core
  page_transition: https://pub.dev/packages/page_transition
  flutter_verification_code: https://pub.dev/packages/flutter_verification_code
  intl_phone_field: https://pub.dev/packages/intl_phone_field
  animate_do: https://pub.dev/packages/animate_do
  get: https://pub.dev/packages/get
  flutter_nearby_connections: https://pub.dev/packages/flutter_nearby_connections
  device_info: https://pub.dev/packages/device_info
  flutter_styled_toast: https://pub.dev/packages/flutter_styled_toast
  image_cropper: https://pub.dev/packages/image_cropper
  image_picker: https://pub.dev/packages/image_picker
  flutter_image_compress: https://pub.dev/packages/flutter_image_compress
  path_provider: https://pub.dev/packages/path_provider
  firebase_storage: https://pub.dev/packages/firebase_storage
  chat_bubbles: https://pub.dev/packages/chat_bubbles
  flutter_email_sender: https://pub.dev/packages/flutter_email_sender
  stacked: https://pub.dev/packages/stacked
  flutter_settings_screens: https://pub.dev/packages/flutter_settings_screens
  flutter_rating_bar: https://pub.dev/packages/flutter_rating_bar
  google_fonts: https://pub.dev/packages/google_fonts
  salomon_bottom_bar: https://pub.dev/packages/salomon_bottom_bar

### Additional Files 

  Found in /extras folder 
  - Application Design
  - ENL Drafts 
  - Presentation Slides
  - ChatApp_Demo.

### Configuration (Firebase / Google APIs)

- **What I changed:** I removed hard-coded API keys from the repository and replaced them with placeholders. The real config files are now ignored by `.gitignore`.
- **Why:** Storing API keys in a public repo is a security risk. You should keep credentials local or in a secure secret store and rotate any exposed keys immediately.

Follow these steps to configure the app locally:

1. In the Firebase Console (https://console.firebase.google.com/) create or open your project.
2. For Android: download `google-services.json`. Place the file at `android\\app\\google-services.json` (this file is ignored by git).
3. For iOS: download `GoogleService-Info.plist`. Place the file at `ios\\Runner\\GoogleService-Info.plist` (this file is ignored by git).
4. If you prefer to use placeholders, copy `android/app/google-services.json.template` -> `android/app/google-services.json` and fill in the values locally.
5. Do not commit your `google-services.json` or `GoogleService-Info.plist` to the repository.

If your previous keys were exposed publicly, revoke them in the Google Cloud Console and create new, restricted API keys. See the repository security notes for more details.