# 🛡️ J&C Assicurazioni — Sito Web

Sito web one-page per J&C Assicurazioni, agenzia assicurativa con sede a Cisterna di Latina. Presenta l'azienda, i servizi offerti e le informazioni di contatto, costruito con HTML, Bootstrap 5 e CSS custom.

🔗 **[Demo live](https://j-c-sito.vercel.app/)**
---

## Panoramica

Il sito è una landing page responsive che accompagna il visitatore dalla presentazione dell'agenzia al catalogo dei prodotti assicurativi, fino ai contatti e alle informazioni legali. Il layout è ottimizzato per mobile con griglia Bootstrap e navbar collassabile con hamburger menu.

## Sezioni

- **Chi siamo** — Presentazione dell'agenzia e della filosofia di consulenza personalizzata.
- **Servizi** — 15 prodotti assicurativi organizzati in 5 categorie: Risparmio e Previdenza, Salute e Infortuni, Casa e Patrimonio, Veicoli e Viaggi, Attività Professionali e Imprese.
- **Footer** — Informazioni IVASS, iscrizione RUI, recapiti (telefono, WhatsApp, email, PEC), link social (Instagram, Facebook) e nota legale.
- **Privacy Policy** — Informativa GDPR e Cookie Policy accessibili tramite offcanvas Bootstrap.

## Tech Stack

| Tecnologia | Ruolo |
|---|---|
| **HTML5** | Struttura della pagina |
| **Bootstrap 5.3** | Griglia responsive, navbar, card, offcanvas |
| **CSS custom** | Personalizzazione colori, tipografia, ombre |
| **Bootstrap Icons** | Icone social e navigazione |
| **Google Fonts** | Montserrat e Roboto |

## Struttura del Progetto

```
J-C_sito/
├── index.html          # Pagina principale (one-page)
├── style.css           # Stili custom
├── main.js             # Script (predisposto)
└── immagini/           # Logo e immagini dei prodotti assicurativi
    ├── logo_j&C.jpg
    ├── piano_accumulo_bambini.png
    ├── fondo_pensione.png
    ├── tcm.png
    ├── LTC.png
    ├── Assicurazione sanitaria.png
    ├── polizza_infortuni.png
    ├── polizza_casa.png
    ├── ass_condominio.png
    ├── ass_capofamiglia.png
    ├── cane_gatto.png
    ├── RCA.png
    ├── Assicurazione_viaggi.png
    ├── attività_commerciali.png
    └── RC_oss.png
```

## Utilizzo

Il sito è statico e non richiede build o dipendenze. Per visualizzarlo in locale basta aprire `index.html` nel browser, oppure usare un server locale:

```bash
# Con Python
python3 -m http.server 8000

# Con VS Code
# Installare l'estensione Live Server e cliccare "Go Live"
```

## Licenza

© 2026 Edoardo Poli. Tutti i diritti riservati.
