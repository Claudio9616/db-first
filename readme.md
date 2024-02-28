Esercizio di oggi: DB First
nome repo: db-first
Modellizzare la struttura di una tabella per memorizzare tutti i dati riguardanti delle auto usate messe in vendita da un concessionario.
id
tipologia_modello (suv-minivan-berlina)
marca
nome_modello
alimentazione
versione_modello (data)
immatricolazione (data)
km_fatti (numero)
allestimento (sport, gt, comfort, cross)
telaio (numero fisso)
propietari precedenti (quantià, ovviamente più di uno)
tipo di cambio
potenza (numero cavalli)
permuta (booleano)

COLONNE | TIPO | ATTRIBUTO
---|---|---
id|biginit|prymary_key, auto_increment
categoria_modello|varchar|notnull
marca|varchar|notnull
nome_modello|varchar|notnull
versione_modello|year|notnull
immatricolazione|date|notnull
km_fatti|int|notnull
allestimento|varchar|notnull
alimentazione|char (6)|notnull
più_propietari_precedenti|char (1)|null || tinyint|null
tipo_marcia|char(1)|notnull
potenza|mediumint|null
permuta|char(1)|notnull
telaio|char (17)|unique, notnull
