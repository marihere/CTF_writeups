## Shakespeare and Encoding

---

#### Description:
*Brutus planned to kill Caesar. However, he hesitated, for he was afraid that Caesar would say 01000100 01010101 01000111 01111100 01011010 00110001 01010110 00101110 01110101 01110000 01110000 00101110 01000011 01110011 01110110 00110010 01110110 01010100 01111110. What did he say?*

---

We are given a message in binary code: 01000100 01010101 01000111 01111100 01011010 00110001 01010110 00101110 01110101 01110000 01110000 00101110 01000011 01110011 01110110 00110010 01110110 01010100 01111110.
Which, when decoded, is: DUG|Z1V.upp.Csv2vT~

The description talks about Caesar, so I immediately thought of the [Caesar cipher](https://en.wikipedia.org/wiki/Caesar_cipher) and [ROT13](https://en.wikipedia.org/wiki/ROT13). But since the are no curly brackets I decided to use the [ROT47](https://en.wikipedia.org/wiki/ROT13#Variants) (which is Caesar cipher by 47 chars).

Then, I used [CyberChef](https://gchq.github.io/CyberChef/#recipe=From_Binary('Space',8)ROT47(-1)&input=MDEwMDAxMDAgMDEwMTAxMDEgMDEwMDAxMTEgMDExMTExMDAgMDEwMTEwMTAgMDAxMTAwMDEgMDEwMTAxMTAgMDAxMDExMTAgMDExMTAxMDEgMDExMTAwMDAgMDExMTAwMDAgMDAxMDExMTAgMDEwMDAwMTEgMDExMTAwMTEgMDExMTAxMTAgMDAxMTAwMTAgMDExMTAxMTAgMDEwMTAxMDAgMDExMTExMTA) to *manually* brute-force the amount of rotations.
![](https://i.imgur.com/T0TQJeS.png)

---

The flag is: 
### CTF{Y0U-too-Bru1uS}
