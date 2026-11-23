# Voci Okubai

Voci italiane naturali per lo screen reader [NVDA](https://www.nvaccess.org/), che funzionano offline: la sintesi avviene tutta sul computer e nessun testo viene inviato altrove.

Ci sono undici voci. Femminili: Voce uno, Elisa, Alessia, Luna, Beatrice, Elena e Marika. Maschili: Samuel, Adams, Giulio e Jared. Tutte usano lo stesso dizionario di pronuncia italiana e leggono in italiano.

## Requisiti

- NVDA 2026.1 o successivo, 64 bit.
- Windows 10 o Windows 11, 64 bit.

## Installazione

1. Apri la pagina dell'ultima versione, nella sezione Releases, e scarica il file `VociOkubai-0.8.8.nvda-addon`. È il componente principale: contiene il motore di sintesi e Voce uno.
2. Apri il file scaricato e conferma l'installazione. Riavvia NVDA quando te lo chiede.
3. Premi NVDA+Ctrl+S, scegli "Voci Okubai" e premi Invio.

## Aggiungere le altre voci

Non serve tornare su questa pagina. In NVDA apri il menu (NVDA+N), poi Strumenti, **Voci Okubai...**. Nella finestra trovi l'elenco di tutte le voci:

- **Ascolta una prova** (Alt+A) fa sentire una breve frase della voce selezionata;
- **Installa o aggiorna** (Alt+I) scarica la voce e la rende subito disponibile, senza riavviare NVDA;
- **Rimuovi** (Alt+R) toglie la voce.

Poi scegli la voce con NVDA+Ctrl+V.

Ogni voce è anche un componente aggiuntivo separato, per esempio `VociOkubai-voce-marika-0.8.8.nvda-addon`, che si installa come gli altri componenti di NVDA. Funziona solo insieme al componente principale.

## Aggiornamenti

Voci Okubai si aggiorna da solo. A ogni avvio di NVDA, e poi ogni 6 ore finché NVDA resta aperto, controlla se ci sono versioni nuove del componente e delle voci installate, e chiede se installarle. Se sei offline non dice nulla.

Puoi controllare subito dal menu Strumenti, **Controlla aggiornamenti di Voci Okubai...**. Per disattivare il controllo automatico: Preferenze, Impostazioni, categoria Voci Okubai.

## File di ogni versione

| File | Che cos'è |
| --- | --- |
| `VociOkubai-<versione>.nvda-addon` | componente principale, con Voce uno |
| `VociOkubai-voce-<nome>-<versione>.nvda-addon` | una voce in più |
| `VociOkubai-anteprima-<nome>.wav` | frase di prova della voce, usata dalla finestra Voci Okubai |
| `voci.json` | elenco delle voci, usato dalla finestra Voci Okubai |
| `SHA256SUMS.txt` | impronte SHA-256 dei file |

## Licenza

Copyright (C) 2026 Okubai.One. Il codice è distribuito secondo i termini della GNU General Public License, versione 2 o successiva (file `LICENSE`). Le voci si basano su [Piper](https://github.com/OHF-Voice/piper1-gpl) (licenza MIT). I riconoscimenti completi sono nel file `LICENZE.txt` dentro ogni componente.
