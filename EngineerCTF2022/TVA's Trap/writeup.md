## TVA's Trap

---

#### Description:
*Nadia is caught in a time loop as the guest of honor at a seemingly inescapable party one night in New York City. In order to get out she has to decode the following text message she gets. The TVA being noobs don’t understand that just encoding is not exactly secure. Can you get the flag and help Nadia get to base ?*

*Flag format: CTF{...}*

---

We are given a file that looks like this:
![](https://i.imgur.com/uORNnbC.png)

From what we can see, it looks like it's a text encoded in Base64 for 8 times. (8 x 64)

So I copied and pasted the text on [CyberChef](https://gchq.github.io/CyberChef/#recipe=From_Base64('A-Za-z0-9%2B/%3D',true)From_Base64('A-Za-z0-9%2B/%3D',true)From_Base64('A-Za-z0-9%2B/%3D',true)From_Base64('A-Za-z0-9%2B/%3D',true)From_Base64('A-Za-z0-9%2B/%3D',true)From_Base64('A-Za-z0-9%2B/%3D',true)From_Base64('A-Za-z0-9%2B/%3D',true)From_Base64('A-Za-z0-9%2B/%3D',true)&input=CgoKCgoKCgogICAgICAgICAgICAgICBWbTB3ZUU1R2JGZFdXR2hVViAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICAwZG9XRll3Wkc5V1ZsbDMgICAgICAgICAgICBXa1JTV0ZKCiAgICAgICAgICAgICAgIHNiRCAgICAgICAgICAgTlpWICAgICAgICAgICAgICAgICAgICBWWiAgICAgIFBWICAgICAgICAgICAgICAgICAgICAgICAgICAgIDJ4YSAgICAgICAgICAgICAgICAgICAgICAgYzFOICAgc1dsCiAgICAgICAgICAgICAgIGRTTSAgICAgICAgICAgMUpRICAgICAgICAgICAgICAgICAgICAgVmogICAgSjQgICAgICAgICAgICAgICAgICAgICAgICAgICAgIFlXUiAgICAgICAgICAgICAgICAgICAgICBXUm4gICAgTmhSCiAgICAgICAgICAgICAgIG1SWCAgICAgICAgICAgVFRGICAgICAgICAgICAgICAgICAgICAgIEtlICBWZCAgICAgICAgICAgICAgICAgICAgICAgICAgICAgIFdaRCAgICAgICAgICAgICAgICAgICAgIFJaViAgICAgMUpYCiAgICAgICAgICAgICAgIFVtNUtZVkp0YUc5VVZtaENaICAgICAgICAgICAgICAgICAgICAgICBXeGsgICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgIFYxVnJaRlJpVmxwSVYydCAgICAgICAgb1YyICAgICAgRkdTCiAgICAgICAgICAgICAgIG5OaiAgICAgICAgICAgUm1oICAgICAgICAgICAgICAgICAgICAgVlYgICBrViAgICAgICAgICAgICAgICAgICAgICAgICAgICAgIEtURiAgICAgICAgIGxxUiAgICAgICBtRmogICAgICAgYkd0CiAgICAgICAgICAgICAgIDZZVSAgICAgICAgICAgWlNUICAgICAgICAgICAgICAgICAgICBsWiAgICAgWVEgICAgICAgICAgICAgICAgICAgICAgICAgICAgIGxwVyAgICAgICAgIFZ6RSAgICAgIHdWaiAgICAgICAgRmtTCiAgICAgICAgICAgICAgIEZOciAgICAgICAgICAgYkZKICAgICAgICAgICAgICAgICAgIGhlICAgICAgIG14ICAgICAgICAgICAgICAgICAgICAgICAgICAgIGhWbSAgICAgICAgIHBPYiAgICAgMkZHICAgICAgICAgVW5OCiAgICAgICAgICAgICAgIFhiVVpVVWpGYVNWcEZXbUZVICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgIGJGcFpVV3hzVjFaNlFYaCAgICAgVmFrcEhVMFphZFZKc1NsZFNNCiAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgMDAx) and decoded it for 8 times.
![](https://i.imgur.com/xzxa7GM.png)

---

And we get the flag which is:
### CTF{w3c-ctf-z0z2_3ry9t0}
