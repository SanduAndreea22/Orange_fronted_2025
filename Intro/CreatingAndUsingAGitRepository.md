# 🪨 Jurnalul Zilnic al Pietrei lui Tufor: Git-ul Devine Distractiv!

Un ghid amuzant despre cum să creezi și să folosești un repository Git, alături de prietenul tău... o piatră pe nume Rocky. 🪨

---

## 📦 1. Creează un folder pentru proiectul tău de suflet

```bash
mkdir pet-rock-journal
cd pet-rock-journal
```

📝 **Explicație:**  
- `mkdir` creează un folder numit `pet-rock-journal`.  
- `cd` intră în acel folder — acesta va fi sanctuarul digital al lui Rocky.

---

## 🪄 2. Inițializează repository-ul Git

```bash
git init
```

📝 **Explicație:**  
Git începe să urmărească tot ce se întâmplă în folder. Creează un folder invizibil `.git` — e ca o cameră de supraveghere pentru Rocky.

---

## ✍️ 3. Creează fișierul jurnalului lui Rocky

```bash
echo "Day 1: Rocky sat on the windowsill. Very still. Very rocky." > journal.txt
```

📝 **Explicație:**  
- Creezi un fișier `journal.txt` cu prima zi din viața lui Rocky.  
- `>` scrie (sau suprascrie) textul în fișier.

---

## 📌 4. Verifică statusul actual

```bash
git status
```

📝 **Explicație:**  
Git îți spune ce fișiere sunt noi, modificate, sau gata de salvat.

---

## 📥 5. Adaugă jurnalul în „staging area”

```bash
git add journal.txt
```

📝 **Explicație:**  
Pregătești fișierul pentru a fi inclus în următorul commit. Rocky e gata să devină istorie (la propriu).

---

## 📸 6. Fă primul commit din viața pietrei

```bash
git commit -m "Add Day 1 of Rocky's adventures"
```

📝 **Explicație:**  
Salvezi prima versiune oficială a jurnalului. Git ține minte ce ai făcut și de ce. Rocky e acum documentat.

---

## 📖 7. Scrie o nouă zi în jurnal

```bash
echo "Day 2: Rocky rolled off the shelf. Drama!" >> journal.txt
```

📝 **Explicație:**  
- `>>` adaugă text la sfârșitul fișierului. Rocky nu e șters, doar i se adaugă noi aventuri.

---

## 🔍 8. Vezi ce s-a schimbat

```bash
git diff
```

📝 **Explicație:**  
Git îți arată exact ce s-a adăugat în fișier. Poți retrăi suspansul căderii lui Rocky pas cu pas.

---

## 📥 9. Adaugă și salvează iar

```bash
git add journal.txt
git commit -m "Add Day 2: Rocky's thrilling fall"
```

📝 **Explicație:**  
Git înregistrează noi aventuri. Istoria se scrie din nou. Tufor e un arhivist de pietre.

---

## 🕰️ 10. Vezi întreaga epopee

```bash
git log
```

📝 **Explicație:**  
Git îți arată toate commit-urile făcute. E ca un roman istoric al lui Rocky, editat de Tufor.

---

## 🛸 Bonus: Trimite-l pe Rocky în Spațiul GitHub

1. Creează un repository pe GitHub numit `pet-rock-journal`.
2. Conectează-l local:

```bash
git remote add origin https://github.com/username/pet-rock-journal.git
git branch -M main
git push -u origin main
```

📝 **Explicație:**  
- `remote add origin` leagă folderul tău local de GitHub.  
- `branch -M main` setează ramura principală.  
- `push` trimite jurnalul lui Rocky pe internet, ca să poată deveni celebru.

---

## 🎉 Gata!

Tufor a reușit! Rocky are acum un jurnal digital, gestionat profesionist cu Git și găzduit în gloria eternă a GitHub-ului. 🪨🚀

Ai învățat să:

- creezi un repository Git,
- faci commit-uri cu mesaje clare,
- gestionezi modificările,
- publici proiectul tău pe GitHub.

Rocky și Tufor îți spun: „Spor la versionat!” 🎩

