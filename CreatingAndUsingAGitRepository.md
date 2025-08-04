# 🪨 My Pet Rock’s Daily Journal: Using Git for Fun (cu explicații)

Un exemplu amuzant despre cum să creezi și să folosești un repository Git.

---

## 📦 1. Creează un folder pentru proiect

```bash
mkdir pet-rock-journal
cd pet-rock-journal
```

📝 **Explicație:**  
`mkdir` creează un folder numit `pet-rock-journal`.  
`cd` intră în acel folder — aici vei lucra.

---

## 🪄 2. Inițializează repository-ul Git

```bash
git init
```

📝 **Explicație:**  
Această comandă spune lui Git să înceapă să urmărească schimbările din acest folder. Git va crea un folder ascuns `.git` unde va ține evidența versiunilor.

---

## ✍️ 3. Creează fișierul jurnalului

```bash
echo "Day 1: Rocky sat on the windowsill. Very still. Very rocky." > journal.txt
```

📝 **Explicație:**  
Creezi primul fișier din proiect. Acesta va conține textul jurnalului pentru Ziua 1.  
`>` înseamnă „scrie în fișier” (creează sau suprascrie).

---

## 📌 4. Verifică statusul

```bash
git status
```

📝 **Explicație:**  
Arată ce fișiere noi sau modificate există și ce e gata pentru commit.

---

## 📥 5. Adaugă fișierul în staging

```bash
git add journal.txt
```

📝 **Explicație:**  
Pregătești fișierul pentru a fi inclus în următorul „commit” (salvare).

---

## 📸 6. Fă primul commit

```bash
git commit -m "Add Day 1 of Rocky's adventures"
```

📝 **Explicație:**  
Salvezi fișierul în istoria Git cu un mesaj clar despre ce ai făcut.

---

## 📖 7. Scrie o nouă zi în jurnal

```bash
echo "Day 2: Rocky rolled off the shelf. Drama!" >> journal.txt
```

📝 **Explicație:**  
`>>` adaugă text la finalul fișierului, fără să-l suprascrie.

---

## 🔍 8. Vezi diferențele

```bash
git diff
```

📝 **Explicație:**  
Afișează diferențele dintre fișierul actual și ultima versiune salvată (commit-ul anterior).

---

## 📥 9. Adaugă și comite iar

```bash
git add journal.txt
git commit -m "Add Day 2: Rocky's thrilling fall"
```

📝 **Explicație:**  
Adaugi modificările și le salvezi cu un nou mesaj.

---

## 🕰️ 10. Vezi istoricul

```bash
git log
```

📝 **Explicație:**  
Vezi toate commit-urile făcute până acum, în ordine cronologică inversă.

---

## 🛸 Bonus: Trimite pe GitHub

1. Creează un repo pe GitHub: `pet-rock-journal`
2. Conectează-l:

```bash
git remote add origin https://github.com/username/pet-rock-journal.git
git branch -M main
git push -u origin main
```

📝 **Explicație:**  
- `remote add origin` conectează repo-ul local la unul pe GitHub.  
- `branch -M main` setează ramura principală ca fiind `main`.  
- `push -u origin main` trimite fișierele tale pe GitHub.

---

## 🎉 Gata!

Acum ai un jurnal de aventuri pentru Rocky și ai învățat cum funcționează Git!
