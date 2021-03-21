# UwU
## Solusi
Diberikan link menuju web berisi semua tentang term "UwU". karena tidak ada petunjuk, kami coba buka file robots.txt dan menemukan clue

``` this time..there might be a directory called as robots lol ```

lalu ketemu, tinggal tambah ``` /robots ``` pada akhir link. kemudian di halaman baru kita diberikan source code phpnya. sourcenya meminta $_GET['php_is_hard'] untuk kemudian dicompare dengan string ```suzuki_harumiya```. setiap occurence ```suzuki_harumiya``` akan dihapus dengan fungsi ```preg_replace()```, oleh karena itu dibutuhkan pengulangan di tengah menjadi ```suzukisuzuki_harumiya_harumiya``` . Dengan ini, ```preg_replace``` akan mengganti ```suzuki_harumiya```di tengah sehingga string tersisa ```suzuki_harumiya```.

Flag kemudian didapatkan sebagai respon dari webnya

## Flag
```vishwaCTF{well_this_was_a_journey}```
