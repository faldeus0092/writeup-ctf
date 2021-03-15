# Commenting is the key

## Problem Statement
> Silicom tried communicating with Castlene and then they made some comments about it... try to find the flag through this file

> question.pcapng

## Solusi

filenya merupakan .pcapng yang merupakan Packet capture format yang berisi "dump" dari data packets ditangkap dari sebuah network. tinggal buka pakai wireshark

![image](https://user-images.githubusercontent.com/73151823/111194982-57ff6c80-85ee-11eb-9d6a-866edb297e5d.png)

dari judul challengenya, "Commenting is the key", berarti kita buka 

> File Properties>Packet Comments 

di kiri bawah wireshark, di situ terdapat flag

![image](https://user-images.githubusercontent.com/73151823/111195547-f1c71980-85ee-11eb-9d35-911ec7f5ef80.png)

## Flag

```vishwaCTF{packets_are_editable}```
