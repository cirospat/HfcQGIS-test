Aggregates
----------

Contiene funzioni che aggregano valori nei livelli e campi. A partire da **QGIS 2.16** il motore di espressioni supporta l'uso di [parametri con nome](http://changelog.qgis.org/en/qgis/version/2.16.0/#named-parameters-expressions).

+---------------------+---------------------------------------------------------------------------------------------------------------+
| Funzione            | Descrizione                                                                                                   |
+=====================+===============================================================================================================+
| aggregate           | Restituisce un valore aggregato calcolato usando elementi da un altro vettore                                 |
+---------------------+---------------------------------------------------------------------------------------------------------------+
| array_agg           | Restituisce la geometria a parti multiple di geometrie aggregate da una espressione                           |
+---------------------+---------------------------------------------------------------------------------------------------------------+
| collect             | Restituisce la geometria a parti multiple di geometrie aggregate da una espressione                           |
+---------------------+---------------------------------------------------------------------------------------------------------------+
| concatenate         | Restituisce tutte le stringhe aggregate tratte da un campo o da una espressione unite con un delimitatore     |
+---------------------+---------------------------------------------------------------------------------------------------------------+
| count               | Restituisce il conteggio degli elementi corrispondenti                                                        |
+---------------------+---------------------------------------------------------------------------------------------------------------+
| count_distinct      |  Restituisce il conteggio dei valori differenti                                                               |
+---------------------+---------------------------------------------------------------------------------------------------------------+
| count_missing       | Restituisce il conteggio dei valori mancanti (nulli)                                                          |
+---------------------+---------------------------------------------------------------------------------------------------------------+
| iqr                 | Restituisce la maggioranza aggregata di valori (valore più comunemente presente) da un campo o espressione    |
+---------------------+---------------------------------------------------------------------------------------------------------------+
| max_length          | Restituisce la lunghezza massima delle stringhe di un campo o espressione                                     |
+---------------------+---------------------------------------------------------------------------------------------------------------+
| maximum             | Restituisce il valore massimo aggregato da un campo o espressione                                             |
+---------------------+---------------------------------------------------------------------------------------------------------------+
| mean                | Restituisce il valore medio aggregato da un campo o espressione                                               |
+---------------------+---------------------------------------------------------------------------------------------------------------+
| median              |  Restituisce il valore mediano aggregato da un campo o espressione                                            |
+---------------------+---------------------------------------------------------------------------------------------------------------+
| min_length          | Restituisce la lunghezza minima delle stringhe di un campo o espressione                                      |
+---------------------+---------------------------------------------------------------------------------------------------------------+
| minimum             | Restituisce il valore minimo aggregato da un campo o espressione.                                             |
+---------------------+---------------------------------------------------------------------------------------------------------------+
| minority            | Restituisce la minoranza aggregata di valori (valore meno comunemente presente) da un campo o espressione     |
+---------------------+---------------------------------------------------------------------------------------------------------------+
| q1                  | Restituisce il primo quartile calcolato da un campo o espressione                                             |
+---------------------+---------------------------------------------------------------------------------------------------------------+
| q3                  | Restituisce il terzo quartile calcolato da un campo o espressione                                             |
+---------------------+---------------------------------------------------------------------------------------------------------------+
| range               | Restituisce l'intervallo aggregato di valori (massimo - minimo) da un campo o espressione                     |
+---------------------+---------------------------------------------------------------------------------------------------------------+
| relation_aggregate  | Restituisce un valore aggregato calcolato usando tutte le geometrie figlie corrispondenti da un altro vettore |
+---------------------+---------------------------------------------------------------------------------------------------------------+
| stdev               | Restituisce il valore di deviazione standard aggregato da un campo o espressione                              |
+---------------------+---------------------------------------------------------------------------------------------------------------+
| sum                 | Restituisce il valore sommato aggregato da un campo o espressione                                             |
+---------------------+---------------------------------------------------------------------------------------------------------------+




![](/img/aggregates/gruppo_aggregates1.png)

**Nota bene**

Grazie ai [_parametri denominati_](http://changelog.qgis.org/en/qgis/version/2.16.0/#named-parameters-expressions) non è più indispensabile seguire, nella sintassi, l'ordine degli argomenti, ecco un esempio:

La sintassi prevede due possibilità:
1. quella classica, senza l'uso dei paramentri denominati (l'ordine è fondamentale);
    1. count_distinct(_expression, group_by, filter_)
2. con i parametri denominati (l'ordine non è più fondamentale): 
    1. count_distinct(filter:= ,_expression:= ,group_by:=_)
   
.. toctree::
   :maxdepth: 3

   aggregate
   array_agg
   collect
   concatenate
   count
   count_distinct
   count_missing
   iqr
   majority
   max_length
   maximum
   mean
   median
   min_length
   minimum
   minority
   q1
   q3
   range
   relation_aggregate
   stdev
   sum
