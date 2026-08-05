# Power BI Custom Visuals Â· byDatenWG

Fertige `.pbiviz`-Pakete zum direkten Import in Power BI â€” zum einfachen Teilen.
Quellcode, Doku und Changelogs liegen in den jeweiligen Entwicklungs-Repos;
hier liegt immer die **aktuelle finale Version** jedes Visuals.

## Visuals

| Visual | Version | Stand | Was es kann |
| --- | --- | --- | --- |
| [ChartKitchen byDatenWG](chartkitchen/) | 1.39.0.0 | 05.08.2026 | IBCS-Komplettpaket in einem Visual: 13 Chart-Modi (SÃ¤ulen, Balken, Linien, Waterfall/GuV-BrÃ¼cke, GuV-Statement, IBCS-Tabelle & Matrix, Pareto, KPI-Kacheln u. v. m.), Szenario-Notation AC/PY/PL/FC, Î”-Panels, Small Multiples, In-Chart-Buttons, Kommentare, 4 Sprachen |
| [P&L Statement byDatenWG](pnl-statement/) | 0.5.0.0 | Juli 2026 | IBCS-GuV/P&L-Statement: unbalancierte Konten-Hierarchie (Parent-Child) aus einer Dimensionstabelle, Zwischensummen- und Formelzeilen (EBITDA, Margen), Vorzeichenkonventionen mit Varianz-Invert fÃ¼r Kostenzeilen, Szenarien AC/PY/PL/FC mit Î”-Balken und Î”%-Pins gegen eine wÃ¤hlbare Referenz, persistiertes Auf-/Zuklappen, k/m-Skalierung, 3-zeiliger IBCS-Titelblock |
| [DataKitchen Gantt](gantt/) | 1.9.0.0 | 23.07.2026 | Projektplan-Gantt: 3-Ebenen-Hierarchie (Projekt â†’ Phase â†’ Vorgang), Basisplan Plan vs. Ist mit Î”-Spalte und Verzugs-Markierung, MeilensteinÃ¼bersicht auf der Projektzeile, Statusdatum-Linie, Zeitachsen-Zoom Tage bis Jahre, MS-Project-Export-tauglich |
| [WÃ¤rmestreifen 3D](warming-stripes-3d/) | 1.5.0.0 | 30.07.2026 | 3D-WÃ¤rmestreifen (X = Zeit, Z = Ort, Y = Abweichung): vier Darstellungsformen (SÃ¤ulenfeld, Relief, BÃ¤nder, klassische Streifen-Tafeln), kuratierte Kameraperspektiven, Orbit-Steuerung, Aufbau-Animation, dynamische Referenzperiode, GlÃ¤ttung und Sortierung â€” inkl. Tooltips und Cross-Filtering |

## Installation

1. GewÃ¼nschte `.pbiviz`-Datei aus dem jeweiligen Ordner herunterladen
   (Datei anklicken â†’ â€žDownload raw file").
2. In Power BI Desktop: **Visualisierungen â†’ â€žâ€¦" â†’ Visual aus einer Datei importieren**.
3. Datei auswÃ¤hlen â€” fertig. Ein bestehendes Visual gleicher Herkunft wird
   beim Import automatisch auf die neue Version aktualisiert (gleiche GUID).

> Hinweis: Beim Import erscheint der Ã¼bliche Power-BI-Warnhinweis fÃ¼r
> benutzerdefinierte Visuals. Alle Visuals hier sind quelloffen (MIT),
> telefonieren nicht nach Hause und speichern keine Daten auÃŸerhalb des Berichts.

## Kontakt

Michael Tenner Â· [Daten-WG](https://www.youtube.com/@Daten-WG) Â·
michael.tenner84@gmail.com

Lizenz: [MIT](LICENSE)
