PREVENTIVI INFISSI — Prima versione

CONTENUTO
- index.html: applicazione
- manifest.json: configurazione app installabile
- sw.js: cache offline dopo la prima visita
- icon-192.png / icon-512.png: icone

FUNZIONI
- Preventivi per infissi in alluminio, PVC, inferriate, cancelli in alluminio, posa e altre voci
- Calcolo €/m², €/pezzo o importo riga manuale
- Quantità, sconti, costi aggiuntivi, IVA e imponibile manuale modificabile
- Archivio locale, apertura/modifica, eliminazione
- Dati aziendali e logo
- Listino rapido personalizzabile
- Stampa o esportazione PDF tramite il menu di stampa del dispositivo
- Esportazione/importazione backup JSON

COME INSTALLARLA SU IPHONE
L'app web installabile deve essere pubblicata su un indirizzo HTTPS. Aprire semplicemente index.html da File non abilita tutte le funzioni PWA/offline.

Metodo semplice:
1. Caricare tutti i file della cartella su un hosting statico HTTPS (ad esempio un sito/hosting che controlli o un servizio di hosting statico).
2. Aprire l'indirizzo HTTPS in Safari su iPhone.
3. Toccare Condividi (quadrato con freccia verso l'alto).
4. Scegliere “Aggiungi alla schermata Home”. Se disponibile, attivare “Apri come app web”.
5. Avviare l'icona dalla schermata Home. Dopo la prima apertura, la cache può consentire l'uso offline.

IMPORTANTE
- Questa versione memorizza dati nel browser del dispositivo, non in un cloud condiviso. Esportare regolarmente il backup JSON.
- Il logo viene memorizzato localmente. Per il primo avvio inserire i dati aziendali e il proprio listino.
- I prezzi del listino sono vuoti intenzionalmente: non sono prezzi di mercato né un'offerta commerciale.
- L'IVA predefinita è 22% solo come valore iniziale modificabile. Verificare l'aliquota applicabile con il proprio commercialista.
- Il PDF usa la funzione di stampa del browser; layout e opzioni dipendono dal dispositivo.
- Prima dell'uso commerciale, provare i calcoli e verificare tutte le voci e le condizioni contrattuali.
