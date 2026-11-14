# A320 EFB – Android-App für Samsung Galaxy Tab S8+

Die App öffnet `http://192.168.178.41:8083/#/efb` in einer Android-WebView.

- Fester Querformatmodus
- Vollbild (Immersive Sticky; Android-Systemleisten lassen sich durch Wischen vorübergehend einblenden)
- JavaScript und DOM-Speicher aktiviert
- Bildschirm bleibt an
- Schaltfläche zum erneuten Verbinden bei Ladefehlern

## APK bauen

1. Android Studio installieren und den Ordner `A320_EFB` als Projekt öffnen.
2. Gradle-Synchronisierung abwarten (Internetverbindung erforderlich).
3. Menü **Build > Build Bundle(s) / APK(s) > Build APK(s)**.
4. Die APK liegt unter `app/build/outputs/apk/debug/app-debug.apk`.
5. APK auf das Tablet übertragen und installieren (Installation aus dieser Quelle ggf. erlauben).

**Hinweise:** PC und Tablet müssen sich im selben Netzwerk befinden, und der Fenix-EFB-Webserver muss auf Port 8083 erreichbar sein. Das Projekt ist Quellcode, keine bereits kompilierte APK. Android kann Systemleisten durch Gesten kurzzeitig einblenden. Nicht auf einem echten Flugzeug für die Flugführung verwenden.
