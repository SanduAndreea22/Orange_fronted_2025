
# 🌐 HTML – Ghidul Detaliat al lui Tufor

Tufor a pășit pentru prima dată în Ținutul Web-ului și a descoperit că limbajul magic ce dă viață paginilor se numește **HTML** – HyperText Markup Language.  
Acest ghid îl va învăța tot ce trebuie să știe pentru a construi primele pagini.

---

## ✅ 1. Structura de Bază a unei Pagini HTML

Orice pagină HTML începe cu o structură fixă – ca fundația unui castel.

```html
<!DOCTYPE html>
<html lang="ro">
<head>
  <meta charset="UTF-8">
  <title>Prima pagină a lui Tufor</title>
</head>
<body>
  <h1>Bun venit!</h1>
  <p>Aceasta este prima mea aventură HTML.</p>
</body>
</html>
```

**Explicații:**
- `<!DOCTYPE html>` – Spune browserului că folosim HTML5.
- `<html lang="ro">` – Marchează începutul paginii și limba conținutului.
- `<head>` – Conține informații despre pagină (titlu, meta date, legături la CSS sau JS).
- `<title>` – Textul din bara de titlu a browserului.
- `<body>` – Conținutul vizibil al paginii.

---

## ✅ 2. Titlurile – `<h1>` până la `<h6>`

Titlurile structurează textul pe nivele de importanță.

```html
<h1>Regatul HTML</h1>
<h2>Capitolul I – Primii pași</h2>
<h3>Subcapitol</h3>
```

**Explicații:**
- `<h1>` – Titlul principal, unic pe pagină.
- `<h2>` – Subtitluri importante.
- `<h3>`…`<h6>` – Subsecțiuni cu importanță mai mică.

---

## ✅ 3. Paragrafe – `<p>`

```html
<p>Tufor își începe aventura învățând HTML.</p>
<p>El descoperă cum să folosească tag-uri și atribute.</p>
```

**Explicație:**  
Tag-ul `<p>` definește paragrafe de text. Browserul adaugă automat spațiu între ele.

---

## ✅ 4. Imagini – `<img>`

```html
<img src="tufor.jpg" alt="Portretul lui Tufor" width="300">
```

**Explicații:**
- `src` – Calea către imagine.
- `alt` – Text alternativ (pentru accesibilitate și SEO).
- `width` – Lățimea în pixeli.

---

## ✅ 5. Linkuri – `<a>`

```html
<a href="https://www.google.com" target="_blank">Caută pe Google</a>
<a href="contact.html">Mergi la pagina de contact</a>
```

**Explicații:**
- `href` – Adresa resursei.
- `target="_blank"` – Deschide linkul într-o filă nouă.
- Textul dintre `<a>` și `</a>` este cel clicabil.

---

## ✅ 6. Comentarii – `<!-- ... -->`

```html
<!-- Acesta este un comentariu și nu apare pe pagină -->
```

**Explicație:**  
Comentariile sunt utile pentru a lăsa note în cod fără să fie afișate.

---

# 📜 Exemple Complete

### Exemplul 1 – Pagină simplă

```html
<!DOCTYPE html>
<html lang="ro">
<head>
  <meta charset="UTF-8">
  <title>Salutare</title>
</head>
<body>
  <h1>Bine ai venit pe pagina lui Tufor!</h1>
  <p>Aici începe aventura.</p>
</body>
</html>
```

### Exemplul 2 – Pagină cu imagine și link

```html
<!DOCTYPE html>
<html lang="ro">
<head>
  <meta charset="UTF-8">
  <title>Galeria lui Tufor</title>
</head>
<body>
  <h1>Castelul HTML</h1>
  <img src="castel.jpg" alt="Castel medieval" width="400">
  <p>Vizitează mai multe imagini pe <a href="https://unsplash.com" target="_blank">Unsplash</a>.</p>
</body>
</html>
```

---

# 🏹 Exerciții pentru Studenți

1. **Prima pagină HTML**
   - Creează un fișier `index.html` cu titlul „Pagina mea”.
   - Adaugă un `<h1>` și un paragraf.

2. **Structurare cu titluri**
   - Folosește `<h1>`, `<h2>` și `<h3>` pentru a organiza un text despre un hobby.

3. **Inserare imagine**
   - Adaugă o imagine locală și setează atributul `alt`.

4. **Creare linkuri**
   - Fă un link către Google și unul către un alt fișier HTML.

5. **Mini-proiect**
   - Realizează o pagină cu:
     - 1 titlu principal
     - 2 subtitluri
     - 2 paragrafe
     - 1 imagine
     - 2 linkuri (intern și extern)

---

## 🎯 Concluzie

Cu aceste elemente, Tufor poate construi deja pagini HTML funcționale. În curând va descoperi CSS și JavaScript pentru a adăuga stil și interactivitate!
