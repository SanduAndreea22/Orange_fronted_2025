# 🎨 Aventurile lui Tufor -- Introducere în HTML & CSS

După ce Tufor a cucerit bazele HTML, a descoperit o lume și mai colorată
-- **CSS**. Dar înainte de a se arunca în bătăliile stilurilor, el a mai
întâlnit câteva unelte importante ale lumii web.

------------------------------------------------------------------------

## 📝 HTML Forms -- Puterea Interacțiunii

Formularele sunt modul în care utilizatorii pot comunica cu paginile
web. Tufor a aflat că un **formular** colectează date.

### Exemplu simplu:

``` html
<form action="/submit" method="post">
  <label for="name">Nume:</label>
  <input type="text" id="name" name="name">
  <input type="submit" value="Trimite">
</form>
```

📌 **Explicație:** Formularele pot conține câmpuri text, radio,
checkbox-uri, liste și butoane pentru a trimite date.

------------------------------------------------------------------------

## 🪟 HTML IFrames -- Ferestre către alte lumi

Un **iframe** permite includerea unei alte pagini web în pagina curentă.

### Exemplu:

``` html
<iframe src="https://www.wikipedia.org" width="600" height="400"></iframe>
```

📌 **Explicație:** Ca o poartă magică prin care Tufor poate vedea altă
lume fără să plece din pagina sa.

------------------------------------------------------------------------

# 🌈 CSS -- Ce este și de ce e util?

CSS (**Cascading Style Sheets**) este arta decorării paginilor. Dacă
HTML este scheletul, CSS este veșmântul care face totul mai frumos.

Tufor a înțeles că fără CSS, o pagină este ca o carte alb-negru. Cu CSS,
devine o poveste plină de culori și stiluri.

------------------------------------------------------------------------

## 🔗 Linking HTML și CSS

Pentru ca magia să funcționeze, trebuie să legăm CSS-ul de HTML.

### 1. Inline CSS

``` html
<p style="color: red;">Salut de la Tufor!</p>
```

### 2. Internal CSS

``` html
<style>
  p { color: blue; }
</style>
```

### 3. External CSS

``` html
<link rel="stylesheet" href="stil.css">
```

📌 **Explicație:** Cel mai bun mod este fișierul extern -- astfel codul
este curat și reutilizabil.

------------------------------------------------------------------------

## ✍️ CSS Syntax

Tufor a învățat incantația magică a CSS-ului:

``` css
selector {
  proprietate: valoare;
}
```

Exemplu:

``` css
h1 {
  color: green;
  font-size: 24px;
}
```

------------------------------------------------------------------------

## 🎯 CSS Selectors

Tufor a descoperit armele pentru a selecta elemente:

-   **Type selector** → `p {}` selectează toate paragrafele.
-   **Class selector** → `.highlight {}` selectează elementele cu clasa
    respectivă.
-   **ID selector** → `#important {}` selectează elementul cu acel ID.
-   **Combinators** → `ul li {}` selectează elemente într-o structură.
-   **Attribute selector** → `input[type="text"] {}`
-   **Pseudo-classes** → `a:hover {}` pentru hover pe link.
-   **Pseudo-elements** → `p::first-line {}` pentru prima linie dintr-un
    paragraf.

------------------------------------------------------------------------

## ⚖️ Cascading Rules

Aici Tufor a aflat de **ierarhia stilurilor**:

1.  **Importanța** (`!important` câștigă mereu)
2.  **Specificitatea** (ID \> clasă \> element)
3.  **Ordinea sursei** (ultimul scris câștigă dacă e egalitate)

Exemplu:

``` html
<p id="text" class="albastru" style="color: green;">Salut!</p>
```

``` css
p { color: black; }        /* cel mai slab */
.albastru { color: blue; } /* mai puternic */
#text { color: red; }      /* și mai puternic */
```

Dar inline (`style="color: green;"`) are prioritate, iar dacă pui și
`!important`, magia e absolută.

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
