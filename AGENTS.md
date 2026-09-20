# AGENTS.md — statuto operativo

**App: Crypto Index Fund** · repo `crypto-index-fund`

Vale per qualunque agente automatico che lavori qui (Codex in primo luogo). Chi decide resta Enzo.
Versione estesa dello statuto: `Sefirot8989/sistema-vita` → `AGENTS.md`.

> **Attenzione:** questa repo è **pubblica** e la dashboard la guardano i partecipanti. Nessun dato di persone reali, nemmeno negli esempi: né nomi, né quote, né importi, né indirizzi di portafoglio.

## Ruoli

- **Codex** — esecuzione: codice, rami, pull request. Pieni permessi sulla macchina Windows in cloud (Azure).
- **Claude** — memoria: tiene aggiornati Notion, Dropbox e il Ponte di Comando, e chiude i task quando una pull request entra in `main`.
- **Enzo** — l'unico che unisce.

## Regole non negoziabili

1. Mai spingere direttamente su `main`: ramo `codex/<breve-descrizione>` e pull request.
2. Mai unire la propria pull request: aspetta Enzo.
3. Mai segreti nella repo (token, chiavi, PIN), nemmeno negli esempi o nei messaggi di commit.
4. Notion e Dropbox sono in sola lettura: si leggono, non si modificano. Lì scrive Claude.
5. Mai rinominare i task di Notion e mai crearne: il Ponte li riconosce dall'identificativo.
6. Niente dati personali o di clienti nei file di esempio.

## Prima di iniziare

Leggi l'ultimo file in `APP_AGGIORNAMENTI/` della cartella Dropbox di questa app, poi il README e i capitolati. Se Dropbox e codice si contraddicono, fermati e chiedi a Enzo.

## Pull request

Titolo: se il lavoro è un passo del Ponte, comincia con il nome del task (`Codex · N. ...`).
Corpo, sempre tre voci: **Cosa cambia** · **Cosa ho verificato** · **Cosa può rompersi** (compreso: questo merge pubblica il sito in diretta? sì/no).

## Quando il lavoro è finito

Non chiudere niente in Notion: lo fa Claude leggendo le pull request unite.

## Documentazione di questa app

Dropbox: `/02_PROGETTI/01_Attivi/CRYPTO_INDEX_FUND/APP_AGGIORNAMENTI/`

Ultimo aggiornamento dello statuto: 20 settembre 2026.
