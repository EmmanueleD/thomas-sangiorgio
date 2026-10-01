# Product

<!-- impeccable:product-schema 1 -->

## Platform

web

## Stack

Static HTML/CSS (scelta esplicita dell'utente, 2026-10-01). Nessuna build, nessuna dipendenza, nessun JS richiesto. Deploy target: GitHub Pages via GitHub Actions, pubblicando la directory `dist/`, con dominio custom `thomassangiorgio.it`. Sites resta una pubblicazione precedente privata.

## Users

Lettori potenziali — chi arriva alla pagina (da un link condiviso, dai social o da Amazon) vuole capire in pochi secondi chi è Thomas Sangiorgio, cosa ha scritto e dove comprare il libro. (Dedotto dal brief; nessuna ricerca utenti.)

## Product Purpose

Sito personale di Thomas Sangiorgio, scrittore, strutturato come presenza autoriale minima: home, indice libri e schede di dettaglio. Successo: il visitatore capisce chi firma il sito, trova l'elenco delle opere e raggiunge la scheda del libro con una CTA chiara verso Amazon.

## Positioning

Sito autore essenziale, non blog e non portfolio: home istituzionale leggera, pagina listing dei libri e pagina dettaglio per ogni opera. L'autore resta nel masthead e nella struttura del sito; i contenuti editoriali verificati restano sulle schede libro.

## Capabilities and Constraints

- Sito statico multi-pagina, contenuti in italiano.
- Home, listing libri e pagina dettaglio libro; nessun blog, portfolio, contatto, social o newsletter inventato.
- Nessuna bio estesa o foto dell'autore senza contenuti verificati. La bio ironica presente sulla quarta di copertina resta disponibile come fonte futura.
- CTA primaria sulle schede libro: link Amazon <https://www.amazon.it/dp/B0HLBCMYPP>.

## Brand Commitments

- Mondo visivo **pinned dall'utente**: `docs/DESIGN.md` (editorial monograph — canvas bone `#f2f1ec`, Playfair Display 400 a 94/63px, Rubik 400 16px, hairline 1px neri, zero colori/ombre/raggi). Non deviare senza consenso esplicito.
- Dati editoriali verificati su Amazon (2026-10-01): titolo *Il Carro di Contenebra*, autore Thomas Sangiorgio, 108 pagine, italiano, pubblicazione 26 settembre 2026, independently published, ISBN-13 979-8177071251, formati copertina flessibile ed eBook.

## Evidence on Hand

- `dist/assets/cover.jpg` — copertina frontale (334×500), scaricata dal CDN Amazon il 2026-10-01.
- Sinossi ufficiale e dichiarazione di genere (dalla pagina Amazon / quarta di copertina), usate verbatim.

## Product Principles

1. La struttura è autoriale, ma il contenuto resta editoriale: home essenziale, indice opere, schede libro forti.
2. Solo contenuti verificati: testi dalla pagina Amazon o dalla quarta di copertina; mai inventare bio, recensioni o premi.
3. Semplicità radicale: niente build, niente JS, niente dipendenze senza motivazione concreta.
4. Italiano first: lingua dei contenuti e dell'interfaccia.
