# html-boilerplate

## Cand se modifica codul, rulati:

`git add .` adaugam toate fisierele in commit

`git commit -m "mesaj commit"` salvam statusul codului cu mesajul "mesaj commit"

`git push` urcam continutul commitului pe server (origin)

## Daca descarcam prima data codul:

`git clone https://...` creaza o copie a repo-ului de pe github

Aceasta copie are tot istoricul de pe github pentru acest repo

O data clonat se poate urca normal, ca la procesul de mai sus

## Daca lucram pe acelasi proiect, pe mai multe device-uri:

Se presupune ca repu-ul a fost clonat pe toate divece-urile.

- situatia 1: pe laptop1 s au modificat fisiere:

Se urca in mod normal pe github cu comenzile de `all`, `commit`, `push`

Pe laptop2 trebuie sincronizat codul. Se va rula:

`git pull` va aduce in locat toate schimbarile de pe github

- situatia 2: pe laptop2 s-au modificat si urcat schimbari:

Se urmeaza instructiunile de `add` si `commit`

Inainte de a da push, se va da un `git pull` pentru a sincroniza ce e locat cu ce e pe github

Se poate rula `git push` care va contine modificarile locate si cele de pe github
