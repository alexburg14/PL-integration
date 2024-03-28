## Wie funktioniert die Software?
- Wenn man auf *Start Measurement* drückt, ohne dass man eine Wellenlänge spezifiziert, wird genau einmal gemessen, wobei die Dauer der Messung oben angepasst werden kann (default ist 1000ms). 
- Wenn man eine Wellenlänge spezifiziert und dann auf *Start Measurement* drückt, wird zwischen der 1/4- und 3/4-Konfiguration abwechselnd gemessen, und zwar jeweils die Dauer, die angegeben ist, und so oft, wie es in iterations steht (Zum Beispiel: bei duration = 1000ms und iterations = 3 wird in der 1/4- und 3/4-Konfiguration abwechselnd jeweils dreimal gemessen, wobei jedes für 1000ms gemessen wird).
    -  Dabei werden beim Endgraphen alle Messungen von der gleichen Konfigurationen addiert (also beim obigen Beispiel werden die drei Messdaten von der 1/4- bzw. 3/4-Konfiguration addiert und geplottet). Mit dem *Switch* Knopf lässt sich der Plot von der anderen Konfiguration anzeigen (am Graphen steht oben rechts "V" für 1/4, "D" für 3/4)
    -  durch *save graph* lässt sich der momentan angezeigte Plot speichern (wenn man beide speichern will also switchen und dann nochmal den anderen Graphen speichern)

- in dem man auf *save csv* drückt, lassen sich die Daten in eine csv-Datei speichert (Funktioniert für den normalen und den alternierenden Modus, wobei beim alternierden Modus dann das aufsummierte Ergebnis gespeichert wird)
