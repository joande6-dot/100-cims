# 100cims de Catalunya, app nativa (Capacitor 8)

Aquest projecte empaqueta la web de www/index.html dins d'una app nativa.
Les dades es desen al mateix mòbil i funciona sense connexió.

## Android (APK)
1. Instal·la Node.js 22 o superior i Android Studio.
2. En aquesta carpeta: npm install
3. npx cap add android
4. npm run android   (sincronitza i obre Android Studio)
5. Connecta el mòbil amb «Depuració USB» activada i prem Run.
   Per generar un APK: Build > Build Bundle(s) / APK(s) > Build APK(s).

## iPhone (iOS)
Cal un Mac amb Xcode.
1. npm install
2. npx cap add ios
3. npm run ios   i a Xcode tria el teu iPhone i prem Run.
   Amb un compte gratuït d'Apple l'app caduca als 7 dies. Per tenir-la fixa o publicar-la cal el Programa de Desenvolupadors d'Apple (99 $/any).

## Canviar l'app
Edita www/index.html i torna a executar npm run android o npm run ios.
Nom i identificador: capacitor.config.json (canvia'ls abans de fer cap add).
