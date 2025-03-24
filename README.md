# HashTable

Šajā uzdevumā jūsu mērķis ir izveidot vienkāršu tālruņu grāmatas pārvaldnieku izmantojot Hash Table datu struktūru. Programmai vajadzētu spēt apstrādāt šādus lietotāja vaicājumus:

## Pievienot numuru vārdu (add)

Tas nozīmē, ka lietotājs pievieno personu ar vārdu vārds un tālruņa numuru numuru tālruņu grāmatā. Ja šāds numurs jau pastāv, tad jūsu pārvaldniekam ir jāaizstāj atbilstošais vārds.

## Dzēst numuru (delete)

Tas nozīmē, ka pārvaldniekam jāizdzēš persona no tālruņu grāmatas. Ja tādas personas nav, tad tam vienkārši jāignorē vaicājums.

## Paradīt numuru (find)

Tas nozīmē, ka lietotājs meklē personu ar tālruņa numuru numurs. Pārvaldniekam jāatbild ar atbilstošo vārdu, vai ar tekstu “nav atrasts" (bez pēdiņām), ja grāmatā nav tādas personas.

## Ievades formāts

Pirmajā rindā ir viens vesels skaitlis N — vaicājumu skaits. Tam seko N rindas, katra no tām satur vienu vaicājumu iepriekš aprakstītajā formātā.

 

## Piemērs

Input:\
12\
add 911 Police\
add 76213 Mom\
add 17239 Bob\
find 76213\
find 910\
find 911\
delete 910\
delete 911\
find 911\
find 76213\
add 76213 Daddy\
find 76213

Output:\
Mom\
not found\
Police\
not found\
Mom\
Daddy


## hash() 
- https://www.programiz.com/python-programming/methods/built-in/hash						
- https://www.toppr.com/guides/python-guide/references/methods-and-functions/methods/built-in/hash/python-hash/						
- https://www.geeksforgeeks.org/implementation-of-hash-table-in-python-using-separate-chaining/