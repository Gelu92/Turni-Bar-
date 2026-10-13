# Turni Bar

App per il telefono per organizzare i turni, i riposi e le mansioni del bar.

- **Turni**: settimana da lunedì a domenica divisa in mattina e sera, generazione automatica, copia della settimana precedente, eliminazione di uno o più turni.
- **Invio**: messaggio WhatsApp con i turni della settimana, messaggio personale a ogni dipendente, PDF della settimana.
- **Mansioni**: checklist giornaliere per apertura, servizio, chiusura e pulizie settimanali.
- **Staff**: persone con più ruoli, turni che possono fare (mattina/sera), riposi fissi, ore massime. Ruoli e fasce orarie si modificano a piacere.

I dati restano salvati sul telefono (nessun server, nessun account). Usa ogni tanto **Staff → Copia backup** per tenerne una copia.

## Pubblicare l'app su GitHub Pages

1. Accedi a [github.com](https://github.com) e crea un nuovo repository (pulsante **New**), ad esempio `turni-bar`, impostato come **Public**.
2. Nel repository tocca **Add file → Upload files** e trascina **tutti i file e la cartella `icons`** contenuti in questo zip (non lo zip stesso). Poi tocca **Commit changes**.
3. Vai su **Settings → Pages**. In **Branch** scegli `main` e la cartella `/ (root)`, poi **Save**.
4. Dopo un paio di minuti l'app è online all'indirizzo `https://TUO-NOME-UTENTE.github.io/turni-bar/`.

## Installare l'app sul telefono

Apri l'indirizzo dell'app dal telefono:

- **Android (Chrome)**: tocca il pulsante **Installa** in alto nell'app, oppure menu ⋮ → **Installa app**.
- **iPhone (Safari)**: tocca **Condividi** → **Aggiungi alla schermata Home**.

Una volta installata si apre a schermo intero e funziona anche senza internet.

## Aggiornare l'app

Quando carichi una nuova versione di `index.html`, cambia anche il numero in `sw.js` (`turni-bar-v1` → `turni-bar-v2`), così i telefoni scaricano la versione nuova.

## File

| File | A cosa serve |
|---|---|
| `index.html` | L'app |
| `manifest.webmanifest` | Nome, colori e icone per l'installazione |
| `sw.js` | Funzionamento senza internet |
| `icons/` | Icone della schermata Home (logo Surprise) |
| `logo-surprise.png` | Logo Surprise in alta risoluzione (1024×1024) |
