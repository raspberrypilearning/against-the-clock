## Timer starten und anhalten

Starte den Timer mit Knopf A, und halte ihn mit Knopf B an.

+ Dein Timer sollte starten, wenn Knopf A gedrückt wird. Füge einen neuen `wenn Knopf A gedrückt` Block zu deinem Programm hinzu:
    
    ![Screenshot](images/clock-a-pressed.png)

+ Der Timer sollte hochzählen, solange Knopf B **nicht gedrückt wird**. Ziehe dafür zuerst einen `während` Block in deine neue `wenn Knopf A gedrückt` Eingabe.
    
    ![screenshot](images/clock-while.png)

+ Ziehe einen `nicht` Block aus "Logik" in deinen `während` Block:
    
    ![Screenshot](images/clock-not.png)

+ Dann kannst du einen `wenn Knopf B gedrückt` Block hinter den `nicht` Block ziehen.
    
    ![screenshot](images/clock-b-pressed.png)
    
    Jeder Code in dieser `während` Schleife wird wiederholt ausgeführt, **so lange Knopf B nicht gedrückt wird**.

+ Als nächstes wollen wir pro Sekunde 1 zu deiner `Zeit` Variable hinzuzählen (1 Sekunde = 1000 ms). Füge einen `pausiere (ms)` Block hinzu, um deinen Timer eine Sekunde lang warten zu lassen.
    
    ![screenshot](images/clock-pause.png)

+ Um deine `Zeit` Variable hochzuzählen,
    
    ![Screenshot](images/clock-change-time.png)

+ Schließlich musst du die aktualisierte `Zeit` Variable anzeigen. So sollte dein Code aussehen:
    
    ![Screenshot](images/clock-update.png)

+ Klicke auf "Simulator starten", um deinen Code zu testen.
    
    + Drücke die Knöpfe A und B gleichzeitig, um deinen Timer auf 0 zu setzen
    + Drücke Knopf A, um deinen Timer zu starten
    + Halte Knopf B gedrückt, um deinen Timer anzuhalten
    
    ![Screenshot](images/clock-test.png)

## Fordere deine Freunde heraus!

Benutze den Timer, um deine Freunde herauszufordern. Du kannst zum Beispiel sehen, wie lange sie brauchen, um das Alphabet rückwärts aufzusagen, oder 10 Hauptstädte zu benennen.