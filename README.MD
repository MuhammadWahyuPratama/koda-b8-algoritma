Buatlah program algoritma yang diawali dengan descriptif , flowchart dan pseudo-code !

# Algoritma

## Descriptif

Membuat algoritma menentukan siswa yang lulus dan tidak lulus

1. Mulai
2. Masukan nama siswa
3. Masukan nilai siswa
4. periksa nilai siswa
5. jika nilai lebih besar dari 75 maka siswa lulus
6. jika tidak maka tidak lulus
7. tampilkan hasil nilai dan nama siswanya
8. selesai

## Flowchart

```mermaid
flowchart LR

a@{shape: circle , label : "Start"}
b@{shape: lean-r, label : "namaSiswa"}
c@{shape: lean-r, label : "Nilai"}
d@{shape: diamond, label: "Nilai >= 75 "}
e@{shape: lean-l, label : hasil="Lulus"}
f@{shape: lean-l, label : hasil="Tidak Lulus"}
g@{shape: lean-r, label : "namaSiswa"}
h@{shape: lean-r, label : "hasil"}
z@{shape: dbl-circ, label : "Finish"}

a-->b
b-->c
c-->d
d--true-->e
d--false-->f
f-->g
e-->g
g-->h
h-->z


```

## Pseudo-code

```pseudo

MULAI

DECLARE namaSiswa : STRING
DECLARE nilai : INTEGER
DECLARE hasil : STRING

INPUT namaSiswa
INPUT nilai

IF NILAI >= 75 THEN
    hasil <- "Lulus"
ELSE
    hasil <- "Tidak Lulus"
ENDIF

OUTPUT "Nama Siswa =" , namaSiswa
OUTPUT "Hasilnya adalah =" , hasil

SELESAI


```
