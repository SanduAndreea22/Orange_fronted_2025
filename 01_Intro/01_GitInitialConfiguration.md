
# 🛠️ Configurarea Inițială Git – Ghidul lui Tufor

După ce Tufor a instalat Git, a aflat că trebuie să-și prezinte identitatea digitală. Git nu e o magie completă fără un strop de personalizare! 🎩

---

## ✅ 1. Setează-ți numele (ca un cavaler al commit-urilor)

```bash
git config --global user.name "Tufor Cel Gituit"
```

📝 **Explicație:**  
Acesta este numele care va apărea în toate commit-urile tale. Git trebuie să știe cine e eroul din spatele codului!

---

## ✅ 2. Setează-ți emailul (pentru legătura cu GitHub)

```bash
git config --global user.email "tufor@example.com"
```

📝 **Explicație:**  
Adresa de email ajută GitHub (sau alte platforme) să asocieze commit-urile tale cu contul tău.

---

## ✅ 3. Verifică-ți identitatea (nu-i nicio rușine)

```bash
git config --global --list
```

📝 **Explicație:**  
Această comandă îți arată toate setările globale făcute. Practic, Git îți arată buletinul tău digital.

---

## 🔧 Alte Vrăji Utile pentru Git

### 🔹 Alege-ți editorul preferat (ca un adevărat scrib)

```bash
git config --global core.editor "code --wait"
```

📝 Deschide Visual Studio Code pentru a edita mesaje de commit, dacă e nevoie.

---

### 🔹 Colorează terminalul (pentru extra claritate și magie vizuală)

```bash
git config --global color.ui auto
```

📝 Git va colora automat statusul, diferențele și istoricul în terminal.

---

### 🔹 Activează rebase automat la `git pull` (pentru un istoric curat)

```bash
git config --global pull.rebase true
```

📝 Opțional, dar util pentru cei care vor un istoric fără noduri în arbore.

---

## 📁 Ce înseamnă `--global`?

Setările făcute cu `--global` se aplică **tuturor** proiectelor Git de pe calculatorul lui Tufor.

Dacă vrei să faci o setare doar pentru un proiect anume, **elimină `--global`** și rulează comanda în acel folder.

---

## 🗂️ Unde sunt salvate aceste setări?

Pe sistemul lui Tufor:

- **Linux/macOS:** `~/.gitconfig`
- **Windows:** `C:\Users\Tufor\.gitconfig`

Git le păstrează aici, ca un jurnal secret al cavalerului commit-urilor.

---

## 🎉 Gata!

Acum Git știe cine e Tufor. Poate începe aventurile commit-urilor, push-urilor și rebase-urilor cu stil și încredere! 🧠🛡️