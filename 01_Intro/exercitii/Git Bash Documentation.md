
# Povestea lui Tufor în Țara Git Bash

Bine ai venit în lumea magică a liniei de comandă, unde Tufor, un student curios, pornește într-o aventură legendară: să devină maestru al Git Bash! 🧙‍♂️💻

---

## Capitolul 1 – Rătăcit prin pădurea fișierelor (`pwd`)

Tufor s-a trezit într-un loc ciudat, înconjurat de directoare misterioase. „Unde sunt?” se întrebă el.

Cu bagheta sa (a.k.a tastatura), rosti vrăjitoarea comandă:

```bash
$ pwd
/c/Users/Tufor/Desktop
```

„Aha! Sunt pe Desktop!” exclamă Tufor. Pădurea nu era atât de înfricoșătoare până la urmă.

---

## Capitolul 2 – Deschide-ochii (`ls`, `ls -la`)

Curios ce comoară se ascunde acolo, Tufor încercă:

```bash
$ ls
poze  teme.txt  dragon_invizibil

$ ls -la
drwxr-xr-x 1 gicu gicu 0 .
-rw-r--r-- 1 gicu gicu 42 .ascuns_tare
```

„Dragonul invizibil era acolo tot timpul?!?” 🐉😱

---

## Capitolul 3 – Portalurile magice (`cd`, `cd ..`, `cd /c`)

Tufor descoperi porți către alte tărâmuri:

```bash
$ cd dragon_invizibil
$ cd ..          # Se întoarce în trecut
$ cd /c          # Intra în tărâmul discului C
```

Folosind aceste porți, el putea călători oriunde. Magie pură.

---

## Capitolul 4 – Ridică un castel (`mkdir`), apoi dărâmă-l (`rm -r`)

Tufor deveni constructor:

```bash
$ mkdir turn_de_veghe
```

Dar, când construcția nu i-a plăcut:

```bash
$ rm -r turn_de_veghe
```

„Cu mare putere vine mare... distrugere.”

---

## Capitolul 5 – Începe o poveste (`touch`)

Tufor vru să-și scrie memoriile:

```bash
$ touch aventura_mea.md
```

Dar până să scrie ceva, a fost distras de o pisică ce alerga după un fișier `.tmp`.

---

## Capitolul 6 – Hărți și comori (Căi Relative și Absolute)

Când a primit o hartă, a învățat două stiluri:

- **Calea Absolută**: `/c/Users/Tufor/Desktop/comori`
- **Calea Relativă**: `../pesteri_secrete`

A mers cu GPS-ul (`pwd`) și a urmat săgețile (`cd`).

---

## Capitolul 7 – Vrăji speciale (Parametrii)

Tufor a aflat că fiecare vrajă poate avea... modificatori!

```bash
$ ls -l
$ mkdir -p labirint/nivel1/nivel2
```

Cu `-p` poți construi și sub-sub-subdirectoare! Magie nestingherită.

---

## Capitolul 8 – Magia tăcerii (`Tab`)

Când Tufor era prea leneș să scrie:

```bash
$ cd pro<Tab>
```

Terminalul îl ajuta! Era ca și cum cineva îi citea gândurile. („Ești magician sau doar bun la autocomplete?”)

---

## Capitolul 9 – Curățenie cu un singur deget (`clear`, `Ctrl + L`)

După atâtea comenzi, ecranul lui Tufor era o mizerie. Atunci a rostit:

```bash
$ clear
```

sau a apăsat `Ctrl + L`. Ecranul a devenit alb ca o foaie nouă. Tufor zâmbi. Zen.

---

## Capitolul Final – Provocările Eroice (Exerciții)

Tufor se afla la finalul uceniciei sale în artele terminalului. Maestrul Bash i-a încredințat cele mai grele misiuni pentru a-i testa curajul, precizia și stăpânirea comenzilor sacre.

---

## 🕵️‍♂️ Misiunea 1 – Detectivul Liniei

🎯 Scop: Înțelege unde ești și ce te înconjoară.

1. Rostește comanda magică pentru a afla locul în care te afli:

```bash
pwd
```

2. Caută indicii vizibile și ascunse:

```bash
ls
ls -la
```

3. Infiltrează-te în camera de supraveghere cunoscută sub numele de „Desktop”:

```bash
cd ~/Desktop
```

---

## 🏗️ Misiunea 2 – Constructorul Nebun

🎯 Scop: Creează un sanctuar de cod.

1. Creează fortăreața unde Tufor va păstra codul:

```bash
mkdir proiect_git
cd proiect_git
```

2. Invocă două pergamente sacre:

```bash
touch readme.md main.py
```

3. Creează camera secretă unde magia se va scrie:

```bash
mkdir src
```

---

## 🔥 Misiunea 3 – Distruge și Reconstruiește

🎯 Scop: Stăpânește arta creației și distrugerii.

1. Extermină un fișier nefolositor:

```bash
rm main.py
```

2. Creează un drum ascuns spre `backup/arhiva` dintr-o singură comandă:

```bash
mkdir -p backup/arhiva
```

3. Plimbă-te prin sălile noii tale construcții:

```bash
cd backup
cd ../src
cd ..
```

---

## 🧙‍♂️ Misiunea 4 – Folosește-ți puterile magice

🎯 Scop: Fii rapid și ordonat ca un ninja digital.

1. Scrie doar începutul unei comenzi sau căi și apasă `Tab` pentru a o completa:

```
cd pro[TAB]
```

2. Curăță ecranul haotic:

```bash
clear
```

sau apasă `Ctrl + L`

---

🏁 **Finalul:**  
Tufor a trecut prin toate misiunile și a fost recunoscut drept Maestru al Terminalului. 