# 📍 Trigono – Das Routen-Spiel

Trigono ist ein kartenbasiertes Geografie-Spiel, bei dem es darum geht, die effizienteste Route zwischen zwei Punkten zu finden. Wer hat die besseren Ortskenntnisse?  Wer beweist das beste räumliche Gefühl für Distanzen?

---

##  Spielregeln

### 1. Spielvorbereitung
* Alle **Ortskarten** werden gemischt und verdeckt als Nachziehstapel bereitgelegt.
* Jeder Spieler erhält **9 Ortskarten** auf die Hand.
* Zwei Karten werden offen vom Stapel gezogen:
    * **Karte 1:** Der Startort 
    * **Karte 2:** Der Zielort 

### 2. Spielablauf
Jeder Spieler versucht nun, die ideale Route zwischen Start und Ziel zu planen:
1. Wähle **3 Karten** aus deiner Hand aus.
2. Lege sie in einer beliebigen Reihenfolge zwischen Start und Ziel.
3. Die Route besteht somit aus: **Start → Ort 1 → Ort 2 → Ort 3 → Ziel**.

### 3. Ermittlung der Route
Die Karten verfügen über **QR-Codes**, in denen die Koordinaten der Orte gespeichert sind. 
* Nutze die Trigono-App, um die 5 Karten nacheinander zu scannen.
* Die App berechnet automatisch die **Gesamtstrecke** in Kilometern.

### 4. Wer gewinnt?
* Der Spieler, dessen gewählte Route die **kürzeste Gesamtdistanz** aufweist, gewinnt die Runde.
* Nach jeder Runde füllen alle Spieler ihre Hand wieder auf **9 Karten** auf.
* Start und Ziel werden für die nächste Runde neu gezogen.

---

##  Siegbedingung
Gespielt wird nach dem **Best-to-5-Prinzip**:
* Notiere die Ergebnisse jeder Runde im **Scoreboard**.
* Wer zuerst **5 Runden** für sich entschieden hat, gewinnt das gesamte Spiel!

---

##  Technische Details
Die App ist eine mobile Web-Anwendung, die Koordinaten via QR-Code einliest und mittels der **Haversine-Formel** die exakte Entfernung auf der Erdkugel berechnet.



## App Link
https://derchopsuey.github.io/Trigono/ <br>
<img src="./gfx/qr-code.png" width="256">
