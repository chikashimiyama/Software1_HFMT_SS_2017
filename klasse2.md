#Klasse2 - Techniken für Erkennung

## Objekte

- snapshot~
- average~ 
- zerox~ 
- peekamp~ 
- &&
- ||
- sigmund~

### Weitere Logical Operators

- !
- ==
- !=
- >
- >=
- <
- <=


## patch 1: Anti-Chatter

### Trade-off von Average-Interval
![](res/k2/img/compare.png)

### Anti-Chatter
 ![](res/k2/img/p1.png)

## patch 2: Zählung der Töne
 ![](res/k2/img/p2.png)
 

## patch 3: Delta
![](res/k2/img/p3.png)

## patch 4: Anwendung eines Delta-Werts

### Transient-Erkennung
 ![](res/k2/img/p4.png)

## patch 5: Dauer eines Tons

### thresh~
![](res/k2/img/env_thresh.png)

### thresh~ + edge~
![](res/k2/img/p5_1.png)

### thresh~ + edge~ + timer
![](res/k2/img/p5_2.png)

## patch 6: Aufnahme einer Hüllkurve
![](res/k2/img/p6.png)

## patch 7: Rhythmuserkennung
### LCD
![](res/k2/img/p7_1.png) 

### Visualisierung des Analyzeergebnises
![](res/k2/img/p7_2.png) 

## patch 8: Datensammlung mit coll

### coll
![](res/k2/img/p8_1.png)

### Kombination mit der Rhythmuserkennung
![](res/k2/img/p8_2.png)


## patch 9: Imitation eines Rhythms (Drum Trigger)
### Samlung der Deltazeiten
![](res/k2/img/p9_1.png)

### Drum triggering
![](res/k2/img/p9_2.png)


## HA
programmieren Sie ein reaktionsystem, das obenstehende Erkennungstechniken sinvoll verwendet.
