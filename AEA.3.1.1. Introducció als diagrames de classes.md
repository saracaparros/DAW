###### Sara Caparrós amb Pau Cànovas (DAW1 - Curs 2018/2019)

# AEA.3.1.1. Introducció als diagrames de classes

## 1. Botiga de venta on-line
1. Una botiga de venta on-line, desitja un programa on:
-	Pugui crear, editar o eliminar clients de la seva base de dades. Cada client ha de tenir un nom, una adreça d’enviament, una adreça de  cobrament i un e-mail. A més, la botiga té uns clients preferencials, que a més de totes les dades dels clients, també tenen emmagatzemat un descompte que se’ls hi haurà d’aplicar a cada comanda realitzada. 
-	Cada client posseeix una targeta que els hi permet validar-se i a la que s’indica qui és el seu propietari, quin és el seu número i fins quan té validesa. 
-	Cada client pot tenir un o varis carrets de la compra, que indiquen el preu total de compra. Cada carret es pot comprar, cancel•lar, crear o eliminar i es paguen amb la targeta. 
-	Els carrets estan composats per ítems, que tenen codi, quantitat demanada i preu. 
-	Aquests ítems es poden afegir o eliminar. 

@startuml
@enduml



## 2. Empresa de lloguer de cotxes
2.Una empresa dedicada al lloguer de cotxes, desitja un programari tenint en compte que:
-	Un determinat client pot tenir en un moment donat diverses reserves fetes. 
-	De cada client es desitja emmagatzemar el seu DNI, nom, adreça i telèfon. 
-	A més, dos clients es diferencien per un codi únic. 
-	Una reserva la realitza un únic client però pot involucrar diversos cotxes. 
-	És important registrar la data d’inici i final de la reserva, el preu del lloguer de cadascun dels cotxes, els litres de benzina en el dipòsit en el moment de realitzar la reserva, el preu total de la reserva i un indicador de si el cotxe o cotxes han sigut entregats. 
-	Tots els cotxes tenen sempre assignat un determinat garatge que no pot canviar. De cada cotxe es requereix la matrícula, el color i la marca. 
-	Cada reserva es realitza en una agència determinada.
 
@startuml
@enduml

## 3. Cadena d'agències de viatges
3.Una cadena d'agències de viatges desitja disposar d’un programari que contempli informació relativa a l'hostalatge i vols dels turistes que la contracten. Les dades a tenir en compte són:
-	La cadena d'agències està composta per un conjunt de sucursals. Cada sucursal ve definida pel codi de sucursal, adreça i telèfon.
-	La cadena té contractats una sèrie d'hotels de forma exclusiva. Cada hotel estarà definit pel codi d'hotel, nom, adreça, ciutat, telèfon i nombre de places disponibles.
-	D'igual forma, la cadena té contractats una sèrie de vols regulars de forma exclusiva. Cada vol ve definit pel nombre de vol, data i hora, origen i destinació, places totals i places de classe turista de les quals disposa.
-	La informació que es desitja emmagatzemar per cada turista és el codi de turista, nom i cognoms, adreça i telèfon.
D'altra banda, cal tenir en compte la següent informació:
-	A la cadena d'agències li interessa conèixer quina sucursal ha contractat el turista.
-	A l'hora de viatjar el turista pot triar qualsevol dels vols que ofereix la cadena, i en quina classe (turista o primera) desitja viatjar.
-	D'igual manera, el turista es pot allotjar en qualsevol dels hotels que ofereix la cadena, i triar el règim d'hostalatge (mitja pensió o pensió completa). Sent significativa la data d'arribada i de partida.

@startuml
@enduml
 
