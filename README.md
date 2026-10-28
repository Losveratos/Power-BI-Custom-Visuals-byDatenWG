# Power BI Custom Visuals · byDatenWG

Fertige `.pbiviz`-Pakete zum direkten Import in Power BI — zum einfachen Teilen.
Quellcode, Doku und Changelogs liegen in den jeweiligen Entwicklungs-Repos;
hier liegt immer die **aktuelle finale Version** jedes Visuals.

## Visuals

| Visual | Version | Stand | Was es kann |
| --- | --- | --- | --- |
| [ChartKitchen byDatenWG](chartkitchen/) | 1.53.0.0 | 24.10.2026 | IBCS-Komplettpaket in einem Visual: 13 Chart-Modi inkl. Scatter/Bubble (Säulen, Balken, Linien, Waterfall/GuV-Brücke, GuV-Statement, IBCS-Tabelle & Matrix, Pareto, KPI-Kacheln u. v. m.), Szenario-Notation AC/PY/PL/FC, Δ-Panels, Small Multiples, In-Chart-Buttons, Kommentare, Dark Mode (Auto/Hell/Dunkel) inkl. dunklem Tooltip, eigener Leer-Zustands-Text, IBCS-Achsenschnitt im Wasserfall per Button, Cross-Interaktion immer als Filter, KPI-Karten mit Trend-Sparklines/-Säulen, Brücken-Ausrichtung wählbar, Auto-Aufklappen der Hierarchie, Scatter-Ausbau 1.48 (SM-Kacheln, Gruppen-Färbung, PY→AC-Pfeile, Trend+R², Log-Skala, Rechteck-Auswahl, Punktformen, Min/Max, Größen-Legende, Play-Modus), 1.49: IBCS-Vorlagen C01–C13 als Presets, Daten-Nachladen bis 30k Zeilen, Lesezeichen-Wiederherstellung, Feld-Intro, echter Hochkontrast, 1.50: Start-Hub (Tour, Template-Galerie mit Vorschauen, Demo, Feld-Intro), 4 Sprachen, 1.52: IBCS-Skalierung als Standard (Δ in Basisskala, markierte Lupe, Breiten 2/3, höchstens 3 Ziffern, gleiche Skala über Karten und Small Multiples, Brückenanker mit Bruchzeichen, Einheit nur im Titel, Bedienmenü ☰) |
| [P&L Statement byDatenWG](pnl-statement/) | 1.6.0.0 | 28.10.2026 | IBCS-GuV/P&L-Statement: unbalancierte Konten-Hierarchie (Parent-Child) aus einer Dimensionstabelle, Zwischensummen- und Formelzeilen (EBITDA, Margen), Vorzeichenkonventionen mit Varianz-Invert für Kostenzeilen, Szenarien AC/PY/PL/FC mit Δ-Balken und Δ%-Pins gegen eine wählbare Referenz, persistiertes Auf-/Zuklappen, k/m-Skalierung, 3-zeiliger IBCS-Titelblock, Treiberbaum mit Tidy-Tree-Layout und Kachel-Zoom, periodengerechte YTD, Selektion/Cross-Filtering + natives Kontextmenü (Drillthrough-Einstieg), ab 1.0: Mega-Table mit IBCS-Templates T01–T04 + 12A als Presets (Varianzspalten, Zellbalken/Pins, integrierter Wasserfall, Wert-Kaskaden, Monat/_YTD-Blöcke, Schwellen-Fußzeile), 4 Sprachen, Smart-Start-Demo, Dark Mode; 1.1: komplette IBCS-Template-Serie inkl. 12G/12H, Tooltips, Σ-treue Rundung, Klammern-Negativ, Hausbegriffe, Filter-Fußzeile, Hervorheben/Wesentlichkeit, Leser-Szenario-Buttons, Skalen-Sync, Tastatur, Virtualisierung; 1.3: Start-Hub (Tour, Template-Galerie T01A–12H mit Vorschauen, ☰-Overlay, ↺ Zum Template zurück); 1.5: IBCS-Skalierung als Standard (eine Skala über alle Blöcke, Ausreißerzone mit Bruchzeichen, Skalenhinweis ×n nur für Δ gegen Kaskade, feste Skala über Reiter), einklappbare Bedienleisten, Margen in pp, Fußnoten mehrspaltig |
| [DataKitchen Gantt](gantt/) | 1.15.0.0 | 23.10.2026 | Projektplan-Gantt: mehrstufige Hierarchie (Projekt + bis zu 5 Klappebenen, 30.000 Zeilen virtualisiert), Basisplan Plan vs. Ist mit Δ-Spalte und Verzugs-Markierung, Meilensteinübersicht auf der Projektzeile, Statusdatum-Linie, Zeitachsen-Zoom Tage bis Jahre (Ansichts-Zustand inkl. Klapp-Status bleibt beim Schließen erhalten), eigener Leer-Zustands-Text, dunkler Tooltip im Dunkel-Theme, MS-Project-Export-tauglich, Gruppenzeile überall klickbar (auch bei skaliertem Visual) |
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
