# Progetto analisi popolazione in america e disucupazione
## Descrizione del Progetto
Questo progetto analizza i dati relativi alla popolazione e alla disoccupazione negli Stati Uniti attraverso l'uso di librerie Python come folium, matplotlib, e pandas. L'obiettivo principale è creare visualizzazioni e fornire informazioni interattive per esplorare:

La distribuzione geografica degli stati americani.
La popolazione per stato basata sui dati del censimento del 2020.
Il tasso di disoccupazione per stato.
Confronti tra stati in termini di popolazione e disoccupazione.
Grafici per visualizzare in modo chiaro i dati estratti.
---
### Funzionalita
  a) Disegno della Mappa dello Stato
L'utente può inserire il nome di uno stato e visualizzare la mappa del suo perimetro geografico.
Viene utilizzato il dataset us_states.json per rappresentare le geometrie con folium.GeoJson.

  b) Mappa della Disoccupazione
Viene creata una mappa coropletica che mostra i tassi di disoccupazione per stato con un gradiente di colori.
Utilizzo del dataset Disoccupazione.json per aggiungere i valori di disoccupazione alla mappa interattiva.

  c) Informazioni sulla Popolazione
Calcolo della popolazione totale di uno stato inserito dall'utente.
Confronto tra due stati per determinare quale ha la popolazione maggiore.
Ordinamento degli stati in base al rank di popolazione.

  d) Grafici
Grafico a Barre:
Confronta le popolazioni di 4 stati scelti dall'utente.
Grafico a Torta:
Visualizza la percentuale della popolazione totale di 4 stati.
Mostra la distribuzione della disoccupazione in 4 stati.
---
###Librerie Utilizzate
a) requests
Per scaricare dataset da URL remoti.
b) json
Per caricare e manipolare file JSON locali.
c) folium
Per generare mappe interattive (confini degli stati, mappa coropletica).
d) matplotlib.pyplot
Per creare grafici a barre e a torta che visualizzano la distribuzione di popolazione e disoccupazione.
e) pandas
Per gestire e manipolare dataset tabulari.
