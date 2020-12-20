 # 555_xmas_fablab

## Cosa c'è nel mio kit ?!
![Parts](https://github.com/paolocavagnolo/555_xmas_fablab/blob/main/img/parts.jpg)

| Nome          |Specifiche |  Q.tà |
|:--------------|:---------:|------:|
| Led           |  5mm      |    6  |
| Timer         |    555    |    1  |
| Condensatore  | 4uF       |    1  |
| resistenza 1  | 56 kOhm   |    1  |
| resistenza 2  | 1 kOhm    |    1  |
| resistenza 3  | 12 Ohm    |    1  |
| resistenza 4  | 1 kOhm    |    1  |
| batteria      | 1220 3V   |    1  |
| portabatteria | 3001      |    1  |

## A cosa servono

### 555
E' il timer più famoso di tutti. Leggete [qui](https://it.wikipedia.org/wiki/NE555) per approfondire.

### Condesatore
Il condesatore in questo circuito regola la velocità del lampeggio tra i led, un condesatore con una capacità più grande farà lampeggiare i led più lentamente. Prova!

### Resistenze e alimentazione
Le resistenze regolano la corrente nel circuito. Se usate la pila da 3V per alimentare il circuito vedrete che i led di destra sono più deboli di quelli di sinistra. Questo dipende anche dal valore delle resistenze.
Se collegate l'alimentazione alla 5V (tagliando un cavetto USB e collegando il filo nero al - e il filo rosso al +5V) dovrete cambiare valore delle resistenze per non danneggiare i led e avere una buona luminosità, questi sono dei buoni valori:


| Nome          | 5 Volt    |  Q.tà |
|---------------|:---------:|------:|
| resistenza 1  | 100 kOhm  |    1  |
| resistenza 2  | 1 kOhm    |    1  |
| resistenza 3  | 1 kOhm    |    1  |
| resistenza 4  | 1 kOhm    |    1  |

## Come si monta il kit?
![saldatore](https://github.com/paolocavagnolo/555_xmas_fablab/blob/main/img/saldatore.jpg?s=100)

Il kit è pronto per essere saldato, ti servirà un saldatore e dello stagno. Se non li hai ricevuti per regalo puoi provare a chiederli in prestito a qualcuno oppure venire al Fablab.

Se proprio non c'è nessuno che ti possa aiutare con le prime saldature puoi provare a cercare dei tutorial su youtube, ma qualcuno a fianco è più piacevole oltre che più sicuro.

### Saldare è l'unica possibilità?

Certo che no. Se hai intenzione di studiare il circuito cambiando componenti o valori delle resistenze è più facile usare una breadboard, la trovi in qualunque negozio di elettronica.
![breadboard](https://github.com/paolocavagnolo/555_xmas_fablab/blob/main/img/breadboard.jpg)



### Come è fatto il circuito?

Per il circuito abbiamo preso spunto da qui:
https://www.petervis.com/GCSE_Design_and_Technology_Electronic_Products/simple-555-circuits/555-timer-dual-led-flasher.html

riadattandolo per farlo funzionare con una pila da 3V

![circuito](https://github.com/paolocavagnolo/555_xmas_fablab/blob/main/img/circuito.png)

## Note

### Alimentazione e durata batteria
Questo circuito non nasce per lavorare a 3V, ma a 5V. A 3 è un po' al limite, quindi basta che la tensioni si abbassi un pochettino e il led non si accenderanno più.

Le batterie, man mano che si scaricano, abbassano leggermente la tensione. Nel nostro caso questo significa che con 6 Led rossi dopo circa un giorno di funzionamento continuo i led si spegneranno.

### Differenza di luminosità nei led
E' normale che i led di destra risultino meno luminosi di quelli di sinistra, è una caratteristica del circuito che funziona a 3V. Lavorando a 5V e modificando il valore delle resistenze funzionerà tutto bene!

### Bella la pcb, se volessi modificarla o produrla da me?
Nella cartella kiCad in questo repository trovi tutti i file che abbiamo usato per far produrre la pcb.


