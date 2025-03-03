# Begriffliches zur Marktanalyse

Die Begriffe Marktpotenzial, Marktvolumen, Marktanteil, Marktsättigung sowie
Marktwachstum werden eingeführt. Neben den Definitionen soll darauf eingegangen
werden, wie die quantitativen Aspekte der Begriffe in Dokumenten und
Präsentationen anschaulich dargestellt werden können.

Als Werkzeuge für die Visualisierung der Begriffe eignet sich insbesondere die
frei verfügbare Plattform
[datawrapper.de](https://app.datawrapper.de/).
Alternativ können zu die Schlüsselbegriffe mit Hilfe von
[Google Charts](https://developers.google.com/chart?hl=de)
oder in einem
[Jupyter Notebook mit
plotly](https://plotly.com/python/ipython-notebook-tutorial/)
visualisiert werden. Dabei handelt es sich allerdings um Alternativen für
ambitionierte Darstellungen.

## Begriffsdefinitionen

Die Eingangs aufgezählten Begriffe werden in der Literatur folgendermassen
definiert: 

Das *Marktvolumen* ist die gegenwärtig von allen Anbietern abgesetzte Menge von
Marktleistungen. In einigen Branchen, wie z. B. der Automobilindustrie, ist das
Marktvolumen durch die amtlich verfügbaren Statistiken über die
Fahrzeuganmeldungen hinreichend gut zu erfassen. In anderen Märkten sind
Marktvolumenermittlungen ggf. nur mit großen Schwierigkeiten durchzuführen.
Vielfach bieten Marktforschungsinstitute Dienstleistungen an, Marktvolumendaten
auf der Grundlage von Hersteller-, Handels- und Kundenbefragungen zu ermitteln
bzw. zu prognostizieren. Je nach Lebensdauer eines Produktes kann die
Entwicklung des Marktvolumens zunächst nur auf Erstkäufen und im späteren
Verlauf auch auf Ersatzbeschaffungen beruhen.[^1] 

Das Marktvolumen kann beispielsweise über eine 
[Symbol map](https://www.datawrapper.de/maps/symbol-map) oder eine 
[Choroplethen-Karte](https://app.datawrapper.de/edit/ZL1PS/basemap)
visualisiert werden.

Das *Marktpotenzial* umfasst die Gesamtheit aller möglichen Absatzmengen eines
Marktes. Werden neue Märkte geschaffen, so besteht i. d. R. ein hohes, nicht
ausgeschöpftes Marktpotenzial, das mit zunehmender Verbreitung der Produkte
ausgefüllt wird. Im Zeitablauf kann das Marktpotenzial auch ausgeweitet werden,
weil sich zunehmend neue Nachfrager für das Produkt als potenzielle Kunden
interessieren. Die Berechnung des Marktpotenzials verlangt neben der Ermittlung
des Marktvolumens die Abschätzung, welche zusätzlichen Mengen bzw. Umsätze mit
potenziellen Nachfragern und bestehenden Käufern realisiert werden können.[^2]

Das Marktpotential kann mit den gleichen Darstellungen visualisiert werden wie
das Marktvolumen.

Der *Marktanteil* eines Unternehmens ergibt sich aus dem Verhältnis von
Absatzvolumen zu Marktvolumen. 

$$
\text{Marktanteil in \%} = \frac{\text{Absatzvolumen (pro
Zeiteinheit)}}{\text{Marktvolumen pro Zeiteinheit}} \times 100 
$$

Der Marktanteil stellt die wichtigste Größe zur Ermittlung der Position eines
Unternehmens im Konkurrenzumfeld innerhalb des relevanten Marktes dar. Vielfach
wird auch der *relative Marktanteil* berechnet. 

$$
\text{Relativer Marktanteil} = \frac{\text{Marktanteil des eigenen
Unternehmens}}{\text{Marktanteil des stärksten Konkurrenen}}
$$

Hierbei wird der Marktanteil des eigenen Unternehmens ins Verhältnis zum
Marktanteil des Hauptwettbewerbers gesetzt. Hat ein Unternehmen einen absoluten
Marktanteil von 20 % und sein Hauptwettbewerber von 40 %, so beträgt der
relative Marktanteil 0,5 (20 % : 40 %). Der eigene Marktanteil beträgt somit nur
die Hälfte des Marktanteiles des Hauptwettbewerbers. Die Ermittlung des
relativen Marktanteiles kann zur Abschätzung von Kostendegressionseffekten im
Vergleich zur Konkurrenz eine wichtige Kenngröße darstellen. Teilweise wird im
Nenner auch der Marktanteil der drei wichtigsten Wettbewerber abgetragen, um
eine weniger stark schwankende Kennzahl ermitteln zu können.[^3]

Anteile können mit 
[figürlichen Grafiken ](https://datavizproject.com/data-type/fraction-of-pictograms/)
dargestellt werden.

Der *Marktausschöpfungsgrad* bzw. *Marktsättigungsgrad* kann durch den Vergleich
des Marktvolumens mit dem Marktpotenzial ermittelt werden: 

$$
\text{Marktausschöpfungsgrad} = \frac{\text{Marktvolumen}}{\text{Marktpotenzial}}
$$

Der Marktausschöpfungsgrad kann zwischen 0 und 1 liegen. Tritt ein Unternehmen
als erstes in einen neuen Markt ein und startet mit den Absatzaktivitäten, so
wäre der Ausschöpfungsgrad in diesem Fall zunächst 0. Im Zeitablauf erhöht sich
i. d. R die Zahl der Anbieter und die Wettbewerbsintensität nimmt zu. Je höher
der Ausschöpfungsgrad ist (nahe 1), desto schwieriger wird es für den einzelnen
Anbieter sein, neue Käuferschichten zu erschließen. Vielmehr können nur noch
Kunden von den bestehenden Konkurrenten abgeworben werden.[^4]

Die (positive) Entwicklung des Marktvolumens im Zeitablauf bezeichnet man als
Marktwachstum (negativ: Marktschrumpfung), das auch wieder mengen- und wertmäßig
definiert und gemessen sein kann. Marktwachstum kann vor allem dadurch
entstehen, dass ein gegebenes Marktpotenzial von den Anbieterinnen zunehmend
ausgeschöpft wird. Neben dem Marktvolumen gilt das Marktwachstum als besonders
wichtiges Kriterium für die Beurteilung der Attraktivität eines Marktes.[^5]

Für zeitliche Entwicklungen drängen sich Line charts auf. Solche können
ebenfalls mit
[Datawrapper](https://app.datawrapper.de/)
erstellt werden.


## Ablauf

Die verschiedenen Begriffe werden in einem Lehrgespräch bzw. -vortrag
vorgestellt. Anschliessend Erarbeiten die SuS eine Anleitung um eine passende
Visualisierung erstellen zu können. Die Anleitungen (Umfang eine Seite) werden
anschliessend der ganzen Klasse zur Verfügung gestellt.


[^1]: Meffert, Heribert, Christoph Burmann, Manfred Kirchgeorg, und Maik
    Eisenbeiß. Marketing: Grundlagen marktorientierter Unternehmensführung
    Konzepte – Instrumente – Praxisbeispiele. Wiesbaden: Springer Fachmedien,
    2024, Seite 61.

[^2]: Meffert, Seite 61.

[^3]: Meffert, Seite 62.

[^4]: Meffert, Seite 62.

[^5]: Eggert, Andreas, Michael Kleinaltenkamp, Alfred Kuß, und Sascha Raithel.
    Marketing-Einführung: Grundlagen - Überblick - Beispiele. Wiesbaden:
    Springer Fachmedien, 2025, Seite 48.