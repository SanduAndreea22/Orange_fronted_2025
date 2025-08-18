
# 🌐 HTML – Ghidul lui Tufor – Partea 3

## `<div>`, `<span>` și tag-uri semantice

### 🔹 `<div>`
- Reprezintă o **diviziune** sau o secțiune într-o pagină HTML.
- Este un container **block-level** (ocupa tot rândul).
- Util pentru structurarea conținutului și aplicarea stilurilor CSS.

**Exemplu:**
```html
<div style="background-color: lightblue; padding: 10px;">
    <h2>Titlu secțiune</h2>
    <p>Acesta este un paragraf într-un div.</p>
</div>
```

### 🔹 `<span>`
- Este un container **inline** (nu trece pe rând nou).
- Folosit pentru a aplica stiluri pe o porțiune de text.

**Exemplu:**
```html
<p>Acesta este un text <span style="color: red;">important</span> în propoziție.</p>
```

### 🔹 Tag-uri semantice
HTML5 a introdus tag-uri cu **semnificație** clară:
- `<header>` – antetul paginii sau al unei secțiuni
- `<nav>` – zona de navigare
- `<main>` – conținutul principal
- `<section>` – secțiune distinctă de conținut
- `<article>` – articol independent
- `<aside>` – conținut secundar (ex. reclame, notițe)
- `<footer>` – subsolul paginii

**Exemplu:**
```html
<header>
    <h1>Blogul lui Tufor</h1>
</header>
<nav>
    <a href="#">Acasă</a> | <a href="#">Articole</a>
</nav>
<main>
    <article>
        <h2>Primul articol</h2>
        <p>Conținutul articolului...</p>
    </article>
</main>
<footer>
    <p>&copy; 2025 Tufor</p>
</footer>
```

---

## Elemente de Formulare

Formularele sunt folosite pentru a colecta date de la utilizatori.

### 🔹 Structura de bază
```html
<form action="procesare.php" method="post">
    <!-- Elemente de input aici -->
</form>
```
- **`action`** – adresa către care se trimit datele
- **`method`** – metoda de trimitere (`GET` sau `POST`)

### 🔹 Tipuri de input
```html
<form>
    Nume: <input type="text" name="nume"><br><br>
    Parolă: <input type="password" name="parola"><br><br>
    Email: <input type="email" name="email"><br><br>
    Data nașterii: <input type="date" name="data"><br><br>
    Selectare fișier: <input type="file" name="fisier"><br><br>
    <input type="submit" value="Trimite">
</form>
```

### 🔹 Alte elemente utile
- `<textarea>` – pentru text pe mai multe rânduri
- `<select>` și `<option>` – liste derulante
- `<input type="radio">` – butoane radio
- `<input type="checkbox">` – bife multiple
- `<button>` – buton personalizat

**Exemplu complet:**
```html
<form action="send.php" method="post">
    <label for="nume">Nume:</label>
    <input type="text" id="nume" name="nume"><br><br>

    <label>Gen:</label>
    <input type="radio" name="gen" value="M"> Masculin
    <input type="radio" name="gen" value="F"> Feminin<br><br>

    <label>Hobby-uri:</label>
    <input type="checkbox" name="hobby" value="sport"> Sport
    <input type="checkbox" name="hobby" value="muzica"> Muzică<br><br>

    <label for="tara">Țara:</label>
    <select id="tara" name="tara">
        <option value="ro">România</option>
        <option value="it">Italia</option>
        <option value="es">Spania</option>
    </select><br><br>

    <label for="mesaj">Mesaj:</label><br>
    <textarea id="mesaj" name="mesaj" rows="4" cols="40"></textarea><br><br>

    <button type="submit">Trimite</button>
</form>
```

---

