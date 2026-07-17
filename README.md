# Simulacr ⚡

> Simulatore di circuiti elettronici interattivo in HTML, CSS e JavaScript puro.

## Descrizione

**Simulacr** è un simulatore di circuiti elettronici completamente client-side, sviluppato senza dipendenze esterne. Offre un ambiente moderno per creare, modificare, analizzare e visualizzare circuiti elettrici ed elettronici direttamente nel browser.

## Caratteristiche principali

### 🎛 Interfaccia moderna
- Tema chiaro/scuro automatico basato sulle preferenze di sistema
- Layout con toolbox, area di lavoro e pannello laterale
- Interfaccia responsive per desktop e dispositivi mobili
- Supporto schermo intero
- Notifiche toast e menu contestuali

### 🔧 Editor di circuiti
- Drag & drop dei componenti
- Griglia con snap automatico
- Zoom, pan e adattamento vista
- Selezione, spostamento ed eliminazione elementi
- Collegamento rapido dei terminali
- Ordinamento automatico dei cavi (beta)
- Salvataggio e caricamento progetti in JSON

### ⚙️ Simulazione
- Avvio e pausa della simulazione
- Controllo della velocità
- Visualizzazione del flusso di corrente
- Modalità elettroni o corrente convenzionale
- Analisi in tempo reale del circuito
- Colorazione per potenziale elettrico
- Visualizzazione etichette e valori

## Componenti disponibili

### Base
- Cavo
- Batteria
- Resistore
- Lampadina
- Interruttore
- Fusibile

### Componenti elettronici
- Condensatore
- Induttore
- Diodo
- LED
- Potenziometro
- Motore DC
- Cicalino

### Sorgenti
- Generatore AC

### Avanzati
- Trasformatore
- Amplificatore operazionale ideale

### Strumenti di misura
- Voltmetro
- Amperometro
- Massa/Terra
- Oscilloscopio integrato

## Tecnologie utilizzate

- HTML5
- CSS3 con variabili CSS e tema dinamico
- JavaScript Vanilla
- SVG per il rendering dei componenti
- Canvas per l’oscilloscopio

## Punti di forza

- Nessuna dipendenza esterna
- Tutto in un singolo file HTML
- Zero variabili globali
- Motore di simulazione incapsulato
- Elevata portabilità
- Ideale per didattica, prototipazione e dimostrazioni

## Installazione

```bash
git clone https://github.com/zmykerd/Simulacr
cd simulacr
```

Aprire semplicemente `simulacr.html` nel browser.

## Screenshot


```md
<img width="1877" height="889" alt="Schermata_20260717_180523 (1)" src="https://github.com/user-attachments/assets/855f741c-6b57-4977-bb14-efadb4e6f9ac" />

```

## Roadmap

- [ ] Supporto ai transistor
- [ ] Circuiti digitali
- [ ] Esportazione immagini SVG/PNG
- [ ] Simulazione avanzata SPICE
- [ ] Libreria componenti espandibile

## Licenza

Distribuito sotto licenza MIT (bisogna dare i crediti).

---

Creato con HTML, SVG e JavaScript per rendere l'elettronica più accessibile.
