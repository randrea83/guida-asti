# Guida per Asti

Gioco di guida in 3D per le strade di Asti. Strade, palazzi, piazze, parchi, il Tanaro e la ferrovia vengono dai dati di [OpenStreetMap](https://www.openstreetmap.org/copyright) (© contributori OpenStreetMap, licenza ODbL).

## Come si gioca

Apri `index.html` con Chrome, Edge o Firefox. Al primo avvio il gioco scarica la mappa di Asti dall'API Overpass (circa 10 MB) e la salva nel browser, così le volte successive parte subito.

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

Su telefono e tablet compaiono i pulsanti sullo schermo.

## Tecnica

Un solo file HTML con [three.js](https://threejs.org/) 0.149 da CDN. Nessuna installazione necessaria.
