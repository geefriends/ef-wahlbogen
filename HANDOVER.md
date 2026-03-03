# Handover: EF-Wahlbogen - Ernst-Mach-Gymnasium Hürth

## Projekt-Status

Interaktiver Wahlbogen für die Einführungsphase (EF) der gymnasialen Oberstufe.
- **Live-URL:** https://geefriends.github.io/ef-wahlbogen/
- **Repo:** https://github.com/geefriends/ef-wahlbogen
- **Lokaler Pfad:** `~/Developer/_output/ef-wahlbogen/`
- **Quell-PDF:** `~/Downloads/ .pdf` (7 Seiten, NRW-Broschüre "Die gymnasiale Oberstufe in NRW")
- **Original-Foto:** `~/Downloads/IMG_3771.jpeg` (Wahlbogen-Formular EMG Hürth)

## Features (bereits implementiert)

- Alle Pflichtfächer (1-8) mit Dropdown-Auswahl
- Wahlpflicht- und Wahlfächer (9-11)
- Vertiefungskurse (12-13)
- Auto-Berechnung: Wochenstunden, Grundkurse, Vertiefungskurse, schriftliche Fächer
- Validierung (34-36 Stunden, Pflichtfächer, Doppelbelegung, schriftlich-Regeln)
- Mobile-Responsive (Card-Layout auf Smartphones)
- localStorage Auto-Save (Eingaben bleiben erhalten)
- PDF/Drucken-Button
- Deployed auf GitHub Pages

---

## Extrahierte Regeln aus der NRW-Broschüre (7 Seiten)

### 1. Aufgabenfelder und Fächer (Seite 2)

**Aufgabenfeld I - Sprachlich-literarisch-künstlerisch:**
- Deutsch
- Fremdsprachen: Englisch, Französisch, Russisch, Spanisch, Niederländisch, Italienisch, Japanisch, Lateinisch, Griechisch, Chinesisch, Hebräisch, Türkisch, Neugriechisch, Portugiesisch
- Kunst, Musik

**Aufgabenfeld II - Gesellschaftswissenschaftlich:**
- Geschichte, Geographie, Sozialwissenschaften, Philosophie, Recht, Erziehungswissenschaft, Psychologie

**Aufgabenfeld III - Mathematisch-naturwissenschaftlich-technisch:**
- Mathematik, Physik, Chemie, Biologie, Informatik, Technik, Ernährungslehre

**Ohne Aufgabenfeld:**
- Religionslehre
- Sport

### 2. Vertiefungsfächer (Seite 2)

- Werden insbesondere in **Deutsch, Mathematik und den Fremdsprachen** angeboten
- **Zweistündig** unterrichtet
- Können im **halbjährlichen Wechsel** belegt werden
- In der EF: **je Halbjahr bis zu zwei** Vertiefungsfächer wählbar
- In der Q-Phase: Belegung von insgesamt **zwei Halbjahreskursen** möglich
- **Keine Leistungsnoten** - nur Rückmeldungen über individuellen Lernfortschritt
- Wird auf die **Wochenstundenzahl angerechnet**, aber **NICHT** auf Gesamtqualifikation/Abiturnote

### 3. Unterrichtsorganisation (Seite 3)

- **Grundkurse: 3-stündig**
- **Neu einsetzende Fremdsprachen in der EF: 4-stündig** (WICHTIG - aktuell im Tool nicht berücksichtigt!)
- **Leistungskurse (Q-Phase): 5-stündig**

### 4. Wochenstundenzahl (Seite 6)

- EF und Q-Phase: **durchschnittlich 34 Unterrichtsstunden** pro Woche
- Pflichtunterricht in den drei Jahren der gymnasialen Oberstufe: **mindestens 102 Wochenstunden** insgesamt

### 5. Allgemeine Belegungsverpflichtungen bis zum Abitur (Seite 6)

Durchgängig bis zum Abitur müssen belegt werden:
1. **Deutsch**
2. **Eine Fremdsprache**
3. **Mathematik**
4. **Ein gesellschaftswissenschaftliches Fach**
5. **Ein naturwissenschaftliches Fach** (Biologie, Physik, Chemie)
6. **Sport**
7. **Die Abiturfächer**

Zusätzlich:
- In den vier Halbjahren der Q-Phase: **8 Leistungskurse** und **mindestens 30 anrechenbare Grundkurse**
- Wer in der Sek I **keine zweite Fremdsprache** erlernt hat, muss eine **neu einsetzende Fremdsprache als 4-stündigen Grundkurs** durchgängig bis Ende der Q-Phase belegen
- Je nach fachlichem Schwerpunkt: **eine weitere Fremdsprache ODER ein zusätzliches naturwissenschaftlich-technisches Fach** durchgängig

### 6. Abiturfächer-Bedingungen (Seite 6)

