# Fewer CTF Tools

## About this list

### Why?

I know, I know. There already exists some perfect lists, like [this](https://github.com/apsdehal/aWEsoMe-cTf) and [this](https://github.com/zardus/ctf-tools), but those lists are **too perfect**. I mean they almost include every tool you can find online. If you are a beginner like me, you may spend a lifetime trying and learning each of them. Even if don't need them all, say if you only need the tool for a specific type of CTF puzzle, you may find yourself spending a lifetime choosing among similar tools.

### What's in this list:

**One** tool for each category of CTF puzzles that are **commonly** seen. 

This list tries to make the chosen tool the most powerful and representative one for solving particular type of CTF puzzle.

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
- Padding Oracle: TODO

### Binary

Reverse
- PE info & unpack: PEiD
- Disassembler & decompiler & debugger: IDA Pro
- JAVA decompiler: [jd-gui](https://github.com/java-decompiler/jd-gui)
- Android APK decompiler: [jadx](https://github.com/skylot/jadx)
- .NET decompiler: [ILSpy](http://ilspy.net)
  
Exploits
- Python Exploit Development Assistance for GDB: [Peda](https://github.com/longld/peda)
- CTF toolkit for exploit development: [pwntools](https://github.com/Gallopsled/pwntools)

### Forensics

- Image steganography: [Stegsolve](http://www.caesum.com/handbook/Stegsolve.jar)
- Meta information: [Exiftool](http://www.sno.phy.queensu.ca/~phil/exiftool/)
- Binary extractor: [binwalk](https://github.com/devttys0/binwalk)

### Web

- HTTP Proxy: Burpsuite
- File scanner: [weakfilescan](https://github.com/ring04h/weakfilescan)
- SQL Injection: [sqlmap](http://sqlmap.org)
- XSS exploit: [BeEF](https://github.com/beefproject/beef)
- Webshell: [antSword](https://medicean.gitbooks.io/antsword/zh-hans/index.html)

### Network

- Packets analyzer: [wireshark](https://www.wireshark.org)
- Scanner: [nmap](https://nmap.org)
- WiFi Cracker: [Aircrack-ng](https://www.aircrack-ng.org/index.html)
