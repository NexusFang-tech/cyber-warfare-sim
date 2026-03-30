# BLACKSITE — Cyber Warfare Simulator

**Live:** [nexusfang-tech.github.io/cyber-warfare-sim](https://nexusfang-tech.github.io/cyber-warfare-sim/)

Interactive cybersecurity warfare simulator combining four modules into one platform: a Red vs Blue Team War Room with live scoring, a ransomware kill chain visualizer with real-time file encryption, an OSINT reconnaissance terminal with 9 commands, and a solvable Capture The Flag arena with 13 challenges across 5 categories.

## Modules

### 1. War Room — Red Team vs Blue Team
- Live battle simulation with automated attack/defense events
- Red team launches attacks (SQLi, credential dumps, lateral movement) with MITRE ATT&CK technique IDs
- Blue team responds with defenses (EDR containment, WAF rules, DNS sinkholes)
- Network map shows nodes getting compromised (red) and defended (green) in real-time
- 15-minute round timer with cumulative scoring

### 2. Ransomware Kill Chain Simulator
- 10-phase kill chain progression from reconnaissance through impact
- 48 file nodes with animated encryption — each file flashes red, gets strikethrough, progress bar fills
- Real-time attack log with timestamps per phase
- Simulated ransom note deployed at completion

### 3. OSINT Terminal
- Interactive hacker terminal with 9 commands: `lookup`, `recon`, `whois`, `breach`, `portscan`, `geoip`, `social`, `headers`, `clear`
- Animated typewriter-style output with color-coded results
- Sidebar auto-populates a dossier on lookups with social accounts, breach exposure, and contact data

### 4. CTF Arena
- 13 solvable challenges across Cryptography, Web Security, Forensics, Network, and Reverse Engineering
- Real flags that actually validate on submission
- Hint system, live leaderboard with 10 competitors, personal score tracking
- Challenges include ROT13, Base64, XOR, hex decode, file signatures, Unix timestamps, and x86 assembly

## Tech Stack

`Vanilla JS` · `HTML Canvas` · `CSS Animations` · `GitHub Pages`

Single HTML file. Zero dependencies. No build step.

## Repo Description

> Interactive Cyber Warfare Simulator — Red vs Blue Team War Room with live scoring, ransomware kill chain visualizer with real-time file encryption, OSINT terminal with 9 commands, and solvable CTF arena with 13 challenges. Single file, zero dependencies.