Vier Abiturfächer müssen:
- Von der **EF an belegt** worden sein
- Spätestens ab der Q-Phase **Klausuren** geschrieben haben
- Alle **drei Aufgabenfelder** abdecken
- Aufgabenfeld I kann **nur durch Deutsch oder eine Fremdsprache** abgedeckt werden (nicht Kunst/Musik)
- **Zwei der vier** Abiturfächer müssen aus **Deutsch, Fremdsprache, Mathematik** stammen
- **Erstes Leistungskursfach:** fortgeführte Fremdsprache ODER Naturwissenschaft ODER Deutsch
- Zweiter LK: im Rahmen der Vorgaben frei wählbar

### 7. Einführungsphase - Spezifische Regeln (Seite 6-7)

**Kursanzahl pro Halbjahr:**
- Mindestens **9 Kurse im Pflichtbereich**
- Mindestens **2 Kurse aus dem Wahlbereich**
- **10 Fächer** gehen in die Versetzung ein

**Pflichtbelegung EF (durchgängig, beide Halbjahre):**

| Nr | Bereich | Pflicht |
|----|---------|---------|
| 1 | Aufgabenfeld I | **Deutsch** |
| 2 | Aufgabenfeld I | **Eine fortgeführte Fremdsprache** (aus Sek I) |
| 3 | Aufgabenfeld I | **Weitere Fremdsprache**, sofern nicht ein Fach aus dem naturwiss.-technischen Bereich gewählt wird |
| 4 | Aufgabenfeld I | **Neu einsetzende Fremdsprache** (4-stündig!), sofern in Sek I keine zweite Fremdsprache erlernt wurde |
| 5 | Aufgabenfeld I | **Kunst oder Musik** |
| 6 | Aufgabenfeld II | **Ein Fach** des gesellschaftswiss. Aufgabenfeldes |
| 7 | Aufgabenfeld III | **Mathematik** |
| 8 | Aufgabenfeld III | **Biologie oder Physik oder Chemie** |
| 9 | Aufgabenfeld III | **Ein weiteres naturwiss.-technisches Fach**, sofern nicht zwei Fremdsprachen gewählt werden |
| 10 | Ohne AF | **Religionslehre** (bzw. Philosophie als Ersatzfach) |
| 11 | Ohne AF | **Sport** |
| 12 | Wahlbereich | Weitere Fächer |
| 13 | Wahlbereich | Vertiefungsfächer |

**Schwerpunkt-Regel (WICHTIG - Seite 5 + 7):**

Jeder Schüler muss einen fachlichen Schwerpunkt bilden. Das geschieht durch die Belegung von entweder:
- **Zwei Fremdsprachen** (= sprachlicher Schwerpunkt), ODER
- **Zwei naturwissenschaftlich-technischen Fächern** (= MINT-Schwerpunkt)

**Wie das konkret funktioniert:**

Alle Schüler müssen im Pflichtbereich bereits belegen:
- Eine fortgeführte Fremdsprache (Nr. 2 in der Tabelle)
- Mathematik (Nr. 7)
- Eine Naturwissenschaft: BI, CH oder PH (Nr. 8)

Der Schwerpunkt entsteht dann durch die **zusätzliche** Wahl:

| Schwerpunkt | Was zusätzlich belegt werden muss | Beispiel |
|-------------|-----------------------------------|---------|
| **Sprachlich** | Eine **zweite Fremdsprache** (Nr. 3 oder 9) - entweder fortgeführt (F, L) oder neu einsetzend (S = 4-stündig!) | Englisch + Französisch |
| **MINT** | Ein **zweites naturwiss.-technisches Fach** (Nr. 9) zusätzlich zur Pflicht-Naturwiss. | Biologie + Chemie, oder Biologie + Informatik |

**Entscheidungslogik im Klartext:**

> "Hast du zwei Fremdsprachen? Dann brauchst du kein zweites NaWi-Fach (darfst aber).
> Hast du nur eine Fremdsprache? Dann MUSST du ein zweites NaWi/Technik-Fach belegen."

**Sonderfall - Keine zweite Fremdsprache aus der Sek I:**
Wer in der Sekundarstufe I keine zweite Fremdsprache erlernt hat (z.B. nur Englisch), MUSS in der Oberstufe eine neu einsetzende Fremdsprache wählen (z.B. Spanisch). Diese ist dann **4-stündig** statt 3-stündig. In diesem Fall ist der sprachliche Schwerpunkt automatisch erfüllt.

**Warum das wichtig ist:**
Die Schwerpunktwahl in der EF bestimmt die gesamte weitere Schullaufbahn, weil in der Qualifikationsphase (Q1/Q2) nur Fächer gewählt werden können, die bereits in der EF belegt wurden. Wer also in der EF keinen MINT-Schwerpunkt legt, kann in der Q-Phase kein zweites NaWi-Fach mehr dazunehmen.

