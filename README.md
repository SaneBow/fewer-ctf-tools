# Fewer CTF Tools

## About this list

### Why?

I know, I know. There already exists some perfect lists, like [this](https://github.com/apsdehal/aWEsoMe-cTf) and [this](https://github.com/zardus/ctf-tools), but those lists are **too perfect**. I mean they almost include every tool you can find online. If you are a beginner like me, you may spend a lifetime trying and learning each of them.

### What's in this list:

**One** tool for each category of CTF puzzles that are **commonly** seen. 

This list tries to make the chosen tool the most powerful and representative one for solving each particular type of CTF puzzle.

### What will not be included in this list:

- Alternative tools for a particular type of CTF puzzle that is similar to the listed tool. (e.g. ZAP and Burpsuite)
- Tools for specific topics that are not so common in CTF. (e.g. PDF analysis tools)

## Tools

### Crypto

Classical
- Substitution: [quipqiup.com](http://www.quipqiup.com)
- XOR: [xortool](https://github.com/hellman/xortool)

Modern
- RSA: [RsaCtfTool](https://github.com/Ganapati/RsaCtfTool)
- MD5 Reverse Lookup: [cmd5.com](http://www.cmd5.com)
- Length Extension Attack: [HashPump](https://github.com/bwall/HashPump)
- Padding Oracle: [Padding-oracle-attack](https://github.com/mpgn/Padding-oracle-attack)

### Binary

Reverse
- PE info & unpack: [ExeinfoPE](http://exeinfo.pe.hu)
- Disassembler & decompiler & debugger: IDA Pro
- JAVA decompiler: [jd-gui](https://github.com/java-decompiler/jd-gui)
- Android APK decompiler: [jadx](https://github.com/skylot/jadx)
- .NET decompiler: [ILSpy](http://ilspy.net)
  
Exploits
- Python Exploit Development Assistance for GDB: [pwndbg](https://github.com/pwndbg/pwndbg)
- CTF toolkit for exploit development: [pwntools](https://github.com/Gallopsled/pwntools)
- ROP gadgets finder: [ROPgadget](https://github.com/JonathanSalwan/ROPgadget)
- oneshot exploitation: [one_gadget](https://github.com/david942j/one_gadget)
- seccomp analysis tool: [seccomp-tools](https://github.com/david942j/seccomp-tools)

### Forensics

- Image steganography: [Stegsolve](http://www.caesum.com/handbook/Stegsolve.jar)
- Meta information: [Exiftool](http://www.sno.phy.queensu.ca/~phil/exiftool/)
- Binary extractor: [binwalk](https://github.com/devttys0/binwalk)

### Web

- HTTP Proxy: [Burpsuite](https://portswigger.net/burp)
- File scanner: [FileSensor](https://github.com/Xyntax/FileSensor)
- SQL Injection: [sqlmap](http://sqlmap.org)
- XSS exploit: [BeEF](https://github.com/beefproject/beef)
- Webshell: [antSword](https://medicean.gitbooks.io/antsword/zh-hans/index.html)

### Network

- Packets analyzer: [wireshark](https://www.wireshark.org)
- Scanner: [nmap](https://nmap.org)
- WiFi security tools suite: [Aircrack-ng](https://www.aircrack-ng.org/index.html)
