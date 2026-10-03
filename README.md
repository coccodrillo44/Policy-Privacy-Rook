# CosaFare — Informativa sulla Privacy (Sito Web)

Sito web statico, moderno e reattivo, realizzato per la consultazione e pubblicazione online dell'**Informativa sul Trattamento dei Dati Personali (Privacy Policy)** dell'applicazione mobile e piattaforma **CosaFare** (Eventi, Sagre e Tradizioni in Toscana), pienamente conforme al **Regolamento (UE) 2016/679 (GDPR)**.

---

## 🚀 Come visualizzare il sito

Il sito è completamente statico e non richiede l'installazione di librerie o dipendenze server:

1. **Apertura diretta nel browser:**
   - Fai doppio clic sul file [`index.html`](./index.html) per aprirlo direttamente in qualsiasi browser (Google Chrome, Microsoft Edge, Mozilla Firefox, Apple Safari).

2. **Anteprima con server locale (opzionale):**
   - Con Python:
     ```bash
     python -m http.server 8000
     ```
     e visita `http://localhost:8000` nel browser.
   - Con Node.js (`npx serve`):
     ```bash
     npx serve .
     ```

---

## 🌟 Funzionalità Principali

- **Design Coerente & Curato:** Stessa identità visiva, colori identitari toscani (terracotta `#c84b31`), layout pulito e massima leggibilità legale già adottati per i *Termini e Condizioni di Utilizzo*.
- **Indice Interattivo con ScrollSpy:** Navigazione rapida tra tutte le 14 sezioni dell'informativa privacy con evidenziazione automatica della sezione attiva durante lo scorrimento.
- **Ricerca Dinamica nel Testo:** Barra di ricerca rapida con conteggio delle corrispondenze, scorrimento tra i risultati ed evidenziazione dei termini cercati. Scorciatoia da tastiera: `/` o `Ctrl + K`.
- **Tema Chiaro / Scuro (Dark Mode):** Rilevamento automatico delle preferenze del sistema operativo con pulsante di attivazione manuale e salvataggio delle preferenze in `localStorage`.
- **Barra di Avanzamento Lettura:** Indicatore visivo dinamico posto in cima allo schermo.
- **Copia Rapida Link Paragrafi:** Pulsante dedicato accanto a ogni titolo di capitolo per copiare negli appunti l'URL con ancoraggio diretto (es. `#sec-10`), accompagnato da notifica toast animata.
- **Supporto Stampa & Salvataggio PDF:** Regole CSS dedicate `@media print` per una stampa o esportazione in PDF pulita, priva di elementi di navigazione e bottoni.
- **Completamente Responsive:** Ottimizzato per smartphone, tablet e monitor desktop con cassetto mobile per l'indice dei contenuti.

---

## 📁 Struttura dei File

- [`index.html`](./index.html) — Struttura semantica del documento con tutte le 14 sezioni conformi al GDPR.
- [`style.css`](./style.css) — Foglio di stile CSS con variabili CSS, design responsive e supporto dark/light mode.
- [`script.js`](./script.js) — Logica interattiva (ricerca, scrollspy, copia link, progress bar, dark mode).
- [`privacy-policy.txt`](./privacy-policy.txt) — File originale del testo legale.
- [`README.md`](./README.md) — Documentazione del progetto web.
