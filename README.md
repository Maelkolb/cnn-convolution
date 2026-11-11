# Convolution und CNN zum Ausprobieren

Interaktive Folien zur Sitzung „Deep Learning“ (Einführung in KI für DH, WiSe 2026/27), zwei Ansichten in einer Datei.

**Convolution** (`index.html`): Ein 3 × 3-Filter wandert über ein Bild mit 6 × 6 Feldern; rechts steht die Rechnung für das aktuelle Fenster.

- **Bild:** zwischen **L** und **T** umschalten (auch Tasten `L` und `T`); einzelne Felder lassen sich anklicken.
- **Filter:** senkrecht oder waagrecht; einzelne Gewichte lassen sich anklicken.
- **Fenster bewegen:** Maus über die Feature Map, Pfeiltasten oder „Wandern lassen“ (Leertaste).

**Ganzes CNN** (`index.html?ansicht=cnn`): dasselbe Bild läuft durch Convolution, Max Pooling und einen Fully Connected Layer bis zur Antwort L oder T.

- Felder im Bild anklicken: alle Zahlen und die Antwort rechnen sich neu.
- Maus über eine Zahl oder ein Neuron: unten steht, wie sie zustande kommt.
- Die Gewichte des Fully Connected Layers sind von Hand gesetzt: vier Neuronen für senkrechte und waagrechte Striche je Bildhälfte (sie feuern ab 8), zwei Neuronen für L und T (sie feuern ab 1,5).

Zwischen den Ansichten wechseln die Tasten `1` und `2`. Eine einzige Datei, keine Abhängigkeiten außer der Schrift Inter von Google Fonts.
