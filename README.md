# Introduzione
Questo progetto permette di comandare un led collegato ad Arduino tramite la tastiera del computer. Il funzionamento è elementare ma consente di capire come la porta seriale comunichi con la scheda Arduino.

# Descrizione del progetto
Il sistema è composto da un led che si accende e spegne tramite opportuni comandi provenienti dal computer.
Il comando "a" accende il led, mentre il comando "s" spegne il led.
Nel caso si scriva una qualsiasi altra lettera il sistema la ignora: infatti, viene specificato nel codice di cancellare ogni dato differente da quelli dati.

# Schema di montaggio
Lo schema di montaggio, naturalmente, è molto semplice. Da sottolineare che, avendo collegato il led al pin 13, si accenderà anche il led incorporato sulla scheda.
Inoltre, all'avvio del codice, il led lampeggerà più volte per via dei dati inviati dal computer ad Arduino. Pure il led Rx (corrispondente alla ricezione dati dalla porta seriale) lampeggerà ogni volta che verrà premuto un tasto.

![image](https://user-images.githubusercontent.com/99251089/153384484-02249279-65a8-4341-920b-f4dbe724f203.png)

# Codice


# Espansioni suggerite
È possibile controllare più led (o altri dispositivi) e inviare anche dati da Arduino al computer (tramite appositi sensori) come pulsanti o altro.
