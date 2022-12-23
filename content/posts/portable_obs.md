---
title: "Portable OBS"
date: 2022-12-23T04:12:05+01:00
draft: false
toc: false
images:
tags:
  - tutorial
  - blog
  - obs
  - windows
---
In diesem Tutorial zeige ich euch wie ihr OBS komplett portabel nutzen könnt. (Das bedeutet, sämtliche Configfiles befinden sich im selben Ordner --> perfekt für ein Backup)

## OBS herunterladen

Geht auf die offizielle Homepage des OBS-Projects und ladet euch die **.zip Datei** herunter.
[OBS Download](https://obsproject.com/de/download)
![obs_download](/img/obs_portable/OBS_portable_download.png)

## Dateien entpacken und vorbereiten

Wählt einen beliebigen Speicherort wo ihr OBS hinhaben wollt und entpackt die **.zip** dorthin.
Nach dem Entpacken sollte der Inhalt eures Ordners so aussehen:

![OBS_portable_raw.PNG](/img/obs_portable/OBS_portable_raw.PNG)

```
WICHTIG: OBS jetzt nocht nicht starten!!
``` 

## Verknüpfung anlegen

1. Den Ordner **bin** und **64bit** öffnen.
2. Die Datei **obs64.exe** suchen. Auf diese Datei rechtsklicken und eine Verknüpfung erstellen.
3. Die Verknüpfung schieben wir am besten in unseren OBS-Stammordner. Unser Ordner sollte nun so aussehen:

![OBS_portable_shortcut.PNG](/img/obs_portable/OBS_portable_shortcut.PNG)

4. Rechtsklick auf die Verknüpfung und **Eigenschaften** auswählen.
5. Im Feld **"Ziel"** hinter dem Pfad *--portable* dazuschreiben.

```
C:\[pfad_zum_ordner]\bin\64bit\obs64.exe --portable
```

![OBS_portable_ziel.PNG](/img/obs_portable/OBS_portable_ziel.PNG)

6. Fertig! Wir können nun die Verknüpfung öffnen und unser OBS normal konfigurieren. Um sicher zu gehen, dass alles funktioniert hat, können wir nochmal in den OBS Ordner surfen. Nun sollte ein neuer Ordner namens **Config** angelegt worden sein. Hier werden nun alle Dateien abgelegt, die sonst irgendwo versteckt im System angelegt werden.

![OBS_portable_config.PNG](/img/obs_portable/OBS_portable_config.PNG)

## Backup

Wenn wir nun unser OBS sichern wollen, können wir einfach den kompletten Ordner nehmen und zB auf Google Drive/Dropbox o.ä. sichern.

## Bonustipps

1. Sämtliche Assets in einen eigenen Unterordner speichern. So werden diese ebenfalls gleich mitgesichert.