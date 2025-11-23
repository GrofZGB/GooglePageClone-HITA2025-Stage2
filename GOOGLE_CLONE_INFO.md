# Google.com Klon - Samo HTML i CSS

## 🎨 Što sam napravio:

Potpuni klon Google.com homepage stranice koristeći **isključivo HTML i CSS** (bez JavaScript-a)!

---

## ✨ Features:

### 1. **Header (Gornji dio)**
- Gmail i Images linkovi
- Apps ikona (grid ikona)
- "Sign in" button - plavi, zaobljen

### 2. **Google Logo**
- Stiliziran tekst sa Google bojama:
  - **G** - Plava (#4285F4)
  - **o** - Crvena (#EA4335)
  - **o** - Žuta (#FBBC05)
  - **g** - Plava (#4285F4)
  - **l** - Zelena (#34A853)
  - **e** - Crvena (#EA4335)

### 3. **Search Box**
- Search ikona (lupa)
- Input polje
- Voice search ikona (mikrofon)
- Google Lens ikona (camera)
- Box shadow i hover efekti

### 4. **Buttons**
- "Google Search" button
- "I'm Feeling Lucky" button
- Hover efekti

### 5. **Language Links**
- "Google offered in: hrvatski English"

### 6. **Footer**
- Lokacija (Croatia)
- Lijevi linkovi: About, Advertising, Business, How Search works
- Desni linkovi: Privacy, Terms, Settings

---

## 🎨 CSS Tehnike korištene:

1. **Flexbox Layout**
   - Za header, main content, footer
   - Centriranje elemenata

2. **Box Shadow**
   - Search box ima shadow za dubinu
   - Hover efekti

3. **SVG Icons**
   - Search, voice, camera, apps ikone
   - Inline SVG za bolje performanse

4. **Google Fonts Style**
   - Arial font family (kao Google)

5. **Responsive Design**
   - Media queries za mobile
   - Flexbox wrap

6. **Hover Effects**
   - Svi linkovi i buttoni
   - Box shadows na hover

7. **Custom Colors**
   - Točne Google boje
   - Footer siva boja

---

## 📱 Responsive:

- Desktop - full width
- Mobile - prilagođen layout
- Footer se slaže vertikalno na malim ekranima

---

## 🔍 CSS Detalji:

### Flexbox Centering:
```css
main {
    flex: 1;
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
}
```

### Search Box Shadow:
```css
.search-box {
    box-shadow: 0 1px 6px rgba(32, 33, 36, 0.28);
}
```

### Button Hover:
```css
.google-btn:hover {
    box-shadow: 0 1px 1px rgba(0, 0, 0, 0.1);
    border: 1px solid #dadce0;
}
```

---

## 🎯 Što radi:

✅ Izgleda kao pravi Google.com  
✅ Svi hover efekti  
✅ Responsive design  
✅ Čiste, točne boje  
✅ SVG ikone  
✅ Footer sa linkovima  
✅ **BEZ JavaScript-a!**

---

## 📝 Napomena:

- Input polje ne radi pretragu (nema JS)
- Linkovi vode na # (dummy linkovi)
- Voice i camera ikone ne rade (nema JS)
- Ali VIZUALNO je identičan Google.com!

---

## 🚀 Deployment:

1. Preuzmi `google-clone.html`
2. Otvori u browseru
3. Ili deploya na Netlify: https://app.netlify.com/drop

---

## 💡 Naučeno:

- Kako napraviti moderan UI sa samo CSS-om
- Flexbox za complex layoute
- SVG ikone inline u HTML-u
- Box shadows za dubinu
- Hover efekti
- Google design system

**Perfektna vježba za HTML i CSS! 🎨**
