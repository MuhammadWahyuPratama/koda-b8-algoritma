# Algoritma

## Luas dan Keliling

Membuat algoritma meghitung luas dan keliling lingkaran

1. Mulai
2. Persiapkan Lingkaran yang mau di hitung luas dan keliling nya
3. masukkan nilai jari jari nya
4. Tentukan nilai phi nya 22,7 atau 3.14
5. pilih hitung dan luas
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
c@{shape: rect, label : phi= 22/7 }
d@{shape: lean-r , label: phi * r * r}
e@{shape: lean-l , label: "{ 'Luas Lingkaran' }"}
j@{shape: rect, label : phi=3.14}
k@{shape: lean-r , label: "2 * phi * r"}
l@{shape: lean-l , label: "{ 'Keliling Lingkaran' }"}
m@{shape: dbl-circ, label: "Stop"}
a-->b-->c-->d-->e-->m
b-->j-->k-->l-->m
```

a-->b-->c-->d-->e-->m
b-->j-->k
