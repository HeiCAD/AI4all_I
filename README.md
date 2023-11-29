<img src="https://www.heicad.hhu.de/fileadmin/_processed_/4/9/csm_ai4all_KeyImage_Blob_Hexa_300px_f87b7be2a1.png"/>

[![Intagram](https://img.shields.io/badge/Instagram-%23E4405F.svg?style=for-the-badge&logo=Instagram&logoColor=white)](https://www.instagram.com/heicad_hhu/)
[![Twitter](https://img.shields.io/badge/Twitter-%231DA1F2.svg?style=for-the-badge&logo=Twitter&logoColor=white)](https://twitter.com/HeiCAD_HHU)
<a href="https://ki-campus.org/courses/kifueralle-hhu" style="width: 120px; height: 28px; background-color: #800080; padding: 2px; border-radius: 0px; display: inline-block;">
  <img src="https://ki-campus.org/sites/default/files/color/kic_theme-ea158196/logo.svg" alt="Your Badge Alt Text">
</a>

# KI Für Alle - Modul 1

Willkommen in unserem Repository für den ersten [KI für Alle](https://ki-campus.org/courses/kifueralle-hhu)-Kurs!

Hier sind alle Materialien und Anleitungen für die verschiedenen Wochenabschnitte und Notebooks zu finden.
Stellt sicher, dass ihr den Anweisungen folgt, damit ihr problemlos auf eurem eigenen Computer arbeiten könnt.
Ihr habt auch die Möglichkeit, [Google Colab](https://colab.research.google.com/?hl=de) oder [Anaconda Cloud](https://anaconda.cloud) zu verwenden.

# Willkommen zu unserem Projekt!

Vielen Dank, dass du dich für unsere Arbeit interessierst.
Um loszulegen, benötigst du `Anaconda` und `Git` auf deinem Computer.
Keine Sorge, es ist einfach!
Hier ist eine Schritt-für-Schritt-Anleitung:

## 1. Anaconda installieren :snake: 

### Schritt 1: Anaconda herunterladen :arrow_down: 

Lade die neueste Version von Anaconda von der offiziellen [Anaconda-Website](https://www.anaconda.com/products/distribution) herunter.
Wähle die passende Version für dein Betriebssystem (Windows, macOS, Linux) aus.

### Schritt 2: Installationsassistent folgen :package: 

Öffne die heruntergeladene Datei und folge den Anweisungen des Installationsassistenten.
Vergiss nicht, die Option auszuwählen, um Anaconda zu deiner Umgebungsvariable (`PATH`) hinzuzufügen, um es global verfügbar zu machen.

### Schritt 3: Teste deine Installation :call_me_hand: 

Öffne die `Anaconda-Navigator`-Anwendung oder starte ein neues `Terminal/CMD` und gib `conda --version` ein.
Wenn alles richtig installiert ist, 
sollte die Versionsnummer angezeigt werden.

## 2. Git installieren :octopus: 

### Schritt 1: Git herunterladen :arrow_down: 

Lade Git von der offiziellen [Git-Website](https://git-scm.com/downloads) herunter.
Wähle die passende Version für dein Betriebssystem aus.

### Schritt 2: Installationsassistent folgen :package:

Öffne die heruntergeladene Datei und folge den Anweisungen des Installationsassistenten. Achte darauf, die Option auszuwählen, um Git in der Kommandozeile verfügbar zu machen.

### Schritt 3: Teste deine Installation :call_me_hand: 

Öffne ein neues `Terminal/CMD` und gib `git --version` ein.
Wenn die Installation erfolgreich war, wird die Git-Version angezeigt.

## Fertig! :hugs: 

Herzlichen Glückwunsch! Du hast nun erfolgreich Anaconda und Git auf deinem Computer installiert.
Wenn du weitere Fragen hast oder Hilfe benötigst, kontaktiere uns. Viel Spaß beim Mitmachen! 😊

# Projekt aus GitHub downloaden :floppy_disk: 

Hier sind zwei einfache Möglichkeiten, wie du unser Repository herunterladen kannst: über HTTPS oder als ZIP-Datei.

## Herunterladen über HTTPS :bouquet: 

Folge diesen Schritten, um das Repository über HTTPS zu klonen:

1. Kopiere den HTTPS-Link des Repositories: `https://github.com/HeiCAD/AI4all_I.git`.
2. Öffne dein Terminal oder die Kommandozeile.
3. Navigiere zu dem Ordner, in den du das Repository klonen möchtest.
4. Führe den Befehl aus: `git clone https://github.com/HeiCAD/AI4all_I.git`.

Und das war's schon! Du hast eine lokale Kopie des Repositories.

## Herunterladen als ZIP :point_up_2:

Wenn du das Repository lieber als ZIP-Datei herunterladen möchtest, folge diesen Schritten:

1. Gehe zu [dieser Seite](https://github.com/HeiCAD/AI4all_I/archive/refs/heads/main.zip).
2. Klicke auf den grünen Button `Code` und wähle `Download ZIP`.

Entpacke die heruntergeladene ZIP-Datei, und schon bist du bereit!

## Fertig! :confetti_ball: 

Du hast erfolgreich unser Repository heruntergeladen. Wenn du Fragen hast oder Hilfe benötigst, zögere nicht, uns zu kontaktieren! 😊

# Erstellen eines Environment mit Anaconda Navigator :globe_with_meridians: 

Diese Schritte zeigen, wie du ein Environment namens `AI4all_I` mithilfe der Datei `environment.yml` erstellen und anschließend ein Notebook darin starten kannst.
Es ist wichtig, dass du weißt, wo du das Repository abgelegt hast!

## Schritt 2: Öffnen von Anaconda Navigator :national_park: 

Starte die `Anaconda Navigator`-Anwendung auf deinem Computer.

## Schritt 3: Erstellen des Environments :nut_and_bolt: 

1. Klicke auf `Environments` im linken Navigationsbereich.
2. Klicke auf `Import` unten links.
3. Wähle `From environment file (YAML)` aus.
4. Navigiere zu dem heruntergeladenen Repository und wähle die Datei `environment.yml` aus.

Anaconda Navigator wird nun das Environment erstellen und alle erforderlichen Pakete installieren.
Dies kann einige Minuten dauern.

## Schritt 4: Aktivieren des Environments :battery: 

1. Gehe zurück zur Registerkarte `Home`in Anaconda Navigator.
2. Wähle das gerade erstellte `AI4all_I` Environment aus der Dropdown-Liste `Applications on` aus, standardmäßig ist `base (root)` ausgewählt.

## Schritt 5: Starten eines Notebooks :rocket: 

1. Klicke auf `Launch` unter `Jupyter Notebook`.

Jetzt öffnet sich Jupyter Notebook in deinem Browser, und du kannst ein neues Notebook erstellen oder ein vorhandenes öffnen.

## Fertig! :thumbsup: 

Du hast erfolgreich das `AI4all_I` Environment erstellt und ein Jupyter Notebook gestartet. 
Viel Spaß beim Programmieren! 😊

# Kontakt und Unterstützung :handshake: 

Falls du Fragen hast, Probleme auftreten oder du einfach nur mit uns in Kontakt treten möchtest, stehen wir dir gerne zur Verfügung. Hier sind verschiedene Möglichkeiten, wie du uns erreichen kannst:

## Mitglieder des Teams: :alien: :vulcan_salute: 

- **Marc Feger** - [@marc](marc.feger@hhu.de)
- **Ludmila Himmelspach** - [@ludmila](ludmila.himmelspach@hhu.de)
- **Ann-Kathrin Selker** - [@ann-kathrin](ann-kathrin.selker@hhu.de)

Fühle dich frei, direkt einen der oben genannten Teammitglieder anzuschreiben, wenn du spezifische Fragen hast.

## Probleme melden: :bomb: 

Wenn du auf ein Problem stößt oder einen Fehler findest, erstelle bitte ein `Issue` in diesem Repository.
Gehe dazu auf die Registerkarte `Issues` oben im Repository und klicke auf `New Issue`. 
Beschreibe das Problem so detailliert wie möglich, damit wir dir schnell und effektiv helfen können.

## Allgemeine Fragen oder Diskussionen: :exploding_head: 

Für allgemeine Fragen oder Diskussionen, die die gesamte Community interessieren könnten, empfehlen wir die Nutzung des `Issue`-Bereichs.
Hier können Ideen ausgetauscht und gemeinsam diskutiert werden.

Wir schätzen deine Beteiligung und stehen bereit, um sicherzustellen, dass dein Beitrag erfolgreich ist! 😊

Beep Boop: Dein HeiCAD-Team :robot: