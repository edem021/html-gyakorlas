# HTML gyakorló vizsgafeladatok

Ezek a feladatok egyszerű HTML/CSS alapismereteket néznek. Old meg őket egy saját `megoldas.html` (és ha kell, `megoldas.css`) fájlban, vagy bővítsd ezt a projektet.

---

## Feladat 1 – Alapstruktúra

Készíts egy érvényes HTML5 oldalt a következőkkel:

- `<!DOCTYPE html>` és helyes nyitó/záró `html`, `head`, `body` elemek
- A `head`-ben legyen **oldalcím** (`<title>`), pl. „Gyakorló vizsga”
- A `body`-ban legyen legalább egy **címsor** (`<h1>`) és két **bekezdés** (`<p>`)

**Ellenőrzés:** Az oldal böngészőben megnyitva látszik a cím a fülön, és a tartalom rendezett.

---

## Feladat 2 – Lista

A bekezdések után adj hozzá:

- egy **számozatlan listát** (`<ul>` + `<li>`), legalább 3 elemmel (pl. kedvenc tantárgyak)
- alatta egy **számozott listát** (`<ol>` + `<li>`), legalább 3 lépéssel (pl. „Hogyan készülök vizsgára”)

---

## Feladat 3 – Hivatkozás és kép

- Tegyél be egy **linket** (`<a href="...">`), ami egy külső oldalra mutat (pl. Wikipédia vagy egy iskolai honlap), és nyisson **új lapon** (`target="_blank"` + `rel="noopener noreferrer"`).
- Illessz be egy **képet** (`<img>`) helyes `src`, `alt` és (opcionálisan) `width` attribútumokkal. Használhatsz ingyenes placeholder képet is, pl. `https://picsum.photos/400/200`

---

## Feladat 4 – Táblázat

Készíts egy **egyszerű táblázatot** (`<table>`, `<tr>`, `<th>` / `<td>`):

- legalább 2 oszlopfejléc és 3 adatsor
- téma szabadon választható (pl. órarend, filmek, sport eredmények)

Használj fejléc cellákat (`<th>`) az első sorban.

---

## Feladat 5 – Stílus (CSS)

Készíts vagy kapcsolj be egy **külön CSS fájlt** (`<link rel="stylesheet" href="...">`), és:

- állíts be **háttérszínt** a `body`-nak
- a főcímnek (`h1`) legyen más **színe** és nagyobb **betűmérete**, mint az alapértelmezettnek
- a táblázatnak legyen **szegélye** (`border` a `table`-en vagy cellákon) és legyen **középre igazítva** (`margin: 0 auto` + megfelelő szélesség), vagy használj egyszerű `text-align: center` a szülő elemre

---

## Tippek

- Validáld az oldalt: [W3C Markup Validation Service](https://validator.w3.org/) (opcionális, de hasznos).
- Minden képnél legyen értelmes `alt` szöveg.
- A fájlok UTF-8 kódolásúak legyenek, magyar ékezetekhez is.

Sok sikert a gyakorláshoz.
