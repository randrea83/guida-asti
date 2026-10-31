# Guida per Asti

Gioco di guida in 3D per le strade di Asti. Strade, palazzi, piazze, parchi, il Tanaro e la ferrovia vengono dai dati di [OpenStreetMap](https://www.openstreetmap.org/copyright) (© contributori OpenStreetMap, licenza ODbL).

## Come si gioca

Apri `index.html` con Chrome, Edge o Firefox. Si parte da Piazza Alfieri (o da Corso Dante se la piazza non è nella mappa). Al primo avvio il gioco scarica la mappa di Asti dall'API Overpass (circa 10 MB) e la salva nel browser, così le volte successive parte subito.

Se il download non parte, la pagina mostra un link: salvi il risultato come `asti.json` e lo trascini nel gioco. Va bene anche un file `.osm` esportato da openstreetmap.org.

## Comandi

| Tasto | Azione |
|---|---|
| W A S D / frecce | guida |
| Spazio | freno a mano |
| C | cambia visuale (dietro, alto, posto di guida, mappa) |
| F | vai a una via |
| R | rimetti l'auto in strada |
| M | mostra/nascondi la minimappa |
| O | ombre on/off |
| K | clacson |
| N | audio on/off |
| G | passa attraverso i muri (per uscire se resti chiuso) |

Su telefono e tablet compaiono pulsanti grandi sullo schermo: sterzo a sinistra, freno/retromarcia e acceleratore a destra, più freno a mano e clacson. Funziona sia in verticale sia in orizzontale (consigliato).

## Sonoro

Motore che sale di giri e cambia marcia, stridio delle gomme in curva e col freno a mano, botto negli urti e clacson. È tutto generato dal browser (Web Audio), senza file audio. Parte al primo tocco o tasto premuto e si spegne col pulsante "Audio".

## Tecnica

Un solo file HTML con [three.js](https://threejs.org/) 0.149 da CDN. Nessuna installazione necessaria.
