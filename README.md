# GestureDJ – Spotify per Handgesten steuern

<img src="icon.png" width="120" align="right">

GestureDJ steuert Spotify über die Frontkamera:

- ☝️ **Zeigefinger-Kreis** im Uhrzeigersinn = lauter, gegen den Uhrzeigersinn = leiser
- ✋ **Offene Hand nach rechts / links wischen** = nächster / vorheriger Song
- ✋ **Offene Hand 1 Sekunde halten** = Play / Pause

Die Kamerabilder werden nur auf dem iPhone ausgewertet und nie gespeichert oder verschickt.

## Voraussetzungen

1. iPhone mit **iOS 17** oder neuer und installierter **Spotify-App**.
2. **Freischaltung bei Spotify:** Schick deine Spotify-E-Mail-Adresse an Justin. Ohne Freischaltung verbindet sich die App nicht mit Spotify.

## Installation (einmalig, ca. 15 Minuten)

### Schritt 1: SideStore installieren

SideStore ist ein kostenloser App-Store für eigene Apps. Er erneuert die Apps alle 7 Tage direkt auf dem iPhone, ohne Kabel.

Folge der offiziellen Anleitung: **https://docs.sidestore.io/docs/installation/prerequisites**
(Du brauchst dafür einmalig einen Windows-PC oder Mac und deine Apple-ID.)

> AltStore (https://altstore.io) funktioniert genauso, braucht für die Erneuerung aber einen PC im selben WLAN.

### Schritt 2: GestureDJ-Quelle hinzufügen

Öffne diesen Link **auf dem iPhone**:

- SideStore: **[GestureDJ zu SideStore hinzufügen](https://g6c6tc6822-alt.github.io/gesturedj-source/)**
- AltStore: **[GestureDJ zu AltStore hinzufügen](https://g6c6tc6822-alt.github.io/gesturedj-source/)**

Klappt der Link nicht, geh in SideStore/AltStore auf **Quellen → +** und füge diese Adresse ein:

```
https://raw.githubusercontent.com/g6c6tc6822-alt/gesturedj-source/main/apps.json
```

### Schritt 3: Installieren

In der Quelle **GestureDJ** antippen → **Installieren**. Updates erscheinen danach automatisch in SideStore/AltStore.

## Erster Start

1. Kamera erlauben.
2. Die App springt einmal zu Spotify → bestätigen → zurück zu GestureDJ. Der Punkt oben links wird grün.
3. Handy aufstellen, Hand 30–60 cm vor die Frontkamera halten.

Falls eine Geste in die falsche Richtung wirkt: Zahnrad → „Wischrichtung / Kreisrichtung umkehren“.

## Tipp: GestureDJ automatisch mit Spotify öffnen

Kurzbefehle → **Automation** → **+** → **App** → Spotify, „Wird geöffnet“ → **Sofort ausführen** → Neue leere Automation → Aktion **App öffnen: GestureDJ**.

## Direkter Download

Die `.ipa` jeder Version gibt es unter [Releases](https://github.com/g6c6tc6822-alt/gesturedj-source/releases), z. B. für Sideloadly.
