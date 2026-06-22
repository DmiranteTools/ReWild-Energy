# 🌿 Rewild Energy – Planning Tool

**Strumento di analisi per la pianificazione di progetti energetici rinnovabili in Italia.**

Sviluppato da [Rewild Energy](https://www.rewilder.energy), questo tool è pensato per consentire alle aziende target di valutare rapidamente l'impatto potenziale di un sito su specie animali protette direttamente nel browser, senza bisogno di GIS, o competenze tecniche specializzate.

---

## 📋 Panoramica

Lo sviluppo di impianti di energia rinnovabile richiede una valutazione attenta dell'impatto sulla fauna locale. Il Rewild Energy Planning Tool semplifica questa fase preliminare: basta selezionare un punto o un'area sulla mappa per ottenere immediatamente un elenco delle specie presenti, il loro stato di conservazione a livello italiano e globale, e un indice di rischio (Hazard) associato.
Il tool è ottimizzato per l'Italia e si basa su dati raster geospaziali ad alta risoluzione sulle distribuzioni delle specie avifaunistiche, incrociati con le categorie della Lista Rossa IUCN.

---

## ✨ Funzionalità principali

### 🗺️ Interrogazione interattiva della mappa

<p align="center">
  <img src="assets/tappabuchi.png" alt="Placeholder" width="800">
</p>

- **Click su un punto** per analizzare una singola posizione geografica
- **Selezione di un'area** (SHIFT + trascina) per analizzare una bounding box su larga scala
- **Inserimento manuale di coordinate** per interrogazioni precise su punti o aree definiti

### 🐦 Analisi delle specie
Per ogni interrogazione il tool restituisce:
- Elenco completo delle specie presenti nel punto o nell'area selezionata
- **Categoria Lista Rossa italiana** (LC, NT, VU, EN, CR, DD)
- **Categoria Lista Rossa globale IUCN**
- **Indice Hazard** per ciascuna specie, misura del rischio associato alla presenza della specie nel sito

### 🌈 Mappa di ricchezza delle specie
- Overlay visivo sulla mappa che mostra la **densità di specie** su tutto il territorio italiano
- Legenda numerica con il valore massimo rilevato nei dati
- Attivabile/disattivabile con un singolo click, caricamento in background

### ⚖️ Modalità confronto
- Analisi comparativa di **fino a 5 siti** (punti o aree) in parallelo
- Pannello dedicato con riepilogo delle specie vulnerabili e dell'Hazard medio per ciascun sito
- Identificazione automatica del **sito migliore** per impatto sulla biodiversità

### 📥 Esportazione dati
- **CSV per singola interrogazione**: elenco dettagliato delle specie con tutti i metadati
- **CSV confronto**: tabella riassuntiva di tutti i siti analizzati in modalità confronto
- Formato semicolon-separated, compatibile con Excel in italiano

---

## 🚀 Installazione e avvio

1. Scaricare il pacchetto del programma su [Zenodo](https://zenodo.org/record/XXXXXXX) (formato `.zip`).
2. Estrarre il contenuto dello zip in una cartella a piacere sul proprio computer.
3. Aprire la cartella estratta, ed avviare `RewildEnergy.exe` con un semplice doppio-click.
4. Il browser si aprirà automaticamente, ed il tool sarà immediatamente pronto all'uso.

> ⚠️ Non è richiesta alcuna installazione di software esterni, il tool è completamente autonomo.


## 📊 Dati

Le distribuzioni delle specie sono basate su dati raster in formato GeoTIFF (EPSG:4326), con una copertura completa del territorio italiano. I dati sullo stato di conservazione e l'indice Hazard derivano dalla Lista Rossa IUCN e da elaborazioni interne Rewild Energy.


---

## 📄 Licenza

Nessuna Licenza

## 🤝 Contatti

📧 [alessandra.dalessio@uniroma1.it](mailto:alessandra.dalessio@uniroma1.it)

---

*Rewild Energy Planning Tool — biodiversità e rinnovabili, insieme.*

