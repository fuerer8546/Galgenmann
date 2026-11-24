# Galgenmännchen für Android

Das Spiel (`www/index.html`) verpackt als Android-App mit [Capacitor](https://capacitorjs.com).
Die APK wird automatisch von GitHub gebaut, es ist keine Android-Entwicklungsumgebung nötig.

## APK herunterladen und installieren

1. Im Repository auf **Releases** gehen und die neueste Version öffnen.
2. `Galgenmaennchen.apk` auf das Handy laden.
3. Datei öffnen und die Installation bestätigen. Beim ersten Mal muss Android die
   Installation aus dieser Quelle (Browser oder Dateien-App) erlauben.

Die APK ist mit dem Debug-Schlüssel signiert. Sie läuft problemlos auf dem Handy,
ist aber nicht für den Play Store gedacht.

## Spiel ändern

1. `www/index.html` ändern (oder ersetzen) und auf `main` pushen.
2. Unter **Actions** läuft der Build (ca. 3 bis 6 Minuten).
3. Danach liegt unter **Releases** eine neue APK.

Ein Build lässt sich auch von Hand starten: **Actions**, **Android-APK bauen**, **Run workflow**.

## Hinweise

- Der Highscore wird auf dem Handy gespeichert. Die Google-Drive-Synchronisierung
  gibt es nur in der Claude-Version der Seite.
- App-Name und Paketname stehen in `capacitor.config.json`.
