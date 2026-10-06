<!-- ELUCENIA technical documentation · cage · de · no clinical/professional/rights approval -->

# CAGE-Fragebogen

[Bedingungen, Quellen und Berechtigungen](https://elucenia.org/de/werkzeuge/cage)

## Verwendung

Verwenden Sie das Werkzeug im Portal oder öffnen Sie index.html über einen lokalen HTTP-Server. Wählen Sie die Sprache, füllen Sie die Felder aus und berechnen Sie das Ergebnis.

## Eingaben und Einheiten

### C – Hatten Sie jemals das Gefühl, weniger Alkohol trinken oder ganz aufhören zu sollen?

`c`

### A – Ärgern Sie sich, wenn andere Ihren Alkoholkonsum kritisieren?

`a`

### G – Fühlen Sie sich wegen Ihrer üblichen Trinkweise schuldig?

`g`

### E – Trinken Sie gewöhnlich morgens Alkohol, um Nervosität oder einen Kater zu lindern?

`e`

## Fassung der Methode

CAGE/Ewing 1984: 4 binäre Fragen, 0–4, Schwelle≥2; Portugiesisch Masur–Monteiro 1983

## Dokumentierte Formel

Ein Punkt je Antwort “ja”: Cut down (reduzieren), Annoyed (Ärger über Kritik), Guilty (Schuldgefühl), Eye-opener (Trinken nach Erwachen). Grenzwert: ≥ 2.

## Grenzen und Population

Kurzer Screeningfragebogen für Alkoholprobleme mit anschließender klinischer Beurteilung. Die zitierte brasilianische Validierung betraf Männer in psychiatrischer stationärer Behandlung; gleiche Leistung in anderen Populationen darf nicht vorausgesetzt werden. Die Zusammensetzung dieser Kohorte ist keine universelle geschlechtsbezogene Ausschlussregel.

## Referenzen

- [Ewing JA. Detecting alcoholism: the CAGE questionnaire. JAMA, 1984.](https://doi.org/10.1001/jama.1984.03350140051025)

- [Masur J, Monteiro MG. Validation of the "CAGE" alcoholism screening test in a Brazilian psychiatric inpatient hospital setting. Braz J Med Biol Res, 1983.](https://pubmed.ncbi.nlm.nih.gov/6652293/)

## Technische Tests reproduzieren

Führen Sie node test.cjs im Stammverzeichnis dieses Repositorys aus, um die dokumentierten synthetischen Fälle zu wiederholen. Ursprüngliche Eingaben, erwartete Ergebnisse und Toleranzen bleiben erhalten. Technische Tests stellen keine klinische Validierung dar.

```sh
node test.cjs
```

tool.json enthält Quellen, Ausgabe und Umfang der Überprüfung. examples.json bewahrt die synthetischen Eingaben und erwarteten Ergebnisse; results.json dokumentiert die tatsächlich erhaltenen Ergebnisse.

[Eintrag und Referenzen](../tool.json) · [JavaScript-Code](../calculator.js) · [Referenzfälle](../examples.json) · [results.json](../results.json)

## Überprüfung und Nutzungsbedingungen

Eine unabhängige klinische Prüfung wurde nicht durchgeführt.

Diese Benutzeroberfläche ist eine selbst erstellte Übersetzung und keine offizielle oder zertifizierte Ausgabe. Eine unabhängige klinische Überprüfung, eine professionelle sprachliche Prüfung und eine Klärung der Rechte an den Instrumenten wurden nicht durchgeführt.

Ergebnis der Formel oder Klassifikation. Interpretation, Vorgehen und Anwendbarkeit hängen von der fachlichen Beurteilung und der ausgewählten Quelle ab.

## Lizenz und Urheberangaben

Apache-2.0 gilt nur für den ELUCENIA-Code. Die Rechte an Instrumenten, Veröffentlichungen, Übersetzungen und Daten verbleiben bei den jeweiligen Rechteinhabern. Bewahren Sie LICENSE und NOTICE auf.

ELUCENIA · Felipe Guedes · Copyright © 2026

## Dokumentierte Ergebnisse

Die folgenden Angaben bewahren die Ausgaben der Methode für synthetische Beispiele. Sie stellen keine unabhängige klinische Validierung dar.

### 1

Negatives Screening

Ein negatives CAGE schließt einen aktuellen Risikokonsum nicht aus: bevorzugen Sie den AUDIT zur Erfassung des Konsums.


### 2

Eine positive Antwort: unterhalb des Cut-offs

Fragen Sie nach Menge und Häufigkeit des Konsums (AUDIT).


### 3

Positives Screening (≥ 2): Verdacht auf Alkoholmissbrauch oder -abhängigkeit

Screening-Instrument: durch klinische Beurteilung bestätigen.

