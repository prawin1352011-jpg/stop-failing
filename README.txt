STOP FAILING - Android project (Capacitor)

You need: Node.js 18+, Android Studio (includes the Android SDK and Java).

1. Open a terminal in this folder and run:  npm install
2. npx cap add android
3. npx @capacitor/assets generate --android      (turns assets/icon-only.png into your app icon)
4. npx cap sync
5. npx cap open android
6. In Android Studio: Build > Build Bundle(s) / APK(s) > Build APK(s).
   The file appears at android/app/build/outputs/apk/debug/app-debug.apk
7. Copy that APK to your phone and install it (allow "install unknown apps" if asked).

To change the app later, edit www/index.html, then run:  npx cap sync
