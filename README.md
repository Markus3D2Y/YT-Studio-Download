# YT Studio – Download

Windows-11-Studio für Creator: Low-Poly-Avatar mit Webcam-, iPhone- oder Handy-Kamera-Tracking, Charakter-Editor, Thumbnail-Editor, Highlight Finder, Soundboard, Replay-Clips, YouTube-Downloader und Schnitt, Aufnahme, OBS-Quelle und virtuelle Kamera.

Dieses Repository enthält nur die Installationsdateien. Der Quellcode ist nicht öffentlich.

## Herunterladen

**[➜ Neueste Version herunterladen](https://github.com/Markus3D2Y/YT-Studio-Download/releases/latest)**

Dort unter „Assets“ die Datei `YTStudio-<Version>-Setup-x64.exe` laden und starten.

## Installation

- Voraussetzungen: Windows 11 (64 Bit) und ein aktueller Grafiktreiber.
- Die Installation läuft für das aktuelle Windows-Konto, ohne Administratorrechte. Installationsordner und Desktop-Verknüpfung sind wählbar.
- Fehlt Microsoft WebView2, richtet das Setup es ein; nur dafür ist Internet nötig.
- Das Setup ist nicht mit einem Codesigning-Zertifikat signiert. Windows SmartScreen kann deshalb „Der Computer wurde durch Windows geschützt“ anzeigen: **Weitere Informationen → Trotzdem ausführen**. Die SHA-256-Prüfsumme steht in `YTStudio-<Version>-SHA256SUMS.txt`.

## Soundboard im Spiel (VB-CABLE)

Damit Mitspieler Soundboard und Stimme hören, enthält das Setup **VB-CABLE** von VB-Audio Software – unverändert, Donationware: [www.vb-cable.com](https://vb-audio.com/Cable/). Im Setup ist „VB-CABLE für das Soundboard installieren“ angehakt, wenn es noch fehlt; Windows fragt nach Administratorrechten, im VB-Audio-Fenster „Install Driver“ klicken, danach den PC neu starten. Im Spiel und in Discord einmalig **CABLE Output** als Mikrofon wählen. Wer VB-CABLE nützlich findet, kann VB-Audio mit einer Spende oder Lizenz unterstützen.

## Handy als Soundboard und Kamera

Unter **Soundboard → Handy als Soundboard** zeigt das Studio einen QR-Code. Mit dem iPhone scannen (PC und Handy im selben WLAN), in Safari „Teilen → Zum Home-Bildschirm“ – dann sind die Pads wie eine App auf dem Handy. Im Tab **Kamera** steuert die Handy-Kamera den Avatar wie eine Webcam; dafür führt die Seite einmalig durch die Installation eines Zertifikats (Safari erlaubt die Kamera nur über https; das Zertifikat gilt nur für Heimnetz-Adressen). Fragt Windows nach Netzwerkzugriff, „Private Netzwerke“ erlauben.

## Updates

Einfach das neue Setup starten. Es erkennt die vorhandene Installation und aktualisiert nur die Programmdateien. Charaktere, Avatare, Einstellungen, Thumbnails, Soundboard, Clips und Downloads bleiben erhalten – auch bei einer Deinstallation. VB-CABLE bleibt bei der Deinstallation des Studios installiert (entfernen über das VB-Audio-Setup, „Remove Driver“). Vorher das Studio vollständig beenden (gegebenenfalls über das Symbol im Infobereich neben der Uhr).
