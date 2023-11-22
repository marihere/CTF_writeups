## Plain Sight

---

#### Description:
*TJ loves wearing his invisibility Cloak and hiding in Plain Sight. He also likes making lists of his favourite Pokemon. TJ asked you for the flag in exchange for a poster of his favourite Pokemon. Here's the poster, can you uphold your end of the bargain?*

**Attachment:** [poster.jpg](https://ectf.nitk.ac.in/files/b890d3ad603ae55ad32f84c796b2a748/poster.jpg?token=eyJ1c2VyX2lkIjo0MjMsInRlYW1faWQiOjIwNSwiZmlsZV9pZCI6MjB9.YiUD1A.OoS98eMFW5Ep0x3kEctNx13K4zw)

---

After reading carefully the description and the hints (1), I started looking for any files hiding in the image.


I found some files so I extracted them.

![](https://i.imgur.com/GFNMwJ2.png)

We now have a ZIP file and a TXT file. The ZIP file isn't important because it contains a copy of the TXT file.

![](https://i.imgur.com/NLo21DR.png)


The TXT file contains a list of Pokémons.

![](https://i.imgur.com/YA30UDQ.png)


I had no idea of what to do... Then I read again the first hint (1) and I decided to search on the Internet "cloak factory forensics" and I clicked on the first [result](https://www.hackingarticles.in/cloakify-factory-a-data-exfiltration-tool-uses-text-based-steganography/), which talks about a tool called [CloakifyFactory](https://github.com/TryCatchHCF/Cloakify). After reading the article I thought that probably it's the same program used on the list that I found.

![](https://i.imgur.com/2Td9vNN.png)


![](https://i.imgur.com/Rf5NKnh.png)


Here I used the option 6, which is the pokemonGo cipher.

![](https://i.imgur.com/08F29tG.png)


And then I got the flag:

![](https://i.imgur.com/V4P44cn.png)

---

The flag is:
### **CTF{p1k@chu}**




-----




(1): Hint 1 - TJ’s Cloak was made in a Factory that hides many things in Plain Sight. | Hint 2 - Turns out TJ's poster can also hide items..
