# Cutest Cookie Clicker Rip-Off 
## Problem Statement
> I built this awesome game based off of cookie clicker! Bet you'll never beat my high score. Hehehe!

> http://web1.utctf.live:4270

## Solusi
diberikan sebuah web, intinya kita disuruh mengklik gambar cookienya sampai melebihi highscore 1.000.000 dalam waktu 30 detik. 

setelah mengecek menggunakan console ```document.cookie``` ternyata highscore disimpan dalam cookie. ![image](https://user-images.githubusercontent.com/73151823/111478031-45a63f80-8762-11eb-9229-59e4d3fdd2cd.png)


tinggal modify highscorenya di console dengan ```document.cookie="highScore=999999999""```

![image](https://user-images.githubusercontent.com/73151823/111478552-c36a4b00-8762-11eb-98a8-d981190ead65.png)

## Flag
> utflag{numnum_cookies_r_yumyum}


