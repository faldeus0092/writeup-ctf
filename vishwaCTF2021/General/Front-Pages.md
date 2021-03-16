# Front Pages
## Problem Statement
> Cover pages or front pages of newspapers and magazines contain the biggest news stories and are designed to grab a person's attention. BTW, did you know that the internet has a front page too?. Flag Format is same : vishwaCTF{}
## Solusi

"the internet has a front page too?" merefer pada julukan reddit, yaitu "reddit: the front page of the internet". Tinggal cari "vishwactf reddit" melalui google

![image](https://user-images.githubusercontent.com/73151823/111307924-a6634880-868c-11eb-9dbf-eaa2ec836a88.png)

 kemudian hasil pencarian ke dua
 
 ![image](https://user-images.githubusercontent.com/73151823/111308023-c1ce5380-868c-11eb-9528-f0fd2cc2aeda.png)

gunakan situs ```http://web.archive.org/``` untuk melihat webpage yang sudah didelete

![image](https://user-images.githubusercontent.com/73151823/111308208-f93d0000-868c-11eb-911b-1436bd974702.png)

terlihat pernah diarchive tanggal 14 maret 2021, setelah dibuka muncul flagnya, tapi masih dienkripsi

![image](https://user-images.githubusercontent.com/73151823/111308412-3bfed800-868d-11eb-889c-5eca26b38e83.png)

18 century french scholar merefer pada Blaise de Vigenere, yang menemukan vigenere cipher (walaupun aslinya vigenere itu abad ke 19). Akan tetapi, untuk mendecode vigenere cipher, kita butuh sebuah key. Setelah berkali2 trial dan error saya baru sadar ternyata keynya nama ctf-nya sendiri, ```VISHWACTF```

![image](https://user-images.githubusercontent.com/73151823/111308793-b596c600-868d-11eb-8c91-fa30dd9cf2f2.png)

## Flag
```vishwaCTF{0$iNt_1s_oFT3n_0v3rL0okeD}```
