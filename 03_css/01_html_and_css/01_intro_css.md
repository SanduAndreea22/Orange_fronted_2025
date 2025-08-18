# 🎨 Tufor Descoperă CSS – Introducere

După ce Tufor a stăpânit HTML-ul, s-a apucat de partea vizuală: CSS. Pentru că nu poți avea un jurnal digital fără puțină magie colorată! 🧙‍♂️✨

---

## 📘 1. CSS Overview

CSS (Cascading Style Sheets) este limbajul care îi spune browserului **cum să arate paginile**.

* Poate schimba culori, fonturi, spațieri, poziționări și multe altele.
* CSS lucrează cu HTML: HTML oferă **structura**, CSS oferă **stilul**.

📝 *Gândiți-vă la HTML ca la schelet și CSS ca la hainele pe care le îmbracă Tufor.*

---

## 🔗 2. Linking CSS și HTML

Există mai multe moduri de a folosi CSS într-un proiect HTML:

### a) Inline CSS

```html
<p style="color: red;">Acesta este un paragraf roșu.</p>
```

* Stilul este aplicat direct pe element.
* Nu e recomandat pentru pagini mari, devine greu de gestionat.

### b) Internal CSS

```html
<head>
  <style>
    p { color: blue; font-size: 18px; }
  </style>
</head>
```

* Stilurile sunt în `<style>` în interiorul HTML-ului.
* Bun pentru pagini mici sau teste rapide.

### c) External CSS

```html
<head>
  <link rel="stylesheet" href="stil.css">
</head>
```

* CSS-ul este într-un fișier separat (`stil.css`).
* Cel mai curat și recomandat pentru proiecte mari.

---

## 🖊️ 3. CSS Syntax

CSS are trei componente principale: **selector**, **property**, **value**.

```css
selector {
  property: value;
  property2: value2;
}
```

Exemplu:

```css
h1 {
  color: green;
  font-family: Arial, sans-serif;
}
```

* `h1` = selector (alege elementul HTML)
* `color` și `font-family` = proprietăți
* `green` și `Arial, sans-serif` = valori

---

## 🧩 4. CSS Selectors

Selectorii definesc **ce elemente HTML** vor fi stilizate:

| Selector   | Exemplu                             | Ce selectează                           |
| ---------- | ----------------------------------- | --------------------------------------- |
| Element    | `p { color: red; }`                 | Toate paragrafele `<p>`                 |
| Class      | `.important { font-weight: bold; }` | Toate elementele cu `class="important"` |
| ID         | `#titlu { font-size: 24px; }`       | Elementul cu `id="titlu"`               |
| Descendent | `div p { color: blue; }`            | Toate `<p>` din interiorul unui `<div>` |
| Universal  | `* { margin: 0; }`                  | Toate elementele                        |

---

## ⚖️ 5. Cascading Rules

Cascada în CSS înseamnă **prioritatea stilurilor**:

1. Inline > Internal > External
2. Selectorii mai specifici > mai generali
3. Ultimul stil scris câștigă (dacă selectorul e la fel de specific)

Exemplu:

```html
<p id="paragraf" class="important" style="color: red;">Salut!</p>
```

CSS:

```css
p { color: blue; }
.important { color: green; }
```

Rezultat: textul va fi **roșu** deoarece stilul inline are prioritate maximă.

---

## 🏹 Exerciții pentru studenți

1. **Aplicare CSS Inline**

   * Creează un paragraf cu textul „Salut, CSS!” și colorează-l folosind `style` inline.

2. **Internal CSS**

   * Creează o pagină HTML cu 3 titluri `<h2>` și aplică-le culori diferite folosind `<style>` intern.

3. **External CSS**

   * Creează un fișier `stil.css` și leagă-l de pagina HTML.
   * Aplică culori, fonturi și dimensiuni text pentru titluri și paragrafe.

4. **Selectori**

   * Creează o clasă `.highlight` care colorează textul în galben.
   * Creează un ID `#important` și aplică-i font bold.
   * Testează selectorul descendent pentru a colora toate `<li>` dintr-un `<ul>`.

5. **Cascading Rules**

   * Creează un paragraf cu stil inline, clasa și ID, apoi vezi ce stil câștigă conform regulilor de cascading.
