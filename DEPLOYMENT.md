# Deployment Guide

*[English](#english) | [Italiano](#italiano)*

---

## English

### Quick GitHub Pages Deployment

1. **Create a new repository** on GitHub
2. **Upload these files**:
   - `index.html` (the main application)
   - `README.md`
   - `LICENSE`
   - `_config.yml`
   - `.gitignore`

3. **Enable GitHub Pages**:
   - Go to repository Settings
   - Scroll to "Pages" section
   - Select "Deploy from a branch"
   - Choose "main" branch and "/ (root)" folder
   - Click "Save"

4. **Access your site**: Your converter will be available at `https://yourusername.github.io/repository-name`

### Alternative Hosting Options

#### Netlify
1. Connect your GitHub repository to Netlify
2. Deploy automatically on each commit
3. Custom domain support available

#### Vercel
1. Import your GitHub repository
2. Automatic deployments
3. Great performance optimization

#### GitHub Codespaces
1. Perfect for development and testing
2. Instant setup with all tools ready

### File Structure
```
kindle-screensaver-converter/
├── index.html          # Main application
├── README.md          # Documentation
├── LICENSE            # MIT License
├── _config.yml        # GitHub Pages config
├── .gitignore         # Git ignore rules
└── DEPLOYMENT.md      # This file
```

### Browser Compatibility
- ✅ Chrome 60+
- ✅ Firefox 55+
- ✅ Safari 12+
- ✅ Edge 79+
- ✅ Mobile browsers (iOS Safari, Android Chrome)

---

## Italiano

### Deployment Rapido con GitHub Pages

1. **Crea un nuovo repository** su GitHub
2. **Carica questi file**:
   - `index.html` (l'applicazione principale)
   - `README.md`
   - `LICENSE`
   - `_config.yml`
   - `.gitignore`

3. **Abilita GitHub Pages**:
   - Vai nelle Impostazioni del repository
   - Scorri fino alla sezione "Pages"
   - Seleziona "Deploy from a branch"
   - Scegli il branch "main" e la cartella "/ (root)"
   - Clicca "Save"

4. **Accedi al sito**: Il convertitore sarà disponibile su `https://tuousername.github.io/nome-repository`

### Opzioni di Hosting Alternative

#### Netlify
1. Connetti il repository GitHub a Netlify
2. Deploy automatico ad ogni commit
3. Supporto domini personalizzati disponibile

#### Vercel
1. Importa il repository GitHub
2. Deployment automatici
3. Ottima ottimizzazione delle performance

#### GitHub Codespaces
1. Perfetto per sviluppo e test
2. Setup istantaneo con tutti gli strumenti pronti

### Struttura File
```
kindle-screensaver-converter/
├── index.html          # Applicazione principale
├── README.md          # Documentazione
├── LICENSE            # Licenza MIT
├── _config.yml        # Config GitHub Pages
├── .gitignore         # Regole ignore Git
└── DEPLOYMENT.md      # Questo file
```

### Compatibilità Browser
- ✅ Chrome 60+
- ✅ Firefox 55+
- ✅ Safari 12+
- ✅ Edge 79+
- ✅ Browser mobile (iOS Safari, Android Chrome)