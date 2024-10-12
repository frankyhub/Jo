<a name="oben"></a>

<div align="center">

|[:skull:ISSUE](https://github.com/frankyhub/Jo/issues?q=is%3Aissue)|[:speech_balloon: Forum /Discussion](https://github.com/frankyhub/Jo/discussions)|[:grey_question:WiKi](https://github.com/frankyhub/Jo/wiki)||
|--|--|--|--|
| | | | |
|![Static Badge](https://img.shields.io/badge/RepoNr.:-%2042-blue)|<a href="https://github.com/frankyhub/Jo/issues">![GitHub issues](https://img.shields.io/github/issues/frankyhub/Jo)![GitHub closed issues](https://img.shields.io/github/issues-closed/frankyhub/Jo)|<a href="https://github.com/frankyhub/Jo/discussions">![GitHub Discussions](https://img.shields.io/github/discussions/frankyhub/Jo)|<a href="https://github.com/frankyhub/Jo/releases">![GitHub release (with filter)](https://img.shields.io/github/v/release/frankyhub/Jo)|
|![GitHub Created At](https://img.shields.io/github/created-at/frankyhub/Jo)| <a href="https://github.com/frankyhub/Jo/pulse" alt="Activity"><img src="https://img.shields.io/github/commit-activity/m/badges/shields" />| <a href="https://github.com/frankyhub/Jo/graphs/traffic"><img alt="ViewCount" src="https://views.whatilearened.today/views/github/frankyhub/github-clone-count-badge.svg">  |<a href="https://github.com/frankyhub?tab=stars"> ![GitHub User's stars](https://img.shields.io/github/stars/frankyhub)|
</div>



# Jo
Little Bot mit 4 Servos

![Bild](pic/jo8.png)

### Story
Diese Bauanleitung beschreibt einen tanzenden Bot. Jedes Bein hat zwei Gelenke die von Servo-Motoren bewegt werden. Als Steuerung dient ein Arduino NANO, gespeist von einer 9V-Batterie. Das Programm kann um eine Hindernis-Erkennung erweitert werden, da beim Bot auch ein Ultraschall-Sensor verbaut ist.
Die Bot-Elemente werden aus einer 2mm ABS-Platte und einer 2mm Sperrholzplatte (Füße) gelasert. Die Montage erfordert etwas Geschick.




### Bauanleitung

### Hardware


| Anzahl | Bezeichnung | 
| -------- | -------- | 
| 1  | ABS Platte DINA4 2mm   |
| 4  |  Platinenhalter (3D-Druck)  |
| 4  | Abstandshalter M3*25 Kunststoff   |
|  1 | Ardunio NANO   |
|  4 | SG90 Servo   |
|  1 |  HCSR04 Ultraschallsensor  |
|  1 | LM 2596S Spannungsregler 5V   |
|  1 |  9V Batterie mit Gehäuse  |
| ---  | ---   |




	
#### Schrauben

| Anzahl | Bezeichnung | 
| -------- | -------- | 
| 10  | M1.5x5 |
| 6  |  M1.4x8  |
| 12   | M2x8   |
| 12  |  M2x8  |
| 18  |  M3x5  |
| 8  |  M3x8 Senkkopf  |
| ---  | ---   |


#### Muttern

| Anzahl | Bezeichnung | 
| -------- | -------- | 
| 6  | M1.4  |
| 12  |  M2  |
| 8  |  M3 selbstsichernd  |
|  --- |  ---  |


### Schritt 1: 

- Die ABS-Platten lasern, Verwende die lbrn Vorlagen


![Bild](pic/jo1.png)

### Schritt 2: 

- Die Schenkel der Fersen und der Füße biegen und auf angegebenen Durchmesser aufbohren.

- Füße: Beide Schenkel gleich lang, Innenmaß 37 mm

![Bild](pic/jo2.png)

- Bohrungen: 

![Bild](pic/jo2a.png)

- Ferse biegen, beide Schenkel gleich lang:

![Bild](pic/jo2b.png)

- Bohrungen: Für die 1,5mm Bohrungen des Servos, den Servo als Bohrschablone verwenden.

![Bild](pic/jo2c.png)

### Schritt 3: Die Platinenhalter drucken

### Schritt 4: Die Schrittmotoren auf die Grundplatte und an die Fersen montieren und verschrauben (alternativ kleben). 
Ferse und Schenkel verschrauben. Die Teile müssen beweglich bleiben, so dass der Schrittmotor den Schenkel bewegen kann.

![Bild](pic/jo3.png)

![Bild](pic/jo4.png)


### Schritt 5: Den Ultraschallsensor an die Deckplatte montieren (alternativ kleben).

### Schritt 6: Den Arduino NANO auf die Deckplatte montieren.

![Bild](pic/jo5.png)


### Schritt 7: Den Batteriehalter an die Grundplatte montieren (alternativ kleben).

![Bild](pic/jo6.png)


### Schritt 8: Die Schrittmotoren, den Ultraschallsensor und den Batteriehalter nach Schaltplan verdrahten.

![Bild](pic/jo7.png)

### Schritt 9: Das Programm in den Arduino NANO laden

### Schritt 10: Funktionstest


---

<div style="position:absolute; left:2cm; ">   
<ol class="breadcrumb" style="border-top: 2px solid black;border-bottom:2px solid black; height: 45px; width: 900px;"> <p align="center"><a href="#oben">nach oben</a></p></ol>
</div>  

---






