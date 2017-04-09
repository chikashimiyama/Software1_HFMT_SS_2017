#Klasse1 - Reaktion


## patch1: Konzept
 ![](res/k1/img/p1.png)
 
## patch2: Beispiel
 ![](res/k1/img/p2.png)

## patch3: Amplitude vs RMS
 ![](res/k1/img/p3.png)

## patch 4: Frequenzerkennung 
[Sigmund von Miller S Puckette](http://vboehm.net/2015/06/a-64-bit-version-of-sigmund/)

### Miller Puckette Externals
![](res/k1/img/p4.png)


## patch 5: Geräuschhaftigkeitserkennung
![](res/k1/img/p5.png) 



## patch 6: Mehrere Konditionen 
 z.B. ein System, das auf ein lauten Geräusch reagiert.
 
### logical AND 
![](res/k1/img/p6-1.png)

### Umsetzung mit zerox~ und average~

![](res/k1/img/p6-2.png)

### logical OR
![](res/k1/img/p6-3.png)


## patch 7: Preprocessing

Die Entfernung des unnötiges Signals vor der Analyze.

### Gating
wenn die Amplitude nicht hoch ist, mach das Tor zu.
![](res/k1/img/p7-1.png)
 
### Filter
![](res/k1/img/p7-2.png)
zu Tiefe Frequenz und zu höhe Frequenz brauchen wir nicht für die Analyze.


## HA
programmieren Sie ein reaktionsystem, die mind. zwei Aspekte des eingegebenen Klangs analyziert und darauf reagiert. 
