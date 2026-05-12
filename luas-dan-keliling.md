# Algoritma

## Luas dan Keliling

Membuat algoritma meghitung luas dan keliling lingkaran

1. Mulai
2. Persiapkan Lingkaran yang mau di hitung luas dan keliling nya
3. masukkan nilai jari jari nya
4. Tentukan nilai phi nya 22,7 atau 3.14
5. hitung luas dan keliling lingkaran
6. phi kali jari-jari kali jari-jari
7. Maka akan meghasilkan luas lingkaran
8. 2 kali phi kali jari-jari
9. Maka akan menghasilkan Keliling lingkaran
10. Selesai

## Flowchart

Membuat flowchart untuk program menghitung luas dan keliling lingkaran

```mermaid
flowchart TD
a@{shape: circle, label : "start"}
b@{shape: lean-r, label : r}
z@{shape: diamond, label : "r % 7 == 0"}
c@{shape: rect, label : phi= 22/7 }
e@{shape: lean-l , label: "{ 'Luas Lingkaran' }"}
y@{shape : rect, label : "luas= phi * r * r"}
x@{shape : rect, label : "kel= 2 * r * r"}
j@{shape: rect, label : phi= 3.14}
u@{shape: lean-r , label: "{ 'Keliling Lingkaran' }"}
m@{shape: dbl-circ, label: "Stop"}
a-->b
b-->z
z--true-->c
z--false-->j
j-->y
c-->y
y-->e
e-->x
x-->u
u-->m


```

## Pseudo-code

```pseudo

DECLARE r = INTEGER
DECLARE phi = REAL
DECLARE luas = REAL
DECLARE kel = REAL
Input r

IF r Modulus 7 == 0 THEN
    phi <- 22/7
ELSE
    phi <- 3.14
ENDIF

luas = phi * r * r
keliling = 2 * phi * r

OUTPUT "LUAS LINGKARAN =", luas
OUTPUT "Keliling Lingkaran =", kel

```
