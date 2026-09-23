# Bewerbungsmaterial: Kundenanalyse Online-Retail

Persönliches Referenzdokument für Bewerbungen, LinkedIn und Vorstellungsgespräche zu diesem Projekt. Nicht Teil der technischen Projektdokumentation (siehe [`README.md`](../README.md)).

## Für den Lebenslauf (kurz, 3–4 Zeilen)

> **Kundenanalyse Online-Retail (Privates Portfolio-Projekt)**
> Python (pandas) & Power BI | github.com/Sukram-ux/online-retail-customer-analyse
> Kundensegmentierung (RFM) und Kohorten-/Retentionsanalyse für 800.000+ Transaktionsdatensätze eines Online-Händlers; identifizierte, dass 30 % der Kunden 82 % des Umsatzes erwirtschaften. Interaktives Power-BI-Dashboard mit 3 datenbasierten Handlungsempfehlungen für das Marketing-Team entwickelt.

## Für LinkedIn / Portfolio-Website (ausführlicher)

> **Kundenanalyse für einen Online-Händler: Wer sind die wertvollsten Kunden – und wie hält man sie?**
>
> In diesem End-to-End-Projekt habe ich über 1 Million Transaktionsdatensätze eines britischen Online-Händlers (2009–2011) bereinigt und analysiert, um Marketingentscheidungen datenbasiert zu unterstützen. Mit Python (pandas) habe ich die Rohdaten bereinigt (Duplikate, fehlerhafte Buchungen, Stornos) und eine RFM-Segmentierung (Recency, Frequency, Monetary) sowie eine Kohorten-/Retentionsanalyse durchgeführt. Zentrale Erkenntnis: Nur 30 % der Kunden erwirtschaften über 80 % des Umsatzes – gleichzeitig kauft die Mehrheit der Kunden nur ein einziges Mal. Die Ergebnisse habe ich in einem interaktiven Power-BI-Dashboard visualisiert (filterbar nach Zeitraum und Land) und daraus drei konkrete, messbare Handlungsempfehlungen für das Marketing-Team abgeleitet – u. a. eine gezielte Reaktivierungskampagne für inaktive Kunden und eine automatisierte Follow-up-Maßnahme zur Steigerung der Wiederkaufrate.
>
> **Tech-Stack:** Python, pandas, Jupyter, Power BI, DAX, Git/GitHub

## Für ein Anschreiben (1–2 Sätze als Baustein)

> In einem eigenständigen Analyseprojekt habe ich anhand realer Transaktionsdaten eines Online-Händlers gezeigt, wie ich mit Python und Power BI aus Rohdaten konkrete, umsetzbare Geschäftsempfehlungen ableite – von der Datenbereinigung über die Kundensegmentierung bis zum interaktiven Dashboard.

### Wie und wo Links im Anschreiben platzieren

Nicht in den Fließtext einstreuen – wirkt schnell wie eine Linkliste. Stattdessen:

1. **Im Kontaktdaten-Block oben (Briefkopf)**, neben Adresse/Telefon/E-Mail, das GitHub-**Profil** verlinken (nicht einzelne Repos):
   ```
   Markus Landwehr
   [Adresse]
   [Telefon] · [E-Mail]
   GitHub: github.com/Sukram-ux
   ```
2. **Im Fließtext** beim Erwähnen des Projekts keinen rohen Link setzen, sondern sprachlich darauf verweisen: *"...Details dazu finden Sie auf meinem GitHub-Profil."*
3. **Ausnahme, wenn beide Projekte (dieses und das SQL-Projekt) genannt werden sollen:** kurz vor der Grußformel eine kompakte Referenzzeile:
   > Beispiele meiner Arbeit: github.com/Sukram-ux/online-retail-customer-analyse · github.com/Sukram-ux/music-store-sql-sales-analyse

---

## Kernaussagen für Vorstellungsgespräche (ehrlich, aber überzeugend)

### Elevator-Pitch / STAR-Antwort ("Erzähl mir von einem Projekt, auf das du stolz bist")

> "Ich wollte in meinem Portfolio zeigen, dass ich nicht nur Diagramme bauen, sondern aus rohen Daten echte Geschäftsentscheidungen ableiten kann. Dafür habe ich mir einen unbereinigten Transaktionsdatensatz eines Online-Händlers vorgenommen – über eine Million Zeilen, mit Duplikaten, Stornos und fehlerhaften Buchungen. Ich habe die Daten in Python bereinigt, eine RFM-Kundensegmentierung und eine Kohorten-Retentionsanalyse durchgeführt und die Ergebnisse in einem interaktiven Power-BI-Dashboard zusammengeführt. Die wichtigste Erkenntnis: Nur 30 % der Kunden erwirtschaften über 80 % des Umsatzes, und die meisten Kunden kaufen nur ein einziges Mal. Daraus habe ich drei konkrete Handlungsempfehlungen mit messbaren Zielen abgeleitet, zum Beispiel eine gezielte Reaktivierungskampagne für inaktive Kunden."

