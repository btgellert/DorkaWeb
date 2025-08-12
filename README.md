# @balintdorka.fit - Pilates Oktató Weboldal

Egy modern, reszponzív pilátesz oktató weboldal, amely a @balintdorka.fit márka nevében készült.

## 🎨 Tervezési Jellemzők

- **Színvilág**: Piros és rózsaszín gradiens
- **Design**: Modern, letisztult, professzionális
- **Reszponzivitás**: Mobilbarát, minden eszközön tökéletes
- **Tipográfia**: Playfair Display és Inter betűtípusok

## 📁 Fájlstruktúra

```
├── index.html          # Fő HTML fájl
├── styles.css          # CSS stílusok
├── script.js           # JavaScript funkcionalitás
└── README.md           # Ez a fájl
```

## 🚀 GitHub Pages-re Publikálás

### 1. GitHub Repository Létrehozása

1. Menj a [GitHub.com](https://github.com) oldalra
2. Kattints a "New repository" gombra
3. Nevezd el a repository-t: `balintdorka-fit-website`
4. Válaszd ki a "Public" opciót
5. Kattints a "Create repository" gombra

### 2. Fájlok Feltöltése

#### Opció A: GitHub Webes Felületén

1. A repository oldalán kattints a "uploading an existing file" linkre
2. Húzd be az összes fájlt (index.html, styles.css, script.js)
3. Írj egy commit üzenetet: "Initial website upload"
4. Kattints a "Commit changes" gombra

#### Opció B: Git Parancssorral

```bash
# Klónozd a repository-t
git clone https://github.com/username/balintdorka-fit-website.git

# Másold be a fájlokat
# (másold be az index.html, styles.css, script.js fájlokat)

# Add és commit
git add .
git commit -m "Initial website upload"

# Push
git push origin main
```

### 3. GitHub Pages Aktiválása

1. A repository oldalán menj a "Settings" fülre
2. Bal oldalon kattints a "Pages" linkre
3. "Source" alatt válaszd ki a "Deploy from a branch" opciót
4. "Branch" alatt válaszd ki a "main" branch-et
5. Kattints a "Save" gombra

### 4. Weboldal Elérhetősége

A weboldal a következő címen lesz elérhető:
```
https://username.github.io/balintdorka-fit-website
```

## 🎯 Weboldal Funkciói

### Főbb Szekciók
- **Hero Section**: Üdvözlő képernyő a fő üzenettel
- **Rólam**: Személyes bemutatkozás és tapasztalatok
- **Szolgáltatások**: Egyéni és csoportos órák, házhoz jövő szolgáltatás
- **Órarend**: Jelenlegi órák időpontjaival
- **Kapcsolat**: Űrlap és elérhetőségek

### Interaktív Funkciók
- Reszponzív navigáció
- Smooth scrolling
- Hover effektek
- Mobilbarát menü
- Kapcsolati űrlap validáció

## 🎨 Testreszabás

### Színek Módosítása

A `styles.css` fájlban a `:root` szekcióban módosíthatod a színeket:

```css
:root {
    --primary-red: #e74c3c;      /* Fő piros szín */
    --secondary-red: #c0392b;    /* Másodlagos piros */
    --primary-pink: #e91e63;     /* Fő rózsaszín */
    --secondary-pink: #ad1457;   /* Másodlagos rózsaszín */
    --light-pink: #fce4ec;       /* Világos rózsaszín */
}
```

### Tartalom Módosítása

Az `index.html` fájlban könnyen módosíthatod:
- Személyes adatokat
- Szolgáltatásokat
- Órarendet
- Kapcsolati információkat

## 📱 Reszponzivitás

A weboldal automatikusan alkalmazkodik:
- **Desktop**: Teljes képernyős megjelenítés
- **Tablet**: Köztes méretű elrendezés
- **Mobil**: Egyszerűsített, mobilbarát elrendezés

## 🔧 Technikai Részletek

- **HTML5**: Szemantikus markup
- **CSS3**: Modern CSS funkciók, Grid és Flexbox
- **JavaScript**: ES6+ szintaxis
- **Font Awesome**: Ikonok
- **Google Fonts**: Tipográfia

## 📞 Támogatás

Ha bármilyen kérdésed van a weboldallal kapcsolatban:
- Ellenőrizd a GitHub repository-t
- Nézd meg a commit üzeneteket
- Használd a GitHub Issues funkciót

## 🎉 Köszönet

Köszönjük, hogy a @balintdorka.fit weboldalt választottad! Reméljük, hogy ez segít a pilátesz oktatási üzleted fejlesztésében.

---

**Készítette**: Modern Web Design  
**Verzió**: 1.0  
**Utolsó frissítés**: 2024
