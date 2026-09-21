# Battle Royale — Dingana 27

## Tanjona
Build APK Android sy test amin'ny appareil Android.

## Zava-dehibe
Ity archive ity dia **projet source + workflow de build**, fa tsy APK efa compilé. Ny compilation dia atao amin'ny Android/CI environment.

## Build automatique
Ny `.github/workflows/android-build.yml` dia afaka manao build `debug APK` rehefa ampiasaina amin'ny GitHub Actions.

## Test tokony hatao
- installation APK
- lancement de l'application
- tactile/menu
- sauvegarde locale
- connexion réseau rehefa server online no ampiasaina

## Production
Alohan'ny publication Play Store dia mbola mila signing/release AAB, package name final, privacy policy ary configuration serveur.