**Für das Wahlbogen-Tool bedeutet das:**
Das Tool muss prüfen, ob der Schüler insgesamt mindestens 2 Fremdsprachen ODER mindestens 2 NaWi/Technik-Fächer (aus: BI, CH, PH, IF, Technik, Ernährungslehre) gewählt hat. Wenn keines von beidem erfüllt ist, muss eine Warnung erscheinen.

### 8. Weitere Vorgaben für Q-Phase (Seite 7)

- In der Q-Phase können **nur Fächer gewählt werden, die schon in der EF belegt** wurden
- Ausnahmen: Literatur, vokal-/instrumentalpraktische Kurse, Zusatzkurse GE/SW, Vertiefungsfächer, Projektkurse
- Wenn weder **Geschichte noch Sozialwissenschaften** im Aufgabenfeld II gewählt: Zusatzkurs im 2. Jahr Q-Phase Pflicht
- **Philosophie** kann nicht gleichzeitig einziges Fach des Aufgabenfeldes II UND Ersatz für Religionslehre sein
- Religionslehre ist keinem Aufgabenfeld zugeordnet, kann aber in der Abiturprüfung als gesellschaftswissenschaftliches Aufgabenfeld vertreten. In diesem Fall muss zusätzlich ein gesellschaftswissenschaftliches Fach durchgängig belegt werden.

---

## Abweichungen / Verbesserungen für den Wahlbogen

Das aktuelle Tool weicht in folgenden Punkten von den offiziellen Regeln ab:

### Muss gefixt werden:

1. **Neu einsetzende Fremdsprache = 4 Stunden, nicht 3**
   - Spanisch (S) als neu einsetzende Fremdsprache muss 4-stündig sein
   - Im Dropdown sollte das klar markiert sein, und die Stunden automatisch auf 4 gesetzt werden

2. **Schwerpunkt-Validierung fehlt**
   - Tool muss prüfen: Entweder 2 Fremdsprachen ODER 2 NaWi/Technik-Fächer
   - Warnung wenn weder noch erfüllt ist

3. **Fehlende Fächer in den Dropdowns:**
   - Aufgabenfeld II: **Geographie** (statt nur "Erdkunde"), **Recht**, **Erziehungswissenschaft** fehlen
   - Aufgabenfeld III: **Informatik** ist vorhanden, aber **Technik** und **Ernährungslehre** fehlen
   - Hinweis: Nicht alle Fächer werden an jeder Schule angeboten. EMG-spezifisches Angebot prüfen.

4. **Religionslehre ist KEIN Aufgabenfeld II**
   - Im aktuellen Tool steht bei Nr. 7 "Aufgabenfeld II" - das ist falsch
   - Religionslehre gehört zu KEINEM Aufgabenfeld (kann aber in der Abiturprüfung das AF II vertreten)

5. **Mindestens 9 Pflichtkurse + 2 Wahlkurse pro Halbjahr**
   - Aktuell prüft das Tool nur 34-36 Gesamtstunden
   - Sollte auch die Anzahl der Kurse validieren (min. 11 Kurse gesamt)

6. **Philosophie-Sonderregel**
   - Wenn Philosophie als Ersatz für Religion gewählt wird UND gleichzeitig einziges Fach im AF II ist: ungültig
   - Braucht Validierungslogik

### Nice-to-have:

7. **Vorausschau Q-Phase / Abitur**
   - Hinweis: "Bedenke, dass du in der Q-Phase nur Fächer wählen kannst, die du in der EF belegt hast"
   - Info-Box: "Für das Abitur brauchst du 4 Fächer aus allen 3 Aufgabenfeldern"

8. **Versetzungsrelevanz**
   - 10 Fächer gehen in die Versetzung ein - könnte markiert werden

---

## Dateien

```
~/Developer/_output/ef-wahlbogen/
├── index.html              ← GitHub Pages entry (Kopie von wahlbogen-ef.html)
├── wahlbogen-ef.html       ← Hauptdatei (interaktiver Wahlbogen)
├── HANDOVER.md             ← Dieses Dokument
└── .git/                   ← Git repo → github.com/geefriends/ef-wahlbogen
```

## Quell-Dokumente

| Datei | Beschreibung |
|-------|-------------|
| `~/Downloads/IMG_3771.jpeg` | Foto des Original-Wahlbogens (EMG Hürth) |
| `~/Downloads/ .pdf` | NRW-Broschüre "Die gymnasiale Oberstufe" (7 Seiten, gescannt) |
| `/tmp/ef-pdf-pages/page-{1-7}.jpg` | Extrahierte Einzelseiten als JPEG |

## Nächste Schritte

1. EMG-spezifisches Fächerangebot abklären (welche Fächer bietet die Schule tatsächlich an?)
2. Oben genannte Fixes implementieren (besonders: 4-stündige neu einsetzende Fremdsprache, Schwerpunkt-Validierung, AF-Zuordnung Religion)
3. Nach Fixes: GitHub Pages aktualisieren (`git push`)
