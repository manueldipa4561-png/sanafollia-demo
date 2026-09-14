# Sanafollia — demo website

Concept website non commissionato per **Ristorante Sanafollia**, Fidenza (PR), progettato e sviluppato da **Punto Due Studio**.

> Demo commerciale non ufficiale. Non implica alcun rapporto commerciale con l'attività.

## Obiettivo

Creare una demo di livello **CRESCITA** che trasformi il posizionamento reale di Sanafollia — cucina emiliana totalmente senza glutine — in un'identità digitale proprietaria, evitando il look da template e differenziandosi chiaramente dalle altre demo Punto Due Studio.

## Creative thesis

**La tradizione cambia farina. Non carattere.**

La demo usa il mondo della pasta fresca come sistema grafico: forme ispirate ai tortelli, superfici che ricordano carta e farina, giallo caldo derivato dalla facciata e composizioni volutamente tattili. Il risultato evita sia l'estetica retro-sovietica di Gagarin sia il linguaggio wine-label/editoriale di Cantina Canistracci.

## Informazioni pubbliche verificate

Ricerca aggiornata al **15 settembre 2026**.

### Identità e contatti

- Nome: **Ristorante Sanafollia**
- Indirizzo: **Via Benedetto Bacchini 23, 43036 Fidenza (PR)**
- Telefono usato nella demo: **+39 0524 527616**
- Email: **ristorantesanafollia@libero.it**
- Facebook: `https://www.facebook.com/Ristorante-Sanafollia-Gluten-Free-274627049386507/`

### Posizionamento

Fonti turistiche e piattaforme di settore descrivono Sanafollia come un ristorante con **cucina totalmente / 100% senza glutine**. Tripadvisor descrive una filosofia legata a cucina casalinga, farine alternative, pasta fresca e radici del territorio.

### Specialità usate nella demo

Parma Welcome indica esplicitamente tra le proposte tradizionali:

- tortelli
- torta fritta

La demo non inventa un menu completo e non pubblica prezzi non verificati.

### Reputazione

Tripadvisor mostra **4,5/5** e centinaia di recensioni. Il numero di recensioni è dinamico, quindi nella demo viene enfatizzato il rating senza fissare un conteggio destinato a diventare rapidamente obsoleto.

### Orari usati

Tripadvisor e Restaurant Guru risultano coerenti, al controllo del 15 settembre 2026, su:

- lunedì: chiuso
- martedì: chiuso
- mercoledì: chiuso
- giovedì: chiuso
- venerdì: 12:00–14:30 / 19:00–22:30
- sabato: 12:00–14:30 / 19:00–22:30
- domenica: 12:00–14:30 / 19:00–22:30

La demo specifica comunque che gli orari possono cambiare.

## Conflitti pubblici trovati

### Telefono

- Tripadvisor, Restaurant Guru, Francigena Fidenza Festival e altre fonti recenti riportano **0524 527616**.
- Parma Welcome riporta **334 1300603**.
- Un documento comunale del 2020 usava **334 1300603** per ordini/consegne.

**Dato scelto per la demo:** 0524 527616.

Motivo: è il numero maggiormente corroborato dalle fonti correnti e specialistiche. Il secondo numero non viene presentato come WhatsApp perché questa funzione non è stata verificata.

### Orari

Parma Welcome mostra un calendario più ampio rispetto a Tripadvisor e Restaurant Guru.

Per la demo sono stati preferiti Tripadvisor e Restaurant Guru perché concordano tra loro e Restaurant Guru dichiara un aggiornamento ad agosto 2026. Gli orari restano comunque un dato da confermare direttamente con il locale prima di una pubblicazione ufficiale.

## Fonti principali

- Tripadvisor — profilo ristorante e informazioni: `https://www.tripadvisor.it/Restaurant_Review-g1069551-d6662974-Reviews-Ristorante_Sanafollia_Gluten_free-Fidenza_Province_of_Parma_Emilia_Romagna.html`
- Restaurant Guru — contatti e orari aggiornati: `https://restaurantguru.it/RISTORANTE-SANAFOLLIA-Fidenza`
- Parma Welcome — scheda turistica ufficiale: `https://parmawelcome.it/scheda/ristorante-sanafollia/`
- Francigena Fidenza Festival — elenco ristoranti / contatti: `https://www.francigenafidenzafestival.it/fidenza/dove-mangiare/`
- Gluto — esperienza e posizionamento gluten-free: `https://www.glutoapp.com/it/locale/16393/ristorante-sanafollia`

## Distinctive decisions

1. Hero costruito come una **tavola astratta**, non come hero fotografico o poster.
2. Sistema grafico basato su **forme dei tortelli**, farine e superfici irregolari.
3. Palette butter-yellow / crema / oliva / terracotta, distinta dalle precedenti demo CRESCITA.
4. Tipografia prevalentemente bold-grotesque con accenti serif solo nelle frasi emotive.
5. La reputazione viene trattata come un grande elemento tipografico, non come carousel di recensioni.
6. Nessun marquee principale, nessuna galleria standard, nessuna sezione “chi siamo” generica.

## Funzionalità implementate

- responsive one-page
- sticky header
- menu mobile con supporto Escape
- click-to-call
- email
- Google Maps
- Facebook
- mobile action dock
- rating pubblico
- orari pubblici con caveat
- JSON-LD `Restaurant`
- SEO base
- Open Graph base
- favicon SVG originale
- custom 404
- reduced-motion support
- progressive-enhancement reveal animations
- Netlify configuration
- security headers

## Non implementato intenzionalmente

- WhatsApp non verificato
- Instagram non verificato
- menu completo non verificato
- prezzi non verificati
- form senza backend
- booking engine fittizio
- delivery non confermato come servizio corrente
- cookie banner finto
- analytics/pixel

## Struttura repository

```text
.
├── index.html
├── styles.css
├── script.js
├── 404.html
├── _headers
├── netlify.toml
├── robots.txt
└── assets/
    └── favicon.svg
```

## Deploy Netlify

- Base directory: vuoto
- Build command: vuoto
- Publish directory: `.`
- Functions directory: vuoto

`netlify.toml` imposta già la root come publish directory.

## Checklist dopo il deploy

1. Confermare direttamente con Sanafollia telefono e orari.
2. Verificare se 334 1300603 è ancora attivo e se è WhatsApp.
3. Verificare eventuale Instagram ufficiale.
4. Aggiungere canonical e `og:url` quando esiste l'URL pubblico.
5. Aggiungere sitemap e riferimento assoluto in robots.txt.
6. Aggiungere eventuale `og:image` con materiale utilizzabile.
7. Se il cliente fornisce foto ufficiali, valutare una gallery coerente col sistema visivo senza trasformare il sito in un template fotografico.
8. Eseguire QA live dopo il deploy Netlify.

## Punto Due Studio

Concept demo by **Punto Due Studio** — https://puntoduestudio.it/
