# Slyke Language Support for Visual Studio Code

Diese VS Code Extension bietet umfassende Unterstützung für die Slyke-Programmiersprache. Slyke ist eine deklarative Sprache, die zur Erstellung moderner, performanter Web-Oberflächen mit Preact entwickelt wurde.

## Features

- **Syntax-Highlighting:** Farbenfrohe Hervorhebung für `.sk`-Dateien, inklusive Kommentaren, Keywords, Strings, HTML-ähnlichen Tags (`<echo>`, `<button>`) und Attributen.
- **Spracherkennung:** Automatische Zuordnung von `.sk`-Dateien zur Slyke-Sprache.
- **Eigenes Icon:** Ein einzigartiges Symbol für Slyke-Dateien in der Explorer-Ansicht.
- **Basis-Code-Unterstützung:** Automatische Klammer-Schließung und Kommentar-Toggling mit `#`.

## Nutzung

1.  Installieren Sie diese Extension über den VS Code Marketplace.
2.  Öffnen Sie eine Datei mit der Endung `.sk`.
3.  Beginnen Sie mit dem Schreiben von Slyke-Code!

**Beispiel Slyke-Code:**

```slyke
# Dies ist ein Kommentar in Slyke
message "Hallo, Slyke Welt!"

<echo message="Diese Nachricht wurde von Slyke gerendert!" />

<button text="Klick mich!" onClick="alert('Hallo von Slyke!');" />

component MyCustomComponent:
  # Hier könnte Ihre eigene Komponente definiert werden
  text "Dies ist eine Komponente"
```
