# 100cims de Catalunya

- `www/`: l'app (PWA: instal·lable i funciona sense connexió).
- Vercel publica `www/` com a web.
- GitHub Actions (`.github/workflows/android.yml`) compila l'APK d'Android.

## Pujar a GitHub
1. Crea un repositori nou a github.com (p. ex. `100cims`).
2. «Add file > Upload files», arrossega tot el contingut d'aquesta carpeta (inclosa `.github`) i fes Commit.

## Vercel (web instal·lable)
1. vercel.com > Add New > Project > importa el repositori.
2. Framework Preset: Other. Output Directory: `www`. Build Command: buida. Deploy.
3. Obre la URL al mòbil i afegeix-la a la pantalla d'inici (iPhone: Safari > Compartir; Android: Instal·la l'app).

## APK d'Android (GitHub)
1. Al repositori: pestanya Actions > «Build Android APK» > Run workflow.
2. Quan acabi, baixa `100cims-apk` de l'apartat Artifacts, descomprimeix i instal·la `app-debug.apk` al mòbil (cal permetre fonts desconegudes).
