# Ciclismo_records
Progetto ciclismo: raccolta dati e rielaborazione



Questo progetto è creato e pensato per le associazioni ciclistiche che hanno bisogno di raccogliere i tempi dei partecipanti, inserirli in un db e in fine restituire le classifiche giornaliere, parziali e definitive non solo dei partecipanti ma anche dei gruppo ciclistici. Il tutto è stato pensato con una componente hardware per effettuare lo start e lo stop del cronometro una volta che il ciclista passatra i punantori laser che si trovano rispettivamente uno alla partenza e uno alla fine del circuito ( allo stato attuale e possibile usare il tutto solamente per le competizioni in cui i concorrenti partecipano uno per volta ).


Il sistema del cronometro è gestito tramite Arduino, e la componentistica è la seguente: 
 - Arduino 
 - 2 Modulo KY-008 con diodo laser puntatore 650nm 5mw rosso keyes proiezione 20 mt
 - 2 fotoresistenza
 - 2 resistenze da 100 Ohm
 - 1 resistenza da 220 Ohm
 - 1 resistenza da 100 kOhm
 - 1 led RGB
 - Colemeter HD44780 1602 16x2 LCD Display MODULO Blu RETROILLUMINA

Dopo aver ottenuto il tempo del ciclista, sara possibile inserire il tempo in una banca dati in cui basterà inserire solamente il numero del ciclista e il tempo impiegato per effetuare il percorso. Il tutto sara gestito tramite una pagina web che andra a interagire con il DB ( MySQL ). In questo modo sarà possibile creare classifiche della giornata di gara, e in un secondo momento sarà possibile stilare una classifica parziale e poi la definitiva. Inoltre sarà possibile avere tuttqa una serie di dati: il milior tempo di ogni gara, il miglior tempo in assoluto, la velocità massima del ciclista, la velocità media del ciclista, ecc... 
