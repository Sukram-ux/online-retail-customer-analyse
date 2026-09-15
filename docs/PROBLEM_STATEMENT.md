# Problem Statement: Kundenanalyse Online-Retail

## Kontext
Der fiktive Auftraggeber ist ein britischer Online-Händler für Geschenkartikel und
Haushaltswaren (Basis: Online-Retail-II-Datensatz, 2009–2011). Das Unternehmen möchte
das Kaufverhalten seiner Kunden besser verstehen, um Marketingbudget gezielter
einzusetzen und Kunden langfristig zu binden.

## Leitfragen (Guiding Questions)
1. Welche Kundensegmente erwirtschaften den größten Umsatzanteil?
2. Welche Kundensegmente erwirtschaften den kleinsten Umsatzanteil, und wodurch
   unterscheiden sie sich von den umsatzstarken Segmenten?
3. Wie hoch ist der Anteil wiederkehrender Kunden über die Zeit (Retention-Rate je Kohorte)?
4. Wie entwickeln sich Umsatz, Bestellanzahl und Kundenzahl monatlich im Zeitraum 2009–2011?

## Hypothesen (vor der Analyse, noch ungeprüft)
- Ein kleiner Anteil der Kunden (z. B. die Top 20 %) erzeugt einen überproportional
  großen Anteil des Umsatzes (Pareto-Prinzip).
- Die Retention-Rate sinkt mit zunehmendem "Kunden-Alter": Je länger ein Kunde dabei
  ist, desto seltener kauft er im Verhältnis erneut.
- Der Umsatz ist saisonal geprägt, mit einem deutlichen Anstieg im vierten Quartal
  (Weihnachtsgeschäft).

## Scope – was gehört dazu
- Deskriptive Analyse (Umsatz, Bestellungen, Kunden über Zeit, Land, Produkt)
- RFM-Segmentierung der Kunden (Recency, Frequency, Monetary)
- Kohorten-/Retention-Analyse
- Interaktives Dashboard (Power BI oder Tableau)
- Handlungsempfehlungen auf Basis der Ergebnisse

## Out of Scope – was bewusst NICHT gemacht wird
- Keine Vorhersagemodelle / Machine Learning (z. B. Churn-Prediction)
- Kein Live-/Produktivsystem, keine Anbindung an echte Unternehmensdaten
- Keine Preisoptimierung oder Produktempfehlungssysteme

## Zielgruppe
-  Marketing-Team
-  Management

## Erfolgskriterien
- Mindestens 3–4 klar unterscheidbare Kundensegmente mit beschreibbaren Eigenschaften
- Kohortenanalyse zeigt einen nachvollziehbaren Retention-Trend über mind. 6 Monate
- Dashboard mit mind. 3 interaktiven Kennzahlen (Umsatz, Kundenzahl, Retention),
  filterbar nach Zeitraum/Land
- Mindestens 3 konkrete, datenbasierte Handlungsempfehlungen
- Vollständig dokumentiertes, reproduzierbares GitHub-Repository