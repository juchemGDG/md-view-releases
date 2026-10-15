# MD-View

MD-View zeigt Obsidian-Notizen so an wie Obsidians Leseansicht – mit
CSS-Snippets, Callouts, Formeln und Druckregeln – und druckt sie als
Arbeitsblatt oder Lernbaustein (Schüler- oder Lehrerfassung, farbig oder
schwarz-weiß). Notizen lassen sich direkt im Blatt bearbeiten.

## Herunterladen

Die aktuelle Version steht unter
**[Releases](https://github.com/juchemGDG/md-view-releases/releases/latest)**.

| System | Datei |
|---|---|
| macOS (Apple Silicon und Intel) | `MD-View_…_universal.dmg` |
| Windows | `MD-View_…_x64-setup.exe` oder `…_x64_en-US.msi` |
| Linux | `.AppImage`, `.deb` oder `.rpm` |

## Erster Start

Die App ist nicht bei Apple bzw. Microsoft signiert.

- **macOS:** Beim ersten Öffnen meldet macOS, dass die App nicht überprüft
  werden kann. Dann in *Systemeinstellungen → Datenschutz & Sicherheit*
  ganz unten „Dennoch öffnen“ wählen. Meldet macOS, die App sei
  „beschädigt“, im Terminal einmal ausführen:
  `xattr -cr /Applications/MD-View.app`
- **Windows:** Bei „Der Computer wurde durch Windows geschützt“ auf
  „Weitere Informationen“ → „Trotzdem ausführen“ klicken.

Dieses Repository enthält nur die Installer; der Quellcode ist privat.