### Einzelne Kernaussagen (belastbar, mit Zahlen)

- "Ich habe mit pandas über 1 Million Rohdatensätze bereinigt und auf eine belastbare, analysefähige Datenbasis von ca. 800.000 Zeilen reduziert – inklusive Umgang mit Duplikaten, negativen Preisen und Stornobuchungen."
- "Meine RFM-Analyse hat das Pareto-Prinzip in den Daten bestätigt: 30 % der Kunden erwirtschaften über 80 % des Umsatzes."
- "Die Kohortenanalyse hat gezeigt, dass die Kundenbindung das eigentliche Problem ist, nicht die Neukundengewinnung – die Retention fällt bereits nach dem ersten Monat auf 15–35 % und bleibt dauerhaft niedrig."
- "Ich habe ein interaktives Power-BI-Dashboard mit Datenmodell, DAX-Measures und mehreren verknüpften Tabellen selbst aufgebaut, nicht nur einzelne Diagramme erstellt."

### Ehrliche Einschränkungen, wenn kritisch nachgefragt wird

- "Die Segmentierung basiert auf einer einfachen, gut nachvollziehbaren Quartils-Methode – kein statistisches Clustering. Für dieses Projekt war das ausreichend und leicht erklärbar, für eine größere Kundenbasis würde ich zusätzlich z. B. k-Means in Betracht ziehen."
- "Meine Erklärung für die saisonalen Umsatzspitzen (vermutlich Wiederverkäufer, die vor Weihnachten Lager aufbauen) ist eine plausible Hypothese, keine bewiesene Tatsache – dafür fehlen mir Daten zum Kundentyp."
- "Ob meine Handlungsempfehlungen tatsächlich wirken, weiß ich nicht – deshalb habe ich sie mit messbaren Zielen versehen, die man nach einer Umsetzung im echten Betrieb überprüfen müsste, im Idealfall mit einem A/B-Test."

---

## Mögliche Interviewfragen zu diesem Projekt

### Datenbereinigung
- **"Warum hast du Zeilen ohne Customer ID entfernt, statt sie zu behalten?"** → Ohne Kunden-ID keine kundenbezogene Auswertung (RFM, Kohorten) möglich; ca. 25 % der Zeilen betroffen – bewusste Entscheidung, kein Zufall.
- **"Wie bist du mit stornierten Bestellungen umgegangen?"** → Nicht gelöscht, sondern über `is_cancellation`-Flag markiert; fließen in Netto-Umsatz ein, wurden aber z. B. bei Frequency ausgeschlossen.

### RFM-Segmentierung
- **"Warum genau diese vier Segmente, und wie sind die Grenzen entstanden?"** → Quartilsbasierte Scores (`qcut`) für Recency/Frequency/Monetary, kombiniert zu einem Gesamtscore. Einfache, nachvollziehbare Methode, kein statistisches Clustering.
- **"Was würdest du anders machen, wenn du mehr Zeit hättest?"** → Ehrliche, reflektierte Antwort wichtiger als eine perfekte, z. B. Clustering-Verfahren testen, fachlich begründete statt rein statistische Segmentgrenzen.

### Kohorten-/Retentionsanalyse
- **"Was sagt dir die Heatmap über das Geschäftsmodell?"** → Hohe Einmalkäufer-Quote – eher ein Bindungs- als ein Neukundengewinnungsproblem.
- **"Wie robust ist diese Aussage?"** → Limitationen kennen: kleinere Kohorten am Ende haben weniger Beobachtungszeit, Dezember 2011 ist unvollständig.

### Power BI / Technisch
- **"Warum Power BI und nicht Excel oder Tableau?"** → Kostenlos, verbreitet im DACH-Raum, gute Skalierbarkeit für 800k+ Zeilen, DAX zum Üben.
- **"Erklär mir deine Datenmodell-Beziehungen."** → 1:*-Beziehung zwischen `customer_rfm` (1) und `online_retail_clean` (*), Kreuzfilterrichtung einfach.
- Sei darauf vorbereitet, **live in Power BI ein Measure zu erklären oder anzupassen**.

### Business-Verständnis / Kritisches Denken
- **"Was ist der Unterschied zwischen Korrelation und Kausalität in deiner Saisonalitäts-Erkenntnis?"** → November-Peak/Dezember-Einbruch beobachtet, Wiederverkäufer-Erklärung ist Hypothese, kein Beweis.
- **"Woher weißt du, dass deine Handlungsempfehlungen wirklich funktionieren würden?"** → Wissen wir nicht sicher – deshalb messbare Ziele, die man nach Umsetzung prüfen müsste (A/B-Test wäre der nächste Schritt).
