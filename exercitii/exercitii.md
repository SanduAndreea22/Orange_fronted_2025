
# Documentație Git Bash - Comenzi de Bază și Exerciții Practice

Această documentație detaliază comenzile esențiale din Git Bash, utile pentru navigarea și manipularea fișierelor și directoarelor în sistemul de operare, urmate de un set de exerciții pentru a vă consolida cunoștințele.

---

## 1. Comanda `pwd`

**Descriere:**  
`pwd` (print working directory) afișează calea completă (absolută) a directorului curent.

**Exemplu:**  
```bash
$ pwd
/c/Users/student/Desktop
```

**Explicație:**  
Această comandă ne arată în ce director lucrăm în prezent.

---

## 2. Comanda `ls` și `ls -la`

**Descriere:**  
- `ls` listează fișierele și directoarele din directorul curent.
- `ls -la` listează toate fișierele, inclusiv cele ascunse (încep cu `.`), cu detalii suplimentare (permisii, dimensiune, dată).

**Exemplu:**  
```bash
$ ls
document.txt  proiect/

$ ls -la
drwxr-xr-x  1 user user   0 Aug  6 10:00 .
drwxr-xr-x  1 user user   0 Aug  6 09:00 ..
-rw-r--r--  1 user user 123 Aug  6 10:00 document.txt
```

**Explicație:**  
Comanda `ls -la` este utilă pentru a vedea și fișierele ascunse, precum și pentru a inspecta permisiunile și datele despre fișiere.

---

## 3. Comanda `cd`

**Descriere:**  
`cd` (change directory) este folosită pentru a naviga între directoare.

**Exemple:**  
```bash
$ cd proiect
$ cd ..        # urcă un nivel înapoi
$ cd /c/Users  # merge la calea absolută specificată
```

### Variante:
- `cd _` – uneori folosit pentru a reveni la ultimul director (în funcție de shell).
- `cd /c` – accesează discul C (echivalent cu C:\).
- `cd /d` – accesează discul D (echivalent cu D:\).

---

## 4. Comanda `mkdir` și `rm`

**Descriere:**  
- `mkdir` creează un nou director.
- `rm` șterge un fișier sau director.

**Exemplu:**  
```bash
$ mkdir curs_git
$ rm document.txt
$ rm -r curs_git  # șterge un director și conținutul său
```

**Atenție:**  
`rm` este periculos – nu trimite la coșul de reciclare. Folosiți-l cu grijă.

---

## 5. Căi Relative și Absolute

- **Cale absolută:** pornește de la rădăcina sistemului (`/`), ex: `/c/Users/student/Desktop`
- **Cale relativă:** pornește din directorul curent, ex: `../alte_fisiere`

---

## 6. Parametri ai comenzilor

**Descriere:**  
Parametrii sunt opțiuni suplimentare ce modifică comportamentul comenzilor.

**Exemplu:**  
- `ls -l` – listare detaliată
- `rm -r` – ștergere recursivă
- `mkdir -p dir1/dir2` – creează structuri de directoare imbricate

---

## 7. Folosirea tastei `Tab`

**Descriere:**  
Tasta `Tab` completează automat numele fișierelor/directoarelor. Este foarte utilă pentru a evita greșelile de scriere.

**Exemplu:**  
```bash
$ cd pro<Tab>    # va completa automat în cd proiect/ dacă există un folder cu acel nume
```

---

## 8. Comanda `touch`, `clear` sau `Ctrl + L`

- `touch fisier.txt` – creează un fișier gol
- `clear` sau `Ctrl + L` – curăță ecranul terminalului

**Exemplu:**  
```bash
$ touch test.md
$ clear
```

---

# Exerciții Practice

## Exercițiul 1 – Navigare și listare

1. Deschide Git Bash.
2. Afișează directorul curent (`pwd`).
3. Listează conținutul (`ls` și `ls -la`).
4. Navighează în directorul Desktop.

## Exercițiul 2 – Creare directoare și fișiere

1. Creează un folder `proiect_git` pe Desktop.
2. Intră în el (`cd proiect_git`).
3. Creează 2 fișiere: `readme.md` și `main.py` folosind `touch`.
4. Creează un folder `src` în interior.

## Exercițiul 3 – Ștergere și comenzi avansate

1. Șterge fișierul `main.py`.
2. Creează un director `backup/arhiva` folosind `mkdir -p`.
3. Navighează cu `cd` folosind calea relativă.

## Exercițiul 4 – Testare Tab și clear

1. Scrie o comandă `cd` și folosește `Tab` pentru auto-completare.
2. Folosește `clear` sau `Ctrl + L` pentru a curăța terminalul.

---

## Bonus

1. Găsește o cale absolută spre un fișier creat.
2. Găsește o cale relativă între două directoare.

---

## Sfaturi utile

- Folosește `Tab` cât mai des.
- Verifică comenzile cu `--help` (ex: `ls --help`).
- Exersează comenzi într-un folder de test pentru a evita pierderea fișierelor importante.

---

**Final:** Acum ai o bază solidă pentru a lucra eficient în Git Bash!