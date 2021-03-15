# Git Up and Dance

## Problem Statement

> You gotta git up and maybe dance a little back and forth to get the desired result

> git_up_and_dance.zip
> 

## Solusi
file zip tersebut jika diekstrak akan menjadi kumpulan file web

![image](https://user-images.githubusercontent.com/73151823/111189443-aad62580-85e8-11eb-8950-e0786b912450.png)

index.html jika dibuka akan menuju browser dan menalpilkan animasi dengan lagu. tidak penting jadi saya skip. perhatian saya di sini adalah judul challenge "**git** up and dance". Serta keberadaan folder .git di situ. Berarti kita bisa mengakses version sebelumnya menggunakan

```git checkout```

Sekarang tugasnya mencari versi mana yang memiliki flag dalam filenya. ketika saya cek dengan

```git log``` 

ketemu sebuah comment yang sepertinya mengarah ke flag

![image](https://user-images.githubusercontent.com/73151823/111189976-38197a00-85e9-11eb-81b5-444df9d124d5.png)

(di situ aslinya tidak ada HEAD, karena udah saya pindah kemarin)

tinggal gunakan command

```git checkout acd2ccc03ddafc1c838adbb3e2d3835d7656777a```

flag ada di file

```workspace.a4362daf.js```

## Flag
```vishwaCTF{d4nc3_4nd_giitupp}```
