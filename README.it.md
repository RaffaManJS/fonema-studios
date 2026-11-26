🇬🇧 [English](README.md) | 🇮🇹 Italiano

## Compilare il CSS

Installa le dipendenze una sola volta, poi compila `input.css` nel file minificato `output.css`:

```bash
npm install
npm run build
```

# Fonema Studios

Sito dimostrativo per uno studio di registrazione fittizio, realizzato con HTML e Tailwind CSS come progetto per il mio portfolio.

> **Nota:** Fonema Studios non è un'attività reale. Indirizzo, numero di telefono e altri dati di contatto sono segnaposto, e le foto provengono da [Unsplash](https://unsplash.com).

## Pagine

- **Home**: nome dello studio nell'hero, un vinile SVG che ruota lentamente, un lettore audio con dei brani e un invito finale prima del footer
- **Servizi**: registrazione, sala prove, mixing e mastering, produzione (beat rock e rap) e un pacchetto completo su preventivo
- **Galleria**: 12 foto divise in 4 categorie
- **Contatti**: come raggiungere lo studio (dati segnaposto),in cui è presente anche una sezione FAQ.

## Tecnologie

- HTML5
- Tailwind CSS (installato con npm, compilato e minificato)
- Variabili CSS per la palette dei colori
- Font in locale (self-hosting): Shrikhand (titoli e logo) e DM Sans
- Grafiche SVG inserite nel codice

## Caratteristiche

- **Palette vintage chiara** definita con variabili CSS (crema `#F3EAD8`, marrone `#4A2E1B`, terracotta `#A3472A`), per cambiare i colori da un unico punto
- **Immagini responsive**: le foto della galleria usano `srcset` in quattro dimensioni (1200, 800, 600 e 400 px), così ogni dispositivo scarica solo quella che gli serve
- **Font in locale**: il sito non fa richieste a server esterni per i font
- **Prestazioni**: punteggio Lighthouse sopra il 97 su tutte le pagine

## Struttura del progetto

- `assets/`: immagini e altri file statici
- `input.css`: file sorgente di Tailwind
- `output.css`: CSS compilato e minificato usato dalle pagine
- `fonts.css`: dichiarazioni dei font in locale
- `package.json` e `package-lock.json`: configurazione di npm e versioni esatte delle dipendenze

La cartella `node_modules/` non è inclusa nel repository: si ricrea con `npm install`.

## Crediti

Realizzato da Raff come parte del portfolio da junior web developer. Foto dei collaboratori di Unsplash, usate secondo la [licenza Unsplash](https://unsplash.com/license).
