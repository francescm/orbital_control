# Orbital control

Ogni giocatore controlla un satellite orbitante che proietta un raggio
di controllo mentale sulla popolazione terrestre.

La popolazione è definita da un profilo psicologico:
* super-ego (idealismo e conversione)
* ego (la appartenenza)
* id (pulsioni elementari e distruttività)

Ogni valore inizialmente è a 3. La somma deve fare sempre nove.

La popolazione iniziale è di 100 unità,

Ogni satellite può eseguire queste azioni:
* sviluppo interno: metto in orbita un satellite;
* controllo: scelgo uno dei profili psicologici e controllo una unità
  di popolazione per ogni satellite per il valore del profilo psi. C'è una
  penalità per ogni volta che questo profilo è già stato bersaglio;
  ogni unità di popolazione già controllata da un altro giocatore costa
  il suo valore di ego;
* mutazione del profilo psi: aumento di uno un profilo e riduco di 1 un altro
  profilo;
* mutazione della popolazione;
* caos: si eliminano (satelliti * profilo psi id) unità di popolazione random.

La popolazione può mutare: (TODO)
* libido (?)
* produttività (?)
* intelligenza (se normale ok, altrimenti rende la popolazione imprevedibile
  o perché troppo stupida o perché troppo poco stupida)

Dopo le azioni dei satelliti ci sono le azioni delle popolazioni controllate
* donare: produco (unità * produttività / 10) satelliti;
* prosperare: aumenta la prosperità della popolazione controllata
* apostolato: si convertono (unità * profilo psi superego) popolazione
* monumenti: per produrre i punti vittoria

Dopo ogni turno la popolazione aumenta (?)

Dopo ogni turno se c'è troppo dislivello tra la prosperità di una
popolazione controllata rispetto alla prosperità media -> rivoluzione (?)

Fine del gioco: quando o tutta la popolazione è asservita (o aumenta o
decresce oltre un certo limite). Ci saranno punti per ogni satellite, per
ogni unità di popolazione asservita e per ogni monumento.
