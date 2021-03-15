# Comments

## Problem Statement

> Changing the contents of file will result in loosing the flag. So I repeat dont change its contents

> Comments.docx

## Solusi

diberikan file docs yang jika dibuka akan ada flag palsu

```vishwaCTF{f@ls3_fl@g```

kata kuncinya di sini adalah kategori challenge yaitu forensik. Mencari "docx forensics" di google, ternyata file .docx dapat dibuka sebagai .zip. Di situ saya menemukan beberapa file setelah diekstrak

![image](https://user-images.githubusercontent.com/73151823/111192751-ffc76b00-85eb-11eb-9aba-5a6c81bd8b0b.png)

flagnya ada di file word/settings.xml , dibalut dengan comment

![image](https://user-images.githubusercontent.com/73151823/111192964-39987180-85ec-11eb-866f-b4b5f08b1705.png)

## Flag

```vishwaCTF{comm3nts_@r3_g00d}```
