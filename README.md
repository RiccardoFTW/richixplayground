# 🎨 Riccardo x Playground - Portfolio 2025

Un portfolio interattivo moderno sviluppato con **Astro** e **GSAP**, che combina design pulito con animazioni fluide per presentare progetti di frontend development e design digitale.

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https://github.com/riccardoventura/rxplayground)
[![Live Demo](https://img.shields.io/badge/Live-Demo-blue)](https://richixplayground.vercel.app)

## ✨ Features

- 🎬 **Animazioni GSAP avanzate** - Loading sequence e transizioni fluide
- 🎯 **Cursore personalizzato** - Interactive cursor con effetti dinamici (solo desktop)
- 📱 **Fully Responsive** - Design ottimizzato per ogni dispositivo
- ⚡ **Performance ottimizzate** - Built con Astro per velocità massima
- 🎨 **Design moderno** - Layout pulito ispirato ai migliori portfolio contemporanei
- 📊 **Analytics integrato** - Vercel Analytics per tracking delle visite
- 🔗 **Hover effects** - Animazioni smooth sui link con effetti slide

## 🛠️ Tech Stack

- **Framework**: [Astro](https://astro.build/) - Generatore di siti statici ultra-veloce
- **Animazioni**: [GSAP](https://greensock.com/gsap/) - Libreria di animazioni professionali
- **Font**: Neue Montreal - Typography moderna e pulita
- **Deployment**: [Vercel](https://vercel.com/) - Hosting con deploy automatici
- **Analytics**: Vercel Analytics - Tracking delle performance e visite

## 🚀 Quick Start

### Prerequisiti

- Node.js 18+
- npm o yarn

### Installazione

```bash
# Clona la repository
git clone https://github.com/riccardoventura/rxplayground.git

# Entra nella directory
cd rxplayground

# Installa le dipendenze
npm install

# Avvia il server di sviluppo
npm run dev
```

Il sito sarà disponibile su `http://localhost:4321`

### Comandi disponibili

| Comando           | Descrizione                 |
| ----------------- | --------------------------- |
| `npm run dev`     | Avvia il server di sviluppo |
| `npm run build`   | Build per produzione        |
| `npm run preview` | Preview del build locale    |

## 📁 Struttura del progetto

```
rxplayground/
├── public/
│   ├── font/              # Font personalizzati
│   └── favicon.svg        # Favicon del sito
├── src/
│   └── pages/
│       └── index.astro    # Pagina principale (SPA)
├── package.json           # Dipendenze e scripts
└── astro.config.mjs       # Configurazione Astro
```

## 🎨 Design System

### Colori

- **Primary**: `#0000ee` (Blue)
- **Secondary**: `#000000` (Black)
- **Tertiary**: `#959595` (Gray)
- **Background**: `#0000ee` (Blue)
- **Text**: `#ffffff` (White)

### Tipografia

- **Font Family**: Neue Montreal
- **Responsive scaling**: Da 9rem (desktop) a 2.5rem (mobile)

## 📱 Features Responsive

- **Desktop**: Cursore personalizzato, hover effects, layout completo
- **Tablet** (≤768px): Layout ottimizzato, hover disabilitato
- **Mobile** (≤480px): Typography ridotta, spacing compatto

## 🎬 Animazioni

### Loading Sequence

1. Testo animato che appare in sequenza
2. Smile finale con delay
3. Fade out del loading
4. Fade in della hero section

### Hero Animations

- Header slide from top
- Title/subtitle fade in from bottom
- Sidebar slide from left/right
- Footer fade in
- Cursor reveal (desktop only)

## 🔧 Personalizzazione

### Cambiare i contenuti

Modifica il file `src/pages/index.astro`:

- **Progetti**: Sezione LAB (sidebar sinistra)
- **Skills**: Sidebar destra
- **Links social**: Footer
- **Info personali**: Header e main content

### Cambiare i colori

Modifica le CSS custom properties in `:root`:

```css
:root {
  --background-color: #0000ee;
  --primary-color: #fff;
  --secondary-color: #000;
  --tertiary-color: #959595;
}
```

## 📊 Analytics

Il portfolio include Vercel Analytics per monitorare:

- Numero di visite
- Paesi di provenienza
- Dispositivi utilizzati
- Performance del sito

Dati visibili nella dashboard Vercel del progetto.

## 🚀 Deploy

### Deploy automatico su Vercel

1. Fai push delle modifiche su GitHub
2. Vercel rileva automaticamente i cambiamenti
3. Build e deploy automatici in ~2 minuti

### Deploy manuale

```bash
# Build del progetto
npm run build

# Preview locale
npm run preview
```

## 📝 Prossimi sviluppi

- [ ] Sezione progetti dettagliata
- [ ] Blog integrato
- [ ] Dark/Light mode toggle
- [ ] Animazioni scroll-triggered
- [ ] Ottimizzazioni SEO avanzate

## 🤝 Contribuzioni

Questo è un portfolio personale, ma feedback e suggerimenti sono sempre benvenuti!

## 📄 Licenza

Questo progetto è sotto licenza MIT. Vedi il file `LICENSE` per maggiori dettagli.

## 📧 Contatti

- **Portfolio**: [richixplayground.vercel.app](https://richixplayground.vercel.app)
- **Email**: r.ventura.dev@gmail.com
- **GitHub**: [@riccardoventura](https://github.com/riccardoventura)
- **LinkedIn**: [Riccardo Ventura](https://linkedin.com/in/riccardo-ventura)

---

⭐ Se ti piace questo progetto, lascia una stella su GitHub!
