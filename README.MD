Buatlah program algoritma yang diawali dengan descriptif , flowchart dan pseudo-code !

# Algoritma

## Descriptif

Membuat algoritma menentukan siswa yang lulus dan tidak lulus

1. Mulai
2. Masukan nama siswa
3. Masukan nilai siswa
4. jika nilai lebih besar dari sama dengan 75 maka nilai hasil adalah lulus
5. jika tidak maka tidak lulus
6. outputnya adalah namaSiswa dan hasil nilainya dinyatakan berdasarkan nilai dari hasil
7. selesai

## Flowchart

```mermaid
flowchart LR

a@{shape: circle , label : "Start"}
b@{shape: lean-r, label : "namaSiswa"}
c@{shape: lean-r, label : "nilai"}
d@{shape: diamond, label: "nilai >= 75 "}
e@{shape: rect, label : hasil="Lulus"}
f@{shape: rect, label : hasil="Tidak Lulus"}
g@{shape: lean-r, label : '"{namaSiswa} hasil nilainya diyatakan {hasil}"'}

z@{shape: dbl-circ, label : "Finish"}

a-->b
b-->c
c-->d
d--true-->e
d--false-->f
f-->g
e-->g
g-->z


```

## Pseudo-code

```pseudo


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

OUTPUT namaSiswa, "hasil nilainya dinyatkan", hasil


```
