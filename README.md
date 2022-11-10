After cloning the repository, do these steps-

- Create a firebase project
- Enable Authentication
- Enable firestore and storage (with valid rules)
- Create Android and Web apps
- Inside the `main.dart` add your own firebase options (The existing ones won't work)
- Migrate to the folder and do-

```
flutter pub get
flutter run //To run the project default output settings
flutter run -d chrome --web-renderer html //To run the project on the web, and with html so that the images load
```
