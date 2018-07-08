# Maps

solo DB (es:PostGIS)

Questo gruppo contiene funzioni espressione per la creazione e la manipolazione di strutture di dati 'a mappa' (noti anche come oggetti dizionario, coppie chiave-valore o array associative). Si possono assegnare valori a determinate chiavi. L'ordine delle coppie chiave valore nell'oggetto mappa non è rilevante come per gli Arrays ([gruppo Arrays](funzioni/../arrays)).

 Funzione  | Descrizione|Plugin
----------:|:-----------|------
[hstore_to_map](funzioni/hstore_to_map.html)|Coverte hstore in map|ArrayPlus
[json_to_map](funzioni/json_to_map.html)|Converte string json in map|ArrayPlus
[map](funzioni/map.html)|Restituisce una mappa con tutte le chiavi ed i valori passati come coppie di parametri
[map_akeys](funzioni/map_akeys.html)|	Restituisce tutte le chiavi di una mappa come un array
[map_avals](funzioni/map_avals.html)|	Restituisce tutti valori di una mappa come un array
[map_concat](funzioni/map_concat.html)|Restituisce una mappa con tutte le entità della mappe fornite
[map_delete](funzioni/map_delete.html)|Restituisce una mappa con il valore della corrispondente chiave passata rimosso
[map_exist](funzioni/map_exist.html)|	Restituisce vero se la chiave passata esiste in mappa
[map_get](funzioni/map_get.html)|Restituisce il valore di una mappa, passando la sua chiave
[map_insert](funzioni/map_insert.html)|Restituisce una mappa con una chiave/valore aggiunto

![](/img/maps/gruppo_maps1.png)