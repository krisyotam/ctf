# tryhackme

TryHackMe room notes and writeups organized by topic and learning path. Indexed in code.db at [krisyotam.com/code](https://krisyotam.com/code/tryhackme).

## Structure

```
rooms/
  fundamentals/       intro, methodology, linux basics
  tooling/            nmap, metasploit, hydra, rustscan, tmux
  web/                owasp top 10, sqli, xss, lfi, juice shop
  networking/         protocols, packet analysis, pivoting
  crypto/             hashing, encoding, cipher challenges
  reverse-engineering/ x86, ghidra, radare2, elf reversing
  privesc/            linux privesc, windows privesc, sudo exploits
  active-directory/   ad attacks, kerberoasting, bloodhound
  ctf/                standalone ctf rooms
  progress.md         room completion tracker
  room-list.md        full room list with links

learning-paths/
  complete-beginner/
  jr-pentester/
  offensive-pentesting/
  soc-level-1/
  red-teaming/
  cyber-defense/
```

Each room gets its own directory under the relevant category:
```
rooms/<category>/<room-slug>/
  notes.md
```
