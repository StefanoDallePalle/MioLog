# MioLog

> Loads, sets, reps and progress. Peer-reviewed by my muscles, not by my optimism.
>
> *Carichi, serie, ripetizioni e progressi. Peer review a cura dei miei muscoli, non del mio ottimismo.*

**English** · [Italiano](#italiano)

*Myo-* (muscle) + *log*. In Italian, *mio* also means "my": it's my training log.

A personal gym log. Installable web app (add it to your Home Screen), works offline.

**Disclaimer:** MioLog is a logging tool, not training or medical advice. Exercises and loads are your own choice and responsibility.

**Privacy:** the app never connects to any server (its Content-Security-Policy blocks all network requests from the page). Sessions and program live only in the browser storage of your device and leave it only when you tap "Export". This repository contains the app code only, no personal data.

- `index.html` — the app
- `sw.js` — offline cache
- `manifest.webmanifest`, `icon-*.png` — installation
- `fonts/` — Barlow Condensed, IBM Plex Sans, IBM Plex Mono (SIL Open Font License 1.1)

**Build your own program** in the *Program* tab: the app starts empty: add workouts, pick exercises from a bilingual library of 40+ exercises or create your own, set sets and rep ranges, reorder. Everything is saved on the device.

The app is bilingual (IT/EN): toggle in the top right.

Importing a program file: *History → Import file* with a `type: "program"` JSON file.
After changing `index.html`, bump `VERSION` in `sw.js`.

---

## Italiano

*Mio-* (muscolo) + *log*: il mio registro carichi.

Registro carichi personale per la palestra. App web installabile (aggiungi alla schermata Home), funziona offline.

**Avvertenza:** MioLog è uno strumento per registrare, non un consiglio di allenamento o medico. Esercizi e carichi sono una tua scelta e responsabilità.

**Privacy:** l'app non si collega a nessun server (la Content-Security-Policy blocca ogni connessione di rete dalla pagina). Sedute e scheda restano nella memoria del browser del dispositivo; escono solo con "Esporta dati". Questo repository contiene solo il codice dell'app, nessun dato personale.

- `index.html` — l'app
- `sw.js` — cache per l'uso offline
- `manifest.webmanifest`, `icon-*.png` — installazione
- `fonts/` — Barlow Condensed, IBM Plex Sans, IBM Plex Mono (SIL Open Font License 1.1)

**Crea la tua scheda** nella sezione *Scheda*: l'app parte vuota: aggiungi allenamenti, scegli gli esercizi da una libreria bilingue di oltre 40 esercizi o creane di tuoi, imposta serie e range di ripetizioni, riordina. Tutto resta salvato sul dispositivo.

L'app è bilingue (IT/EN): pulsante in alto a destra.

Importare una scheda da file: *Storico → Importa file* con un file JSON `type: "program"`.
Dopo una modifica a `index.html`, incrementare `VERSION` in `sw.js`.
