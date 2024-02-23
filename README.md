# Demo für GitHub Actions #

<br>

Diese Repo enthält neben dieser README-Datei nur eine Workflow-Datei für *GitHub Actions*.

<br>

Die Worfklow-Datei liegt im Unterordner [.github/workflows/](.github/workflows/) dieses Repos.

<br>

Die Workflow-Datei erzeugt eine einfache Textdatei mit Informationen zum aktuellen Datum und stellt diese Textdatei zum Download bereit.
Hierzu wird folgende Linux-Befehl ausgeführt:

```
date '+%e.%m.%Y: %A, %j. Tag im Jahr, liegt in Kalenderwoche %V.' > datum.txt
```

<br>