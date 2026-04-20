---
layout: default
title: Legenda Formattazione
---

# 📘 Legenda Formattazione Markdown

Usa questa pagina come riferimento mentre scrivi i tuoi appunti. Il Markdown è semplice: basta aggiungere questi simboli al testo.

---

## 🛠️ Comandi Base

# `# Nome Autore`
**Titolo Principale** (usane solo uno per pagina).

## `## Titolo Sezione`
**Sottotitolo** (ideale per Biografia, Poetica, Opere).

### `### Argomento`
**Titolo piccolo** (per paragrafi specifici o singoli componimenti).

**`**parola**`**
**Grassetto** (indispensabile per evidenziare i concetti chiave).

*`*opera*`*
**Corsivo** (usalo per i titoli dei libri, delle poesie o termini stranieri).

> `> "Testo"`
> **Citazione** (crea un box rientrato, perfetto per i versi poetici).

`---`
**Linea divisoria** (una riga orizzontale per separare nettamente i temi).

---

## 🔗 Collegamenti (Reference)
Per collegare le pagine tra loro, usa le parentesi quadre per il testo e le tonde per il link:

* **Sito esterno:** `[Treccani](https://www.treccani.it)`
* **Torna alla Home:** `[🏠 Home](../../index.html)`
* **Altro autore:** `[Vai a Dante](../dante/index.html)`

---

## 🎨 Trucchi Avanzati (HTML)
Dato che Jekyll legge anche l'HTML, puoi usare questi per lo studio:

* **Sottolineare:** `<u>Testo</u>` -> <u>Testo</u>
* **Evidenziare:** `<mark>Testo</mark>` -> <mark>Testo</mark>
* **Checkbox:** `- [ ] Da studiare` / `- [x] Fatto!`

## 🎯 Collegamenti a punti specifici (Ancore)

**1. Ai Titoli (Automatico):**
Scrivi il titolo in minuscolo sostituendo gli spazi con i trattini.
* Esempio: `[Vai alla Poetica](#poetica)`

**2. A una parola qualsiasi (Manuale):**
* **Punto di arrivo:** `<a id="nome-scelto"></a>Parola`
* **Link di partenza:** `[Vai lì](#nome-scelto)`

**3. Da un'altra pagina:**
* `[Vai a Dante (Inferno)](../dante/index.html#inferno)`
