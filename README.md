# Orbital control

Ogni giocatore controlla un satellite orbitante che proietta un raggio
di controllo mentale sulla popolazione terrestre.

La popolazione è definita da un profilo psicologico:
* superego (idealismo e conversione)
* ego (la appartenenza)
* id (pulsioni elementari e distruttività)

Ogni valore inizialmente è a 3.

La popolazione iniziale è di 100 unità,

Ogni satellite può eseguire queste azioni:
* sviluppo interno: metto in orbita un satellite;
* controllo: prendo come bersaglio uno dei profili psi e controllo di unità
  di popolazione per ogni satellite per il valore del profilo psi - 1 per
  ogni volta che questo profilo è stato bersaglio; ogni unità di popolazione
  già controllata da un altro giocatore costa il suo valore di ego;
* mutazione del profilo psi: aumento di uno un profilo e riduco di 1 un altro
  profilo;
* mutazione della popolazione;
* caos: si eliminano (satelliti * profilo psi id) unità di popolazione random.

La popolazione può mutare: (TODO)
* libido (parte da 3)
* prosperità (parte da 3)

Dopo le azioni dei satelliti ci sono le azioni delle popolazioni controllate
* donare: produco (unità * produttività / 10) satelliti;
* prosperare: aumenta la prosperità della popolazione controllata
* apostolato: (unità * profilo psi superego)
* monumenti: per produrre i punti vittoria

Dopo ogni turno la popolazione aumenta (?)

Dopo ogni turno se c'è troppo dislivello tra la prosperità di una
popolazione controllata rispetto alla prosperità media -> rivoluzione (?)
