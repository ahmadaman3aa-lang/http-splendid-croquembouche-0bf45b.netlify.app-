# GadaaICT Mobile App (Flutter)

Cross-platform app for students: Android & iOS, trilingual.

## Setup
```bash
cd mobile
flutter pub get
# set your API URL in lib/main.dart:
#   ApiService('https://yourdomain.com/api')
flutter run
```

## Features implemented
- Login (JWT) with auto-persisted session
- 3-step student registration incl. Telebirr payment step
- Materials browser with type filter (video/pdf/audio/ppt/link) - opens YouTube/Drive/PDF
- Live classes with JOIN button (Jitsi/Zoom/Meet)
- My Subjects with progress bars
- Language switcher OM / አማ / EN
- Logout

## To add later
- Video playback inside app (video_player already in deps)
- Quiz taking UI (API endpoints already exist: POST /assessment/quizzes/<id>/take/)
- Certificate download (GET /comms/certificates/<id>/pdf/)
- Parent view
- Offline PDF caching
