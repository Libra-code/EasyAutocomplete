# 🎯 EasyAutocomplete — Powerful & Flexible jQuery Autocomplete Plugin

[![Demo Preview](path-to-demo-image/EasyAutocomplete.gif)](https://link-to-live-demo.com)

**EasyAutocomplete** è un potente plugin jQuery per l'autocompletamento che permette di arricchire facilmente i tuoi campi di input con suggerimenti dinamici.

---

## 🚀 Caratteristiche principali

- 🔌 Supporto per sorgenti **locali** o **remote** (JSON, XML, testo semplice)
- ⚙️ Chiamate AJAX automatiche
- 🔍 Ricerca, ordinamento e matching avanzati delle stringhe
- 🧩 Template **personalizzabili** per la lista dei risultati
- 🔁 Gestione eventi tramite **callback** flessibili
- 🎨 Stili CSS **moderni** inclusi (senza immagini!)

> 👉 Consulta la [Guida Completa](#) e la [Documentazione](#) per una panoramica approfondita.

---

## ⚡ Esempio Rapido

### 🔸 HTML

```html
<input id="countries" placeholder="Cerca un paese...">
```

### 🔸 JavaScript

```javascript
var options = {
  url: "data/countries.json",
  getValue: "name"
};

$("#countries").easyAutocomplete(options);
```

### 🔸 JSON (esempio)

```json
[
  { "name": "Afghanistan", "code": "AF" },
  { "name": "Albania", "code": "AL" },
  { "name": "Algeria", "code": "DZ" },
  { "name": "Andorra", "code": "AD" }
]
```

---

## 🧪 Demo

Esempi pratici sono disponibili nella cartella [`/demo`](./demo).  
Oppure visita la [Live Demo](#).

---

## 📁 Struttura del progetto

| Cartella     | Contenuto                                      |
|--------------|------------------------------------------------|
| `/dist`      | File pronti all'uso (JS/CSS compilati)         |
| `/src`       | Codice sorgente                                |
| `/demo`      | Esempi d’uso                                   |
| `/test`      | Test unitari                                   |

---

## 🔧 Build e Test

### Per compilare il progetto:

```bash
grunt build
```

### Per eseguire tutti i test:

```bash
grunt test
```

---

## 📃 Licenza

Distribuito sotto licenza [MIT](https://github.com/pawelczak/EasyAutocomplete/blob/master/LICENSE.txt).

---

## 🔗 Link Utili

- 🌐 [Homepage del progetto](#)
- 📘 [Documentazione completa](#)
- 🛠️ [Guida all’uso](#)
- 🧪 [Demo interattive](#)
