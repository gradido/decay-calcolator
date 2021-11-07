# decay-calculator
## Berechnung der Vergänglichkeit von Gradido - GDD
## Calculation of the decay of Gradido - GDD

Die Berechung der Vergänglichkeit von Gradido GDD kann mit diesem Rechner dargestellt werden.
The calculation of the transience of Gradido GDD can be displayed with this calculator.



### Formel - Formula

> x - x * 0.99999997802044727^Sekunden  
(Diese Formel ist erstellt von https://github.com/einhornimmond )



### Bibliotheken - Libraries

- jQuery
- Bootstrap
- Momentjs
  
  
  ![Bildschirmfoto von 2021-11-07 16-57-37](https://user-images.githubusercontent.com/1324583/140652367-02c76a66-76c1-4f48-9db7-5da20d057ebd.png)




### Rechenbeispiel

```
eine beispielrechnung / formel mit 1000 GDD

1 jahr (365 Tage )  === 31536000 Sekunden

1000  - ( 1000 * 0,99999997802044727)  = 0,00002198

also 0,00002198 GDD Decay bei Sekunde 1 bei 1000 GDD

sekunde 2 

wäre 
(1000  - 0,00002198) - (( 1000 - 0,00002198 ) * 0,99999997802044727)  = 0,00002198

oder anders gerechnet 

999,99997802 - (999,99997802 * 0,99999997802044727) = 0,00002198

Sekunde 3 

.... 

```





### TODO 

- Es sollte ein min="" Datum im zweiten Datum vom ersten Datum automatisch ersetzt werden. 
- Startdatum mit JETZT Datum ausfüllen 
- Die Rechnung besser dartsellen und erklären 
