# tag-search

Per nuovo progetto ho dovuto realizzare una select con riempimento automatico e possibilità di selezionare più scelte, in pratica se inserisci il nome di una tecnologia (almeno due caratteri) parte una ricerca all'interno di un json, la ricerca è implementata con una piccola libreria http://fusejs.io in sostanza implementa un'algoritmo di ricerca fuzzy leggero e veloce senza dipendenze.

Il json proviene da stackoverflow che mette a disposizione i suoi dati grazie alle api, quindi il json contiene i nomi di linguaggi e servizi vari con tanto di sinonimi, per questo se cerchi js uscirà fuori JavaScipt, infatti js è un sinonimo di JavaScript, una volta scaricati i dati vengono salvati in localstorage.

Se clicchi sul nome del linguaggio/tecnologia lo vedrai pinnare sotto alla search bar e se clicchi sul pulsante submit della search bar ritornerà un oggetto contenente i nomi delle tecnologie cercate.

Questo repo è solo un contenitore per il file json contenente i dati e la pen è solo la demo di una funzionalità per un progetto personale, quindi non troverai una libreria da scaricare ma spero di averti dato una mano nel caso anche tu abbia bisogno di implementare una funzionalità del genere, nel caso ti invito a visionare la demo su codepen: https://codepen.io/filippoq/pen/ybbXMP
