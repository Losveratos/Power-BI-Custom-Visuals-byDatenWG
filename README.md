# Power BI Custom Visuals · byDatenWG

Fertige `.pbiviz`-Pakete zum direkten Import in Power BI — zum einfachen Teilen.
Quellcode, Doku und Changelogs liegen in den jeweiligen Entwicklungs-Repos;
hier liegt immer die **aktuelle finale Version** jedes Visuals.

## Visuals

| Visual | Version | Stand | Was es kann |
| --- | --- | --- | --- |
| [ChartKitchen byDatenWG](chartkitchen/) | 1.43.0.0 | 16.09.2026 | IBCS-Komplettpaket in einem Visual: 13 Chart-Modi (Säulen, Balken, Linien, Waterfall/GuV-Brücke, GuV-Statement, IBCS-Tabelle & Matrix, Pareto, KPI-Kacheln u. v. m.), Szenario-Notation AC/PY/PL/FC, Δ-Panels, Small Multiples, In-Chart-Buttons, Kommentare, Dark Mode (Auto/Hell/Dunkel), 4 Sprachen |
| [P&L Statement byDatenWG](pnl-statement/) | 0.5.0.0 | Juli 2026 | IBCS-GuV/P&L-Statement: unbalancierte Konten-Hierarchie (Parent-Child) aus einer Dimensionstabelle, Zwischensummen- und Formelzeilen (EBITDA, Margen), Vorzeichenkonventionen mit Varianz-Invert für Kostenzeilen, Szenarien AC/PY/PL/FC mit Δ-Balken und Δ%-Pins gegen eine wählbare Referenz, persistiertes Auf-/Zuklappen, k/m-Skalierung, 3-zeiliger IBCS-Titelblock |
| [DataKitchen Gantt](gantt/) | 2.1.0.0 | 28.10.2026 | Projektplan-Gantt nach MS-Project-Vorbild: Gliederung direkt aus dem PSP-Code (oder bis zu 5 Ebenen-Feldern), Sammelvorgänge als Gruppen, Vorgänger im MS-Project-Format mit EA/AA/EE/AE und Zeitabstand, kritischer Pfad und Puffer (aus dem Export oder berechnet), Stichtage, Basisplan mit Δ, Fortschrittslinie, Arbeitstage mit Feiertagen, überfällige Vorgänge zum Statusdatum; Ansichten Alle/Hauptmeilensteine/kritischer Pfad/überfällig, Suche, Gliederung bis Ebene n, frei schaltbare Spalten, Tooltip und Beschriftungen, Balkenfarbe nach Status/Feld; Einrichtungshilfe für Ersteller (Felder-Checkliste, Datenprüfung, Vorlagen) und ein Formatbereich, der nur zeigt, was die Daten hergeben; bis 30.000 Zeilen flüssig |
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
