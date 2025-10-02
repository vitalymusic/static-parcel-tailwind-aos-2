# Static Parcel Tailwind AOS

Šis ir vienkāršs **statiskas mājaslapas šablons**, kas izmanto:
- [Parcel](https://parceljs.org/) bundleri
- [TailwindCSS](https://tailwindcss.com/) stilizācijai
- [AOS (Animate On Scroll)](https://michalsnik.github.io/aos/) animācijām

---

## 🚀 Uzstādīšana un palaišana

1. Klonē repozitoriju vai atarhivē `.zip` failu:
   
   cd static-parcel-tailwind-aos
   

2. Instalē atkarības:
  
   npm install
   

3. Palaid izstrādes serveri:
   
   npm run dev
   
   Lapa būs pieejama: [http://localhost:1234](http://localhost:1234)

4. Veido produkcijas build:
   
   npm run build
   
   Optimizētie faili būs `dist/` mapē.

---

## 📂 Projekta struktūra


static-parcel-tailwind-aos/
 ├─ src/
 │   ├─ index.html      # Galvenais HTML fails
 │   ├─ style.css       # Tailwind + custom CSS
 │   └─ script.js       # JS ar AOS inicializāciju
 ├─ package.json        # Projekta konfigurācija un skripti
 ├─ tailwind.config.js  # Tailwind konfigurācija
 └─ .gitignore          # Ignorē node_modules, dist, cache u.c.


---

## ✨ Funkcijas

- 🚀 Live reloading ar Parcel
- 🎨 Stilizācija ar TailwindCSS
- 🪄 Animācijas ar AOS
- 📦 Gatavs publicēšanai ar `npm run build`


## 📜 Licence

Brīvi izmanto, pārveido un adaptē saviem projektiem ✌️
