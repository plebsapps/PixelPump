# PixelPump Fitness App

Das PixelPump-Projekt besteht aus einer App für die PixelWatch und einer Web-Komponente.

Beide Komponenten teilen einige gemeinsame Klassen und Funktionen,

während andere spezifisch für die jeweilige Plattform sind.

## Projektstruktur

ch.plebsapps.pixelpump/
│
├── common/                # Gemeinsame Klassen und Funktionen für App und Web
│   ├── model/             # Geschäftslogik-Modelle
│   │   ├── Ausruestung.java
│   │   ├── Uebung.java
│   │   ├── Trainingseinheit.java
│   │   └── MuskelGruppe.java
│   │
│   └── util/              # Gemeinsame Hilfsklassen oder Funktionen
│

├── app/                   # PixelWatch App spezifische Klassen und Ressourcen

│   ├── ui/                # UI Komponenten

│   │   ├── activities/   # Hauptbildschirme

│   │   ├── fragments/    # UI Fragmente

│   │   ├── adapters/     # Datenadapter für Listen, etc.

│   │   └── views/        # Benutzerdefinierte Ansichten

│   │

│   ├── database/         # Klassen zur Datenbankinteraktion für die App

│   │

│   ├── services/         # Hintergrunddienste, Notifications, etc.

│   │

│   └── util/             # App-spezifische Hilfsklassen oder Funktionen

│

└── web/                  # Web-spezifische Klassen und Ressourcen

├── controllers/      # Web-Controller für verschiedene Endpunkte

│

├── views/            # HTML- oder Template-Dateien für die Webansicht

│

├── database/        # Klassen zur Datenbankinteraktion für das Web

│

├── services/        # Web-spezifische Dienste

│

└── util/            # Web-spezifische Hilfsklassen oder Funktionen

Gemeinsame Klassen (common)

Dieser Abschnitt enthält Klassen und Funktionen, die sowohl von der App als auch von der Web-Komponente geteilt werden. Das Hauptziel ist es, die Wiederverwendbarkeit zu maximieren und Duplikation zu vermeiden.

PixelWatch App (app)

Diese Ebene ist speziell für die PixelWatch-App und enthält alle notwendigen Ressourcen, um die App zu erstellen und auszuführen. Hier finden Sie alles, von der Benutzeroberfläche bis zur Datenbankinteraktion.

Web-Komponente (web)

Ähnlich wie die App-Ebene, aber speziell für die Web-Komponente des Projekts. Dies beinhaltet alles, was für die Erstellung und Ausführung der Webanwendung benötigt wird.

