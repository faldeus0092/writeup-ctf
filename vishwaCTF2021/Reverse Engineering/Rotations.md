# Rotations

## Problem Statement

> Rotations make you dizzy...don't they?

> attached file: mm

## Solusi

diberi file tanpa ekstensi, namanya juga gak jelas. saya coba buka dengan strings di cmd

![image](https://user-images.githubusercontent.com/73151823/111197241-d3621d80-85f0-11eb-9c36-23be2d9282d3.png)

di situ saya menemukan string yang polanya mirip dengan flag (?)

```
ivfujnPGH
S{s1Nt_1H
f_e0g4gRH
q_Ol_!3}
```

dilihat dari judulnya, "rotation" saya kepikiran menggunakan rotasi/shift dari caesar cipher. karena tidak tahu berapa shiftnya yaudah saya bruteforce

![image](https://user-images.githubusercontent.com/73151823/111197548-2fc53d00-85f1-11eb-9030-db9b6407f8b2.png)

menggunakan online decoder, ternyata +13 memunculkan sebuah string yang mirip flag, hanya saja terdapat huruf U di akhir setiap baris

hapus huruf U, kemudian rapikan stringnya

## Flag
```vishwaCTF{f1Ag_1s_r0t4tEd_By_!3}```
