# 🌐 HTML – Partea II – Caractere speciale, Liste și Tabele

După ce Tufor a stăpânit bazele HTML, a aflat că mai există elemente esențiale pentru o pagină web: **caractere speciale**, **liste** și **tabele**.

---

## ✅ 1. Caractere speciale HTML

Uneori, în HTML nu putem folosi direct anumite caractere (precum `<`, `>`, `&`) deoarece acestea au semnificație în cod.  
Pentru a afișa aceste simboluri, folosim **entități HTML**.

### Exemple frecvente:

| Simbol | Cod HTML | Descriere |
|--------|----------|-----------|
| `<`    | `&lt;`   | Semnul mai mic |
| `>`    | `&gt;`   | Semnul mai mare |
| `&`    | `&amp;`  | Ampersand |
| `©`    | `&copy;` | Simbol copyright |
| `®`    | `&reg;`  | Simbol înregistrat |
| `€`    | `&euro;` | Simbol euro |

**Exemplu în cod:**

```html
<p>5 &lt; 10 și 10 &gt; 5</p>
<p>&copy; 2025 Aventurile lui Tufor</p>
```

---

## ✅ 2. Liste în HTML

Listele sunt de două tipuri principale: **ordonate** (cu numere) și **neordonate** (cu buline).

### 2.1 Liste neordonate (`<ul>`)

```html
<ul>
  <li>Mere</li>
  <li>Pere</li>
  <li>Banane</li>
</ul>
```

**Explicație:**  
- `<ul>` – listă neordonată.  
- `<li>` – fiecare element din listă.

### 2.2 Liste ordonate (`<ol>`)

```html
<ol>
  <li>Deschide editorul</li>
  <li>Scrie codul</li>
  <li>Salvează fișierul</li>
</ol>
```

**Explicație:**  
- `<ol>` – listă ordonată (numerotată automat).

### 2.3 Liste imbricate (nested)

```html
<ul>
  <li>Fructe
    <ul>
      <li>Mere</li>
      <li>Pere</li>
    </ul>
  </li>
  <li>Legume</li>
</ul>
```

---

## ✅ 3. Tabele în HTML

Tufor a descoperit cum să aranjeze datele într-un **tabel**.

### Structura de bază:

```html
<table border="1">
  <tr>
    <th>Nume</th>
    <th>Vârstă</th>
  </tr>
  <tr>
    <td>Tufor</td>
    <td>25</td>
  </tr>
  <tr>
    <td>Alex</td>
    <td>22</td>
  </tr>
</table>
```

**Explicație:**  
- `<table>` – definește tabelul.  
- `<tr>` – un rând din tabel.  
- `<th>` – celulă de antet (bold, centrat).  
- `<td>` – celulă normală.

### Tabel cu rânduri și coloane unite:

```html
<table border="1">
  <tr>
    <th rowspan="2">Nume</th>
    <th colspan="2">Note</th>
  </tr>
  <tr>
    <th>Matematică</th>
    <th>Informatică</th>
  </tr>
  <tr>
    <td>Tufor</td>
    <td>10</td>
    <td>9</td>
  </tr>
</table>
```

**Atribute speciale:**  
- `rowspan="n"` – unește celule pe verticală (n rânduri).  
- `colspan="n"` – unește celule pe orizontală (n coloane).

---

# 📜 Exemple complete

### Exemplul 1 – Pagina cu caractere speciale

```html
<!DOCTYPE html>
<html lang="ro">
<head>
  <meta charset="UTF-8">
  <title>Caractere speciale</title>
</head>
<body>
  <p>5 &lt; 10 &amp;&amp; 10 &gt; 5</p>
  <p>&copy; 2025 Aventurile lui Tufor</p>
</body>
</html>
```

### Exemplul 2 – Listă de cumpărături

```html
<ul>
  <li>Pâine</li>
  <li>Lapte</li>
  <li>Ouă</li>
</ul>
```

### Exemplul 3 – Tabel de elevi

```html
<table border="1">
  <tr>
    <th>Nume</th>
    <th>Clasă</th>
    <th>Vârstă</th>
  </tr>
  <tr>
    <td>Tufor</td>
    <td>12A</td>
    <td>18</td>
  </tr>
  <tr>
    <td>Maria</td>
    <td>11B</td>
    <td>17</td>
  </tr>
</table>
```
