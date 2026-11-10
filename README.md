# Mein Tram – Abfahrtstafel (ZVV / SBB)

App starten → sofort sehen, wann das nächste Tram zur Arbeit bzw. nach Hause fährt.
Daten: transport.opendata.ch (offizielle CH-Fahrplandaten inkl. Echtzeit-Verspätungen).

## APK bekommen – Variante A: GitHub (ohne Installation am PC)
1. Auf github.com ein neues (privates) Repository anlegen.
2. Inhalt dieses Ordners hochladen ("Add file → Upload files", inkl. Ordner `.github`).
3. Reiter **Actions** → Workflow "APK bauen" läuft automatisch (ca. 3–5 Min.).
4. Beim fertigen Lauf unten unter **Artifacts** `MeinTram-apk` herunterladen → ZIP enthält `app-debug.apk`.

## Variante B: Android Studio
Ordner öffnen → *Build → Build App Bundle(s)/APK(s) → Build APK(s)*.
Ergebnis: `app/build/outputs/apk/debug/app-debug.apk`.

## Installieren
APK aufs Handy kopieren, antippen, "Installation aus unbekannten Quellen" einmalig erlauben.

## Bedienung
- Beim ersten Start Haltestelle Zuhause + Arbeit wählen (Vorschläge erscheinen beim Tippen).
- Vor der Umschaltzeit (Standard 13 Uhr) zeigt die App "Zur Arbeit", danach "Nach Hause".
- Optional: nur Tram, nur Direktverbindungen, Fussweg zur Haltestelle (blendet unerreichbare Verbindungen aus).
- Aktualisiert sich alle 30 Sek. und bei jedem Öffnen. ⚙ oben rechts = Einstellungen.
