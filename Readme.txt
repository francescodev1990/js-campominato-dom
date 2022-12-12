
Consegna

Il computer deve generare 16 numeri casuali nello stesso range della difficoltà prescelta: le bombe. Attenzione: nella stessa cella può essere posizionata al massimo una bomba, perciò nell’array delle bombe non potranno esserci due numeri uguali.
In seguito l'utente clicca su una cella: se il numero è presente nella lista dei numeri generati - abbiamo calpestato una bomba - la cella si colora di rosso e la partita termina. Altrimenti la cella cliccata si colora di azzurro e l'utente può continuare a cliccare sulle altre celle.
La partita termina quando il giocatore clicca su una bomba o quando raggiunge il numero massimo possibile di numeri consentiti (ovvero quando ha rivelato tutte le celle che non sono bombe).
Al termine della partita il software deve comunicare il punteggio, cioè il numero di volte che l’utente ha cliccato su una cella che non era una bomba.

SCOMPOSIZIONE DEL PROBLEMA

1- GENERARE 16 NUMERI CASUALI CHE SONO LE BOMBE;
2- AL CLICK DELL'UTENTE SU UNA CELLA SE TROVA IL NUMERO PRESENTE NELL'ARRAY CALPESTA UNA BOMBA E LA CELLA SI TINGE DI ROSSO E LA PARTITA TERMINA;
3- AL CLICK DELL'UTENTE SU UNA CELLA SE TROVA IL NUMERO NON PRESENTE NELL'ARRAY LA CELLA SI TINGE DI AZZURRO E L'UTENTE PUO' CONTINUARE LA PARTITA;
4- LA PARTITA TERMINA ANCHE QUANDO L'UTENTE RIVELA TUTTE LE CELLE SENZA BOMBA;
5- PER FINIRE IL PC DEVE COMUNICARE IL PUNTEGGIO CHE EQUIVALE AL NUMERO DI VOLTE CHE L'UTENTE HA CLICCATO SULLE CELLE SENZA INCAPPARE SU UNA BOMBA;