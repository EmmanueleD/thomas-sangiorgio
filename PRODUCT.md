# Product

<!-- impeccable:product-schema 1 -->

## Platform

web

## Stack

Static HTML/CSS (scelta esplicita dell'utente, 2026-10-01). Nessuna build, nessuna dipendenza, nessun JS richiesto. Deploy target: GitHub Pages via GitHub Actions, pubblicando la directory `dist/`, con dominio custom `thomassangiorgio.it`. Sites resta una pubblicazione precedente privata.

## Users

Lettori potenziali — chi arriva alla pagina (da un link condiviso, dai social o da Amazon) vuole capire in pochi secondi chi è Thomas Sangiorgio, cosa ha scritto e dove comprare il libro. (Dedotto dal brief; nessuna ricerca utenti.)

## Product Purpose

Pagina personale di Thomas Sangiorgio, scrittore, interamente dedicata al suo primo romanzo pubblicato, *Il Carro di Contenebra*. Successo: il visitatore capisce che il libro esiste, ne percepisce il tono (gotico / fiaba nera) e raggiunge la pagina Amazon per l'acquisto.

## Positioning

Sito monografico su un'unica opera: niente portfolio, niente blog, niente sezione autore (decisione utente, 2026-10-01). Il libro è l'unico protagonista; l'autore appare solo nel masthead.

## Capabilities and Constraints

- Una sola pagina statica, contenuti in italiano.
- Nessuna sezione autore, nessuna bio, nessuna foto dell'autore (decisione utente). La bio ironica presente sulla quarta di copertina resta disponibile come fonte futura.
- Nessun contatto, social o newsletter disponibile: non inventarli.
- Unica CTA: link Amazon <https://www.amazon.it/dp/B0HLBCMYPP>.

## Brand Commitments

- Mondo visivo **pinned dall'utente**: `docs/DESIGN.md` (editorial monograph — canvas bone `#f2f1ec`, Playfair Display 400 a 94/63px, Rubik 400 16px, hairline 1px neri, zero colori/ombre/raggi). Non deviare senza consenso esplicito.
- Dati editoriali verificati su Amazon (2026-10-01): titolo *Il Carro di Contenebra*, autore Thomas Sangiorgio, 108 pagine, italiano, pubblicazione 26 settembre 2026, independently published, ISBN-13 979-8177071251, formati copertina flessibile ed eBook.

## Evidence on Hand

- `dist/assets/cover.jpg` — copertina frontale (334×500), scaricata dal CDN Amazon il 2026-10-01.
- Sinossi ufficiale e dichiarazione di genere (dalla pagina Amazon / quarta di copertina), usate verbatim.

## Product Principles

1. Il libro è il protagonista: ogni elemento serve il romanzo, mai il contrario.
2. Solo contenuti verificati: testi dalla pagina Amazon o dalla quarta di copertina; mai inventare bio, recensioni o premi.
3. Semplicità radicale: niente build, niente JS, niente dipendenze senza motivazione concreta.
4. Italiano first: lingua dei contenuti e dell'interfaccia.
