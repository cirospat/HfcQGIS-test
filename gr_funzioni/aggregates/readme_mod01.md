# Aggregates

Contiene funzioni che aggregano valori nei livelli e campi. A partire da **QGIS 2.16** il motore di espressioni supporta l'uso di [parametri con nome](http://changelog.qgis.org/en/qgis/version/2.16.0/#named-parameters-expressions).


## [aggregate](funzioni/aggregate.html)<br>Restituisce un valore aggregato calcolato usando elementi da un altro vettore<br>
## [array_agg](funzioni/array_agg.html)<br>Restituisce un array di valori aggregati da un campo o espressione<br>
## [collect](funzioni/collect.html)<br>Restituisce la geometria a parti multiple di geometrie aggregate da una espressione<br>
## [concatenate](funzioni/concatenate.html)<br>	Restituisce tutte le stringhe aggregate tratte da un campo o da una espressione unite con un delimitatore<br>
## [count](funzioni/count.html)<br>Restituisce il conteggio degli elementi corrispondenti<br>
## [count_distinct](funzioni/count_distinct.html)<br>Restituisce il conteggio dei valori differenti<br>
## [count_missing](funzioni/count_missing.html)<br>Restituisce il conteggio dei valori mancanti (nulli)<br>
## [iqr](funzioni/iqr.html)<br>Restituisce lo scarto interquartile calcolato da un campo o espressione<br>
## [majority](funzioni/majority.html)<br>Restituisce la maggioranza aggregata di valori (valore più comunemente presente) da un campo o espressione<br>
## [max_length](funzioni/max_length.html)<br>Restituisce la lunghezza massima delle stringhe di un campo o espressione<br>
## [maximum](funzioni/maximum.html)<br>Restituisce il valore massimo aggregato da un campo o espressione<br>
## [mean](funzioni/mean.html)<br>Restituisce il valore medio aggregato da un campo o espressione<br>
## [median](funzioni/median.html)<br>Restituisce il valore mediano aggregato da un campo o espressione<br>
## [min_length](funzioni/min_length.html)<br>Restituisce la lunghezza minima delle stringhe di un campo o espressione<br>
## [minimum](funzioni/minimum.html)<br>Restituisce il valore minimo aggregato da un campo o espressione.<br>
## [minority](funzioni/minority.html)<br>Restituisce la minoranza aggregata di valori (valore meno comunemente presente) da un campo o espressione<br>
## [q1](funzioni/q1.html)<br>Restituisce il primo quartile calcolato da un campo o espressione<br>
## [q3](funzioni/q3.html)<br>Restituisce il terzo quartile calcolato da un campo o espressione<br>
## [range](funzioni/range.html)<br>Restituisce l'intervallo aggregato di valori (massimo - minimo) da un campo o espressione<br>
## [relation_aggregate](funzioni/relation_aggregate.html)<br>Restituisce un valore aggregato calcolato usando tutte le geometrie figlie corrispondenti da un altro vettore<br>
## [stdev](funzioni/stdev.html)<br>Restituisce il valore di deviazione standard aggregato da un campo o espressione<br>
## [sum](funzioni/sum.html)<br>Restituisce il valore sommato aggregato da un campo o espressione<br>

![](/img/aggregates/gruppo_aggregates1.png)

### Nota bene

Grazie ai [_parametri denominati_](http://changelog.qgis.org/en/qgis/version/2.16.0/#named-parameters-expressions) non è più indispensabile seguire, nella sintassi, l'ordine degli argomenti, ecco un esempio:

La sintassi prevede due possibilità:
1. quella classica, senza l'uso dei paramentri denominati (l'ordine è fondamentale);
    1. count_distinct(_expression, group_by, filter_)
2. con i parametri denominati (l'ordine non è più fondamentale): 
    1. count_distinct(filter:= ,_expression:= ,group_by:=_)
