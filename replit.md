# Pagina Download Report di Sostenibilità 2024 - Tasca d'Almerita

## Panoramica del Progetto
Pagina web mobile-first dedicata al download del Report di Sostenibilità 2024 di Tasca d'Almerita. La pagina presenta un design elegante che rispecchia l'identità visiva del sito ufficiale dell'azienda, con particolare attenzione alla sostenibilità ambientale e all'agricoltura biologica.

## Caratteristiche Principali

### Design
- **Mobile-First**: Progettato prioritariamente per dispositivi mobili, con layout responsive per tablet e desktop
- **Palette Colori**: Toni terrosi ispirati al brand Tasca d'Almerita (marrone, beige, verde oliva)
- **Tipografia**: Font serif eleganti (Georgia, Times New Roman) che richiamano tradizione e qualità

### Funzionalità
1. **Header Sticky**: Logo aziendale nero e titolo della pagina sempre visibili durante lo scroll
2. **Carosello Hero**: 6 immagini dei vigneti Tasca d'Almerita con scorrimento automatico ogni 5 secondi
3. **Navigazione Manuale**: Indicatori cliccabili per navigare tra le immagini del carosello
4. **Pulsante Download**: Link diretto al PDF del Report di Sostenibilità 2024
5. **Sezione Informativa**: Informazioni sulla certificazione B Corp

### Elementi Tecnici
- **HTML5 Semantico**: Struttura chiara e accessibile
- **CSS3 Moderno**: Variabili CSS, Flexbox, Grid, animazioni fluide
- **JavaScript Vanilla**: Nessuna dipendenza esterna, codice leggero e performante
- **Accessibilità**: Focus visibile, supporto per riduzione movimento, ARIA labels

## Struttura File

```
├── index.html          # Pagina principale HTML con struttura completa
├── style.css           # Foglio di stile CSS con tutti i commenti in italiano
└── replit.md          # Documentazione del progetto
```

## Codice Commentato

### HTML (index.html)
Ogni sezione HTML è commentata in italiano:
- Header con logo e titolo
- Sezione hero con carosello
- Contenuto principale con informazioni
- Pulsante di download
- Footer

### CSS (style.css)
Il CSS è organizzato in sezioni commentate:
- Reset e variabili globali
- Stili header
- Carosello hero
- Contenuto principale
- Pulsante download
- Sezione informativa
- Footer
- Media queries responsive
- Animazioni
- Accessibilità

## Responsive Breakpoints

- **Mobile**: < 768px (default, mobile-first)
- **Tablet**: ≥ 768px
- **Desktop**: ≥ 1024px

## Colori Brand

```css
--color-primary-brown: #8B6F47    /* Marrone principale */
--color-dark-brown: #6B5333       /* Marrone scuro */
--color-light-brown: #A0826D      /* Marrone chiaro */
--color-beige-light: #F5F1E8      /* Beige chiaro */
--color-beige: #EBE4D1            /* Beige medio */
--color-green: #6B8E23            /* Verde oliva */
```

## Link Esterni

- **Logo**: https://www.tascadalmerita.it/images/svg/Logo.svg
- **Report PDF**: https://cms.tascadalmerita.it/wp-content/uploads/2025/04/Tasca-SOStain-Report-2024.pdf
- **Immagini Carosello**: 6 immagini ad alta risoluzione dai CDN di Tasca d'Almerita

## Server Web

Il progetto utilizza un semplice server HTTP Python sulla porta 5000:
```bash
python3 -m http.server 5000
```

## Modifiche Future Possibili

- Aggiungere transizioni fade tra le immagini del carosello
- Implementare gesture di swipe per dispositivi touch
- Aggiungere sezioni con highlights del report
- Integrare animazioni on-scroll per elementi
- Aggiungere form di newsletter
- Implementare lazy loading per le immagini

## Data Creazione
11 Novembre 2025

## Note Tecniche
- Nessuna dipendenza esterna richiesta
- Compatibile con tutti i browser moderni
- Performance ottimizzate per mobile
- Immagini caricate da CDN esterno
