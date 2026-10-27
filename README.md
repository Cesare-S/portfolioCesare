# Portfolio di Cesare Savoca

Portfolio in italiano, realizzato con HTML e CSS. Nessuna dipendenza o compilazione.

## Anteprima locale

```sh
python3 -m http.server 8000
```

Apri <http://localhost:8000>. Interrompi il server con `Ctrl+C`.

## Pubblicazione su GitHub Pages

1. Carica i file sul branch `main` del repository `Cesare-S/portfolioCesare`.
2. Apri **Settings → Pages** su GitHub.
3. In **Build and deployment**, scegli **Deploy from a branch**.
4. Seleziona **main**, cartella **/ (root)**, e premi **Save**.
5. A pubblicazione completata, apri <https://cesare-s.github.io/portfolioCesare/>.

Il file `.nojekyll` permette di pubblicare direttamente i file statici. I percorsi relativi funzionano nel sottopercorso del repository. Non serve un workflow personalizzato.

Documentazione: [creare un sito GitHub Pages](https://docs.github.com/en/pages/getting-started-with-github-pages/creating-a-github-pages-site).

## Aggiornamenti

- Contenuti e contatti: `index.html`.
- Colori e impaginazione: `styles.css`, con variabili iniziali per i colori.
- Avatar e icona del sito: file SVG in `assets/`.

Il percorso racconta le esperienze in azienda, i progetti personali e le collaborazioni con altri freelance. Non viene pubblicata una selezione di singoli progetti: nomi, schermate, link e casi di studio potranno essere aggiunti quando autorizzati. I nomi delle aziende restano omessi.

Il file `cv_copiato.txt` è materiale di lavoro locale, escluso da Git tramite `.gitignore`. È usato soltanto come fonte per esperienze e dettagli professionali: non viene collegato o proposto come CV scaricabile. La disponibilità resta per collaborazioni da remoto; i riferimenti al trasferimento presenti nel CV non vengono ripresi nel sito.

Nessun cookie, analytics, font remoto o modulo di contatto. L’email apre il programma di posta del visitatore; GitHub e LinkedIn collegano i profili pubblici.
