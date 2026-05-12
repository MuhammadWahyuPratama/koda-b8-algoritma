# Algoritma

## Bilangan ganjil atau genap

Membuat algoritma menentukan bilangan ganjil atau genap

1. Mulai
2. Siapkan bilangan ganjil atau genap
3. bilangan di modulus 2 dan hasilnya adalah 0 maka di sebut bilangan genap
4. Kalau tidak menghasil kan nilai 0 maka di sebut bilangan ganjil
5. Selesai

## Flowchart

Membuat flowchart untuk program menentukan bilangan ganjil atau genap

```mermaid
flowchart TD

start@{shape: circle, label: "start"}
bilangan@{shape : lean-r , label: "Bilangan"}
proses@{shape: diamond, label: "dibagi habis 2"}
hasil@{shape: lean-r , label: true= "genap"}
hasil2@{shape: lean-r , label: false = "ganjil"}
selesai@{shape: dbl-circ, label: "stop"}

start-->bilangan-->proses-->hasil
proses-->hasil2-->selesai
hasil-->selesai
```
