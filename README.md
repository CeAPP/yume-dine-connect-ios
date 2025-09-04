# Yume Dine Connect (Flutter WebView)

A minimal Flutter app that opens https://yume-dine-connect.lovable.app/ inside a WebView.

## Local dev (optional)
- Install Flutter
- `flutter pub get`
- `flutter run`

## CI (Codemagic)
This repo is set up so Codemagic will:
1) Generate iOS platform (`flutter create --platforms=ios .` if missing)
2) Patch the bundle identifier to `com.yumedine.connect`
3) Build an IPA and publish to TestFlight using your App Store Connect API key.