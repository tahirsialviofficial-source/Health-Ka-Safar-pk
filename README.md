# Health ka Safar – Android App

Aap ki site (https://healthkasafar.blogspot.com/) ka professional Android app, naye logo ke saath.

## APK kaise banayen

### Tareeqa 1 – Android Studio (PC par)
1. Android Studio install karein (Koala ya naya).
2. `File > Open` se is poore folder ko kholein aur Gradle sync hone dein.
3. `Build > Build Bundle(s) / APK(s) > Build APK(s)`.
4. APK yahan milega: `app/build/outputs/apk/debug/app-debug.apk`

### Tareeqa 2 – Bina Android Studio ke (GitHub se)
1. github.com par free account banayen, naya repository banayen.
2. Is folder ki saari files (`.github` folder samet) upload karein.
3. `Actions` tab > `Build APK` > `Run workflow`.
4. 3-5 minute baad us run ke andar `HealthKaSafar-debug-apk` download karein (zip ke andar APK hai).

Note: Pehle se install purana app pehle uninstall kar dein (signing key alag hoti hai).

## Is mein kya naya hai
- Naya logo: app icon (adaptive + round), Android 12 splash, aur loading screen
- Dark + green theme jo logo se match karti hai
- Upar patli green progress bar, neeche kheench kar refresh
- Internet na ho to branded "Internet nahi hai" screen aur Retry button
- Back button se pichle page par jana, home par double-back se exit
- Phone, email, WhatsApp aur dusri sites ke links bahar khulte hain
- Files download support, YouTube fullscreen video support
- Invalid SSL certificate par page load nahi hota (security)

## Customize
- Site ka link: `MainActivity.java` mein `HOME_URL`
- Rang: `app/src/main/res/values/colors.xml`
- Text (Roman Urdu): `app/src/main/res/values/strings.xml`
