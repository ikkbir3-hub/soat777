# Neon Digital Clock — Android

Bu loyiha neon effektli elektron soatni Android ilovasi (APK) sifatida yig'ish uchun tayyorlangan.

## GitHub orqali APK olish

1. ZIP faylni oching.
2. Ichidagi `neon-digital-clock-android` papkasini GitHub'da yangi repository'ga yuklang.
3. Repository ichida **Actions** bo'limiga kiring.
4. **Build Android APK** workflow'ini tanlang va **Run workflow** tugmasini bosing (yoki `main`/`master` branch'ga push qiling).
5. Jarayon tugagach, workflow natijasidagi **Artifacts** bo'limidan `neon-digital-clock-apk` faylini yuklab oling.
6. Yuklangan artifact ZIP ichidan `app-debug.apk` faylini topasiz.

## Muhim

- Bu ZIP — Android ilovasini yig'ish uchun manba loyiha; ZIPning o'zi APK emas.
- GitHub Actions internet orqali Android loyihasini yaratadi va APK yig'adi.
- Olingan debug APK sinov uchun. Play Store'ga chiqarish uchun release build va imzolash kaliti kerak.
- Ilova hozircha internet talab qilmaydi; soat telefonning mahalliy vaqtini ko'rsatadi.
