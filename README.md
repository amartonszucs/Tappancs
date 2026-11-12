# 🐾 Tappancs kutyakozmetika – promóciós weboldal

Egyoldalas, telefonon és számítógépen is használható promóciós weblap egy kitalált budapesti mikrovállalkozásnak, a **Tappancs kutyakozmetikának**.

**🔗 Élő oldal:** https://amartonszucs.github.io/Tappancs/

> A projekt a **Gábor Dénes Egyetem** *Informatika alapjai* tárgyának csapatmunkában készült projektfeladata (1. témakör: *Mikrovállalkozás digitális arculata és működése*, központi téma: **Kutyakozmetika**). A vállalkozás, a szereplők és az adatok kitaláltak.

---

## Tartalom

Az oldal a projekt mindhárom munkarészét egy helyen mutatja be:

| Szekció | Leírás |
|---|---|
| **Nyitókép** | A szalon portálja, időpontkérés gomb, élő „most nyitva / zárva” kijelzés |
| **Rólunk** | Küldetés, a szalon bemutatása |
| **Szolgáltatások** | Fürdetés, generál (trimmelés/ollózás, nyírás), prémium/show generál, karomvágás és további kiegészítők |
| **Előtte–utána** | Húzható összehasonlító csúszka három kutyával |
| **Árlista** | Átlagárak termet szerint (kistestű / közepes / nagytestű), kiegészítő szolgáltatások árai, részletes árlista fajták szerint |
| **Csapat** | Az 5 munkatárs portréja és bemutatkozása |
| **Pénzügyi terv** | Éves összesítők, havi bevétel–költség oszlopdiagram, kiadás-megoszlás tortadiagram, havi eredmény, induló költségek |
| **Dokumentumok** | Letölthető cégbemutató (Word), pénzügyi terv (Excel) és prezentáció (PowerPoint), link az elégedettségi kérdőívhez (Google Forms) |
| **Kapcsolat** | Cím, telefon, e-mail, nyitvatartás, térkép, időpontkérő űrlap |

## Funkciók

- **Reszponzív kialakítás** – telefonon lenyíló menüvel, érintéssel húzható csúszkával
- **Világos és sötét mód** – a rendszerbeállítást követi, kézzel is váltható
- **Időpontkérő űrlap** – a kitöltött adatokból kész e-mailt állít össze a látogató levelezőprogramjában
- **Interaktív grafikonok** – a pénzügyi terv Excel-munkafüzet adataiból
- **Kevés fájl** – a képek, a Word és az Excel az `index.html`-be vannak ágyazva, csak a prezentáció külön fájl
- **Akadálymentesség** – billentyűzettel is kezelhető, látható fókusz, képleírások (alt szövegek)

## Felhasznált technológiák

- **HTML5, CSS3, JavaScript** (keretrendszer nélkül)
- [Chart.js](https://www.chartjs.org/) – grafikonok
- [Google Fonts](https://fonts.google.com/) – Fredoka és Figtree betűtípusok
- [GitHub Pages](https://pages.github.com/) – ingyenes tárhely

## Fájlok

| Fájl | Tartalom |
|---|---|
| `index.html` | A teljes weboldal, beágyazott képekkel, cégbemutatóval és pénzügyi tervvel |
| `Tappancs_kutyakozmetika_bemutato.pptx` | A prezentáció, amit az oldal Dokumentumok része tölt le |
| `README.md` | Ez a leírás |

## Szerkesztés

Az `index.html` alján, a `<script>` rész elején található a prezentáció és az elégedettségi kérdőív linkje:

```js
const LINKS = {
  prezentacio: "Tappancs_kutyakozmetika_bemutato.pptx",   // a repóban lévő PowerPoint fájl neve
  urlap: "https://docs.google.com/forms/..."              // a Google Forms kérdőív linkje
};
```

Ha a prezentációt lecseréled, az új fájl neve pontosan egyezzen a fenti névvel. Ha egy link üres, a hozzá tartozó gomb „Hamarosan” felirattal jelenik meg.

## Frissítés GitHubon

1. Szerkeszd és mentsd el a módosított fájlt. A fájlnevek pontosan egyezzenek a fenti táblázattal.
2. A repóban válaszd az **Add file → Upload files** menüt, húzd be a fájlt vagy fájlokat, majd kattints a **Commit changes** gombra.
3. 1–2 perc múlva frissül az élő oldal. Ha a régit látod, frissítsd a böngészőt, vagy nyisd meg inkognitó ablakban.

## Csapat

| Név | Szerepkör |
|---|---|
| *[név]* | Projektmenedzser, fejlesztő |
| *[név]* | Fejlesztő |
| *[név]* | Fejlesztő |
| *[név]* | Fejlesztő |

## Források

- A Tappancs kutyakozmetika projektcsapata: *Cégbemutató dokumentum* és *Pénzügyi terv* (Excel-munkafüzet), belső projektdokumentumok.
- A logó, a szalonról készült képek, a csapatkép, a portrék és a szolgáltatásokat bemutató képek **AI-generált illusztrációk**.
- Térkép: Google Maps, Budapest XI. kerület, Fejér Lipót utca környéke.

---

© 2026 Tappancs kutyakozmetika projektcsapat. Oktatási célra készült.
