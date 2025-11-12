# Pagina Download Report di Sostenibilità 2024 - Tasca d'Almerita

## Panoramica del Progetto
Pagina web mobile-first dedicata al download del Report di Sostenibilità 2024 di Tasca d'Almerita. La pagina presenta un design elegante che rispecchia l'identità visiva del sito ufficiale dell'azienda, con particolare attenzione alla sostenibilità ambientale e all'agricoltura biologica.

## Caratteristiche Principali

### Design
- **Mobile-First**: Progettato prioritariamente per dispositivi mobili, con layout responsive per tablet e desktop
- **Palette Colori**: Background crema (#FFF8E7) con toni terrosi ispirati al brand Tasca d'Almerita (marrone, beige, verde oliva)
- **Tipografia**: Font serif eleganti (Georgia, Times New Roman) che richiamano tradizione e qualità

### Funzionalità
1. **Multilinguaggio IT-EN**: Selettore lingua funzionante in alto a sinistra con cambio istantaneo dei contenuti
2. **Header Sticky**: Logo aziendale nero e titolo della pagina sempre visibili durante lo scroll
3. **Carosello Hero**: 6 immagini dei vigneti Tasca d'Almerita con scorrimento automatico ogni 5 secondi
4. **Navigazione Manuale**: Indicatori cliccabili per navigare tra le immagini del carosello
5. **Pulsante Download**: Link diretto al PDF del Report di Sostenibilità 2024
6. **Sezione B Corp**: Informazioni sulla certificazione B Corp con logo ufficiale
7. **Sezione SOStain**: Dettagli sul disciplinare SOStain con lista dei 10 requisiti e logo
8. **Footer Social**: Link a Facebook, LinkedIn e Instagram con icone SVG
9. **Credits**: Informazioni sul developer e progetto universitario

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
- Selettore lingua multilinguaggio
- Stili header
- Carosello hero
- Contenuto principale
- Pulsante download
- Sezioni informative (B Corp e SOStain)
- Loghi certificazioni
- Lista ordinata SOStain
- Footer con social media
- Media queries responsive
- Animazioni
- Accessibilità

### JavaScript
Sistema multilinguaggio completo con:
- Oggetto translations con tutte le traduzioni IT/EN
- Funzione changeLanguage() per cambio istantaneo della lingua
- Gestione carosello automatico e manuale

## Responsive Breakpoints

- **Mobile**: < 768px (default, mobile-first)
- **Tablet**: ≥ 768px
- **Desktop**: ≥ 1024px

## Colori Brand

```css
--color-primary-brown: #8B6F47    /* Marrone principale */
--color-dark-brown: #6B5333       /* Marrone scuro */
--color-light-brown: #A0826D      /* Marrone chiaro */
--color-cream: #FFF8E7            /* Crema - Background principale */
--color-beige-light: #F5F1E8      /* Beige chiaro */
--color-beige: #EBE4D1            /* Beige medio */
--color-green: #6B8E23            /* Verde oliva */
```

## Link Esterni

### Loghi e Risorse
- **Logo Aziendale**: https://www.tascadalmerita.it/images/svg/Logo.svg
- **Logo B Corp**: https://www.tascadalmerita.it/images/svg/sustainability/bcorp_logo.svg
- **Logo SOStain**: https://www.tascadalmerita.it/images/svg/SostainLogo-color.svg
- **Report PDF**: https://cms.tascadalmerita.it/wp-content/uploads/2025/04/Tasca-SOStain-Report-2024.pdf
- **Immagini Carosello**: 6 immagini ad alta risoluzione dai CDN di Tasca d'Almerita

### Social Media
- **Facebook**: https://www.facebook.com/TascadAlmerita
- **LinkedIn**: https://www.linkedin.com/company/tasca-d-almerita/
- **Instagram**: https://www.instagram.com/tascadalmerita/

## Server Web

Il progetto utilizza un semplice server HTTP Python sulla porta 5000:
```bash
python3 -m http.server 5000
```

## Modifiche Implementate (Update 2)

1. ✅ Background cambiato da beige a crema (#FFF8E7)
2. ✅ Pulsante multilinguaggio IT-EN funzionante in alto a sinistra
3. ✅ Logo B Corp aggiunto nella sezione certificazione
4. ✅ Nuova sezione SOStain con logo e lista dei 10 requisiti
5. ✅ Footer arricchito con icone social (Facebook, LinkedIn, Instagram)
6. ✅ Credits developer: "Giuseppe Saporito Cusimano for UniPegaso - Project Work Laurea in Informatica per le Aziende Digitali, 2025/26"

## Modifiche Future Possibili

- Aggiungere più lingue (FR, DE, ES)
- Implementare gesture di swipe per dispositivi touch sul carosello
- Aggiungere sezioni con highlights del report
- Integrare animazioni on-scroll per elementi
- Aggiungere form di newsletter
- Implementare lazy loading per le immagini

## Data Creazione
11 Novembre 2025

## Ultimo Aggiornamento
11 Novembre 2025 - Aggiunto multilinguaggio, loghi certificazioni, sezione SOStain e social media

## Note Tecniche
- Nessuna dipendenza esterna richiesta
- Compatibile con tutti i browser moderni
- Performance ottimizzate per mobile
- Immagini caricate da CDN esterno
