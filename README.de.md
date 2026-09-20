# Lumen — Desktop Orb

[![Website](https://img.shields.io/badge/Website-lumen--orb-38bdf8)](https://alex-stark-industries.github.io/Lumen-Desktop-Orb/)
[![Download](https://img.shields.io/badge/Download-Latest%20Release-38bdf8?logo=github)](../../releases/latest)
[![License](https://img.shields.io/badge/License-Free%20to%20use-2ea44f)](LICENSE)
[![Platform](https://img.shields.io/badge/Windows-10%20%2F%2011-0078D6?logo=windows)](../../releases/latest)

**Eine winzige Sprachkugel, die auf deinem Desktop lebt.**
Rechtsklick öffnet ein Menü mit schnellen Befehlen — die Uhrzeit, den Systemstatus,
das Wetter, eine Websuche, eine beliebige App per Namen öffnen — jeder davon
**sofort** beantwortet und mit einer echten Stimme **laut vorgelesen**.

> **Kein Konto. Kein Abo. Kein Sprachmodell. Keine Cloud.**
> Nur ein kleines schwebendes Licht, das schnell antwortet und nicht im Weg steht.

---

### Highlights

- 🔵 **Eine lebendige Partikelkugel** — eine sanft leuchtende Kugel, die im Ruhezustand treibt und beim Sprechen zu einer flüssigen Welle anschwillt.
- ⚡ **Sofortige Antworten** — jeder Schnellbefehl ist eine deterministische Abfrage oder Aktion, kein "nachdenkendes" Modell. Nichts, worauf man warten müsste.
- 🎙️ **Eine echte gesprochene Stimme** — eine richtige neuronale Stimme, lokal auf dem Gerät, keine robotische System-TTS.
- 🖱️ **Rechtsklick für alles** — ein sauberes, eigenes Menü ist die gesamte Oberfläche. Keine Fenster zu verwalten, keine Einstellungen zu durchsuchen.
- 🌦️ **Wetter, Websuche, jede App per Namen öffnen** — die wenigen Befehle, die ein Wort oder zwei brauchen, fragen einfach direkt danach.
- 🪶 **Klein und unauffällig** — kein Sprachmodell, kein Mehrgigabyte-Download, kein Hintergrunddienst. Es lädt nur einmalig die Stimme selbst herunter.

---

### Screenshots

<table>
<tr>
<td width="50%">

**Die Kugel** — im Ruhezustand, ruhig auf dem Desktop treibend.
<img src="docs/screenshots/orb.png" alt="Lumen desktop orb" width="100%">

</td>
<td width="50%">

**Rechtsklick-Menü** — jeder Befehl nur einen Klick entfernt.
<img src="docs/screenshots/menu.png" alt="Lumen right-click command menu" width="100%">

</td>
</tr>
</table>

---

### Download & Installation

1. Öffne die [**Releases**](../../releases/latest)-Seite und lade
   `Lumen Setup <Version>.exe` herunter.
2. Führe sie aus. Der Installer ist **pro Benutzer** — es sind **keine Administratorrechte** nötig.
3. Lumen erscheint als kleine leuchtende Kugel unten rechts auf dem Bildschirm.

> **Erster Start:** Der Installer ist nicht digital signiert, daher zeigt Windows SmartScreen
> möglicherweise *"Windows hat Ihren PC geschützt"*. Klicke auf **Weitere Informationen → Trotzdem ausführen**.
> Das ist normal für eine kostenlose, unabhängige App.

Neu hier? Der [**Willkommensguide**](WELCOME.md) begleitet dich Schritt für Schritt
durch Installation und ersten Befehl, ohne etwas vorauszusetzen.

**Keine weitere Einrichtung nötig** — anders als größere KI-Assistenten hat Lumen
kein Modell, das vorher heruntergeladen oder installiert werden müsste. Die allererste
gesprochene Antwort lädt ein kleines Sprachmodell herunter (einige hundert MB, einmalig);
alles danach ist sofort verfügbar und komplett offline.

---

### Dokumentation

| Dokument | Inhalt |
|---|---|
| [Willkommensguide](WELCOME.md) | Für Einsteiger, Schritt für Schritt: Installation, Start, erster Befehl |
| [Befehlsübersicht](GUIDE.md) | Jeder Befehl, was er tut und wie man ihn benutzt |
| [Datenschutz](PRIVACY.md) | Genau, was das Netzwerk berührt (und was nicht) |
| [Lizenz](LICENSE) | Kostenlos nutzbar — vollständige Bedingungen |
| [Hinweise zu Drittanbietern](THIRD-PARTY-NOTICES.md) | Open-Source-Komponenten, mit denen Lumen gebaut ist |

---

### Systemanforderungen

| | Minimum |
|---|---|
| **Betriebssystem** | Windows 10 / 11, 64-Bit |
| **RAM** | 4 GB |
| **Freier Speicher** | ~500 MB (App + Sprachmodell) |
| **Internet** | Nur für den einmaligen Download des Sprachmodells sowie die Befehle Wetter / Websuche |

Alles andere — die Uhr, der Systemstatus, das Öffnen von Apps, das Menü selbst —
funktioniert vollständig offline.

---

### Datenschutz auf einen Blick

- **Keine Konten, keine API-Schlüssel, keine Telemetrie, keine Analyse.**
- **Nirgendwo läuft ein Sprachmodell** — jeder Befehl ist eine kleine, feste
  Routine, keine KI, die entscheidet, was zu tun ist.
- Die Stimme (Text-zu-Sprache) läuft **auf dem Gerät**, nach einem einmaligen Download.
- Lumen **aktualisiert sich selbst** — sie prüft im Hintergrund still bei GitHub nach
  und installiert neue Versionen von selbst, damit du nie hierher zurückkommen musst,
  um einen Fix zu holen.
- Die einzige Netzwerknutzung, immer: dieser einmalige Sprachmodell-Download, die
  Update-Prüfung und die zwei Befehle, die ausdrücklich die Außenwelt betreffen
  (**Wetter**, **Websuche**).

Vollständige Details: [PRIVACY.md](PRIVACY.md).

---

### Lizenz

Kostenlos nutzbar — aber das ist eine Lizenz, keine Open-Source-Software: keine Weitergabe,
kein Weiterverkauf, keine Veränderung. Vollständige Bedingungen siehe [LICENSE](LICENSE).

*Nicht verbunden mit, gesponsert von oder assoziiert mit irgendeinem Film, Spiel,
Franchise oder einer Marke. "Lumen" ist einfach Latein für "Licht".*

---

In einer anderen Sprache lesen: [English](README.md) · [Italiano](README.it.md) · [Français](README.fr.md) · [Español](README.es.md) · [हिन्दी](README.hi.md)
