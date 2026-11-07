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
| **Szolgáltatások** | Fürdetés, generál (trimmelés/ollózás, nyírás), prémium/show generál, karomvágás, fogápolás |
| **Előtte–utána** | Húzható összehasonlító csúszka három kutyával |
| **Árlista** | Átlagárak termet szerint (kistestű / közepes / nagytestű), részletes árlista fajták szerint |
| **Csapat** | Az 5 munkatárs portréja és bemutatkozása |
| **Pénzügyi terv** | Éves összesítők, havi bevétel–költség oszlopdiagram, kiadás-megoszlás tortadiagram, havi eredmény, induló költségek |
| **Dokumentumok** | Letölthető cégbemutató (Word) és pénzügyi terv (Excel), link a prezentációhoz és az elégedettségi űrlaphoz |
| **Kapcsolat** | Cím, telefon, e-mail, nyitvatartás, térkép, időpontkérő űrlap |

## Funkciók

- **Reszponzív kialakítás** – telefonon lenyíló menüvel, érintéssel húzható csúszkával
- **Világos és sötét mód** – a rendszerbeállítást követi, kézzel is váltható
- **Időpontkérő űrlap** – a kitöltött adatokból kész e-mailt állít össze a látogató levelezőprogramjában
- **Interaktív grafikonok** – a pénzügyi terv Excel-munkafüzet adataiból
- **Egyetlen fájl** – a képek és a dokumentumok az `index.html`-be vannak ágyazva, nincs szükség külön mappákra
- **Akadálymentesség** – billentyűzettel is kezelhető, látható fókusz, képleírások (alt szövegek)

## Felhasznált technológiák

- **HTML5, CSS3, JavaScript** (keretrendszer nélkül)
- [Chart.js](https://www.chartjs.org/) – grafikonok
- [Google Fonts](https://fonts.google.com/) – Fredoka és Figtree betűtípusok
- [GitHub Pages](https://pages.github.com/) – ingyenes tárhely

## Szerkesztés

Az `index.html` alján, a `<script>` rész elején található a prezentáció és az űrlap linkje:

```js
const LINKS = {
  prezentacio: "",   // a PowerPoint megosztási linkje (pl. OneDrive)
  urlap: ""          // az elégedettségi űrlap linkje (Google / MS Forms)
};
```

Ha egy link üres, a hozzá tartozó gomb „Hamarosan” felirattal jelenik meg.

## Frissítés GitHubon

1. Szerkeszd és mentsd el az `index.html`-t (a fájlnév pontosan ez legyen).
2. A repóban válaszd az **Add file → Upload files** menüt, húzd be a fájlt, majd kattints a **Commit changes** gombra.
3. 1–2 perc múlva frissül az élő oldal. Ha a régit látod, frissítsd a böngészőt, vagy nyisd meg inkognitó ablakban.

## Csapat

| Név | Szerepkör |
|---|---|
| *Karban Csaba Ferenc* | Projektmenedzser, fejlesztő |
| *Fazekas András Levente* | Fejlesztő |
| *Madarász Levente* | Fejlesztő |
| *Márton-Szűcs Albert* | Fejlesztő |

## Források

- A Tappancs kutyakozmetika projektcsapata: *Cégbemutató dokumentum* és *Pénzügyi terv* (Excel-munkafüzet), belső projektdokumentumok.
- A logó, a szalonról készült képek, a csapatkép, a portrék és a szolgáltatásokat bemutató képek **AI-generált illusztrációk**.
- Térkép: Google Maps, Budapest XI. kerület, Fejér Lipót utca környéke.

---

© 2026 Tappancs kutyakozmetika projektcsapat. Oktatási célra készült.
