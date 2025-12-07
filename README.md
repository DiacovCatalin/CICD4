# CICD4 - GitHub Pages Project

Acest proiect demonstrează publicarea automată a unui site web static folosind GitHub Pages și GitHub Actions.

## 📋 Descriere

**Proiect:** CICD4  
**Autor:** DiacovCatalin  
**Tehnologii:** HTML5, CSS3, GitHub Actions, GitHub Pages

## 🚀 Funcționalități

- ✅ Site web static responsive
- ✅ Stilizare CSS modernă
- ✅ Publicare automată pe GitHub Pages
- ✅ Workflow CI/CD pentru deployment
- ✅ Badge de status pentru build

## 🌐 Accesare Site

Site-ul este publicat la: **https://DiacovCatalin.github.io/CICD4/**

## 🔧 Structura Proiectului

```
CICD4/
├── index.html              # Pagina principală
├── style.css               # Stilizare CSS
├── README.md               # Documentație
└── .github/workflows/
    └── deploy.yml          # Workflow pentru deployment automat
```

## 📦 Workflow CI/CD

### Trigger
- Rulează automat la fiecare `push` pe branch-ul `main`/`master`
- Rulează la fiecare `pull request` către `main`/`master`

### Proces
1. **Build**: Pregătește fișierele pentru deployment
2. **Deploy**: Publică site-ul pe GitHub Pages

### Badge Status
![Deploy to GitHub Pages](https://github.com/DiacovCatalin/CICD4/workflows/Deploy%20to%20GitHub%20Pages/badge.svg)

## 🎨 Caracteristici Design

- **Design responsiv**: Funcționează pe desktop, tabletă și mobil
- **Gradient modern**: Fundal cu gradient violet-albastru
- **Animții**: Hover effects și tranziții smooth
- **Layout curat**: Container centralizat cu card-uri pentru conținut

## 🛠️ Tehnologii Folosite

- **HTML5**: Structură semantică
- **CSS3**: Stilizare modernă cu flexbox și media queries
- **GitHub Actions**: Automatizare deployment
- **GitHub Pages**: Hosting gratuit pentru site-uri statice

## 📱 Compatibilitate

- ✅ Chrome 60+
- ✅ Firefox 55+
- ✅ Safari 12+
- ✅ Edge 79+
- ✅ Mobile browsers

## 🔄 Proces de Deployment

1. Se face push la modificări în repository
2. GitHub Actions se declanșează automat
3. Site-ul este build-uit și publicat
4. Site-ul devine disponibil în câteva minute

## 📝 Notițe

- Acest proiect folosește cele mai recente versiuni de GitHub Actions
- Workflow-ul este optimizat pentru a evita warning-uri de deprecare
- Site-ul este configurat pentru deployment automat și continuu

---

**Laborator 4 - Publicarea cu GitHub Pages**  
*Creat de DiacovCatalin © 2025*
