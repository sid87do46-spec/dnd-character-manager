D&D CHARACTER MANAGER 0.4 — PWA

Novità: manifest installabile, icone, Service Worker per utilizzo offline dopo la prima visita online. Motore e dati della v0.3 invariati.

PUBBLICAZIONE DA SMARTPHONE:
1. Esporta prima il backup JSON dalla versione precedente.
2. Carica TUTTI i file di questa cartella nella stessa directory di un hosting HTTPS (ad esempio GitHub Pages o Netlify Drop).
3. Apri l’indirizzo HTTPS con Chrome Android e attendi il primo caricamento.
4. Menu Chrome > Aggiungi a schermata Home / Installa app (la voce dipende dal browser).
5. Apri l’app, crea un personaggio di prova, chiudila, attiva modalità aereo e verifica la riapertura.

LIMITI:
- Il Service Worker non funziona aprendo index.html come file locale (file://).
- Il backup LocalStorage resta legato all'origine: importare il JSON sul nuovo indirizzo HTTPS.
- Nessuna sincronizzazione cloud; cancellare dati del browser può eliminare i personaggi.
- Le regole avanzate e le automazioni di classe sono ancora parziali.
