# Power BI Custom Visuals · byDatenWG

Fertige `.pbiviz`-Pakete zum direkten Import in Power BI — zum einfachen Teilen.
Quellcode, Doku und Changelogs liegen in den jeweiligen Entwicklungs-Repos;
hier liegt immer die **aktuelle finale Version** jedes Visuals.

## Visuals

| Visual | Version | Stand | Was es kann |
| --- | --- | --- | --- |
| [ChartKitchen byDatenWG](chartkitchen/) | 1.48.0.0 | 16.10.2026 | IBCS-Komplettpaket in einem Visual: 13 Chart-Modi inkl. Scatter/Bubble (Säulen, Balken, Linien, Waterfall/GuV-Brücke, GuV-Statement, IBCS-Tabelle & Matrix, Pareto, KPI-Kacheln u. v. m.), Szenario-Notation AC/PY/PL/FC, Δ-Panels, Small Multiples, In-Chart-Buttons, Kommentare, Dark Mode (Auto/Hell/Dunkel) inkl. dunklem Tooltip, eigener Leer-Zustands-Text, IBCS-Achsenschnitt im Wasserfall per Button, Cross-Interaktion immer als Filter, KPI-Karten mit Trend-Sparklines/-Säulen, Brücken-Ausrichtung wählbar, Auto-Aufklappen der Hierarchie, Scatter-Ausbau 1.48 (SM-Kacheln, Gruppen-Färbung, PY→AC-Pfeile, Trend+R², Log-Skala, Rechteck-Auswahl, Punktformen, Min/Max, Größen-Legende, Play-Modus), 4 Sprachen |
| [P&L Statement byDatenWG](pnl-statement/) | 0.17.0.0 | 26.08.2026 | IBCS-GuV/P&L-Statement: unbalancierte Konten-Hierarchie (Parent-Child) aus einer Dimensionstabelle, Zwischensummen- und Formelzeilen (EBITDA, Margen), Vorzeichenkonventionen mit Varianz-Invert für Kostenzeilen, Szenarien AC/PY/PL/FC mit Δ-Balken und Δ%-Pins gegen eine wählbare Referenz, persistiertes Auf-/Zuklappen, k/m-Skalierung, 3-zeiliger IBCS-Titelblock, Treiberbaum mit Tidy-Tree-Layout und Kachel-Zoom, periodengerechte YTD, Selektion/Cross-Filtering + natives Kontextmenü (Drillthrough-Einstieg) |
| [DataKitchen Gantt](gantt/) | 1.14.0.0 | 16.10.2026 | Projektplan-Gantt: mehrstufige Hierarchie (Projekt + bis zu 5 Klappebenen, 30.000 Zeilen virtualisiert), Basisplan Plan vs. Ist mit Δ-Spalte und Verzugs-Markierung, Meilensteinübersicht auf der Projektzeile, Statusdatum-Linie, Zeitachsen-Zoom Tage bis Jahre (Ansichts-Zustand inkl. Klapp-Status bleibt beim Schließen erhalten), eigener Leer-Zustands-Text, dunkler Tooltip im Dunkel-Theme, MS-Project-Export-tauglich |
| [Wärmestreifen 3D](warming-stripes-3d/) | 1.5.0.0 | 30.07.2026 | 3D-Wärmestreifen (X = Zeit, Z = Ort, Y = Abweichung): vier Darstellungsformen (Säulenfeld, Relief, Bänder, klassische Streifen-Tafeln), kuratierte Kameraperspektiven, Orbit-Steuerung, Aufbau-Animation, dynamische Referenzperiode, Glättung und Sortierung — inkl. Tooltips und Cross-Filtering |

## Installation

1. Gewünschte `.pbiviz`-Datei aus dem jeweiligen Ordner herunterladen
   (Datei anklicken → „Download raw file").
2. In Power BI Desktop: **Visualisierungen → „…" → Visual aus einer Datei importieren**.
3. Datei auswählen — fertig. Ein bestehendes Visual gleicher Herkunft wird
   beim Import automatisch auf die neue Version aktualisiert (gleiche GUID).

> Hinweis: Beim Import erscheint der übliche Power-BI-Warnhinweis für
> benutzerdefinierte Visuals. Alle Visuals hier sind quelloffen (MIT),
> telefonieren nicht nach Hause und speichern keine Daten außerhalb des Berichts.

## Kontakt

Michael Tenner · [Daten-WG](https://www.youtube.com/@Daten-WG) ·
michael.tenner84@gmail.com

Lizenz: [MIT](LICENSE)
