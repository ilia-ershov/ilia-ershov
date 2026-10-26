# Hi, I'm Ilia Ershov

First-year Information Security student at HSE University (Moscow). I work on
reverse engineering, CTFs and the security of LLM agents.

- 🏆 Three-time prize-winner of the national final of the All-Russian School
  Olympiad in Information Security (2024, 2025, 2026)
- 🔬 Information-security intern at Sber (2026) and Kaspersky "Technology Valley" (2023)
- 🚩 Led the HSE Lyceum CTF community for two years (100 → 250 members)
- 👨‍🏫 Teach the Moscow information-security olympiad team (about 300 students)

📫 [ilia@ershov.me](mailto:ilia@ershov.me) · [ershov.me](https://ershov.me) · Telegram [@m0w0kl3n](https://t.me/m0w0kl3n)

## Projects

| Project | What it is |
| --- | --- |
| [**Yandex Station Lite — security research**](https://github.com/ilia-ershov/yandex-station-lite-research) | Rooted my own Alice smart speaker over the LAN using leaked CA certs, reversed its 21 MB firmware in IDA Pro, analysed its telemetry, and reversed the glagol LAN protocol far enough to drive the assistant. Full writeup with a severity-rated findings register |
| [**llm_ida_c2_analysis**](https://github.com/ilia-ershov/llm_ida_c2_analysis) | LLM agent that reverse-engineers malware C2 protocols through a headless IDA Pro over MCP, verifies its findings with Capstone and Unicorn emulation, and writes a report and a working protocol client |
| [**MCP Firewall**](https://github.com/ilia-ershov/mcp_firewall) | Protocol-aware proxy that shields AI agents from prompt injection, secret leaks and obfuscated payloads in MCP tool output, with a reproducible safe/unsafe demo |
| [**Veil**](https://github.com/ilia-ershov/veil) · [live](https://veil.ershov.me/) | Web service that issues a separate forwarding e-mail address for every website, protecting users from data-breach lookups and targeted phishing (Flask, PostgreSQL, React) |
| [**ABOB**](https://github.com/ilia-ershov/abob) | Text-mode web browser in C with ncurses and Vim keybindings, co-developed with a classmate |
| [**fcard**](https://github.com/Andrewchistyakov/flashcards_lyc) | Team C++ project: command-line flashcards app with tests in GitHub Actions; I wrote the core card logic, CSV storage, review TUI and tests |

## CTF

- Play on CTFtime teams [274325](https://ctftime.org/team/274325) and [281646](https://ctftime.org/team/281646); mostly reverse engineering and pwn.
- M\*CTF Junior Finals — 1st place (team), 2023; CU School CTF — 4th place, 2025.
- Practice on Hack The Box and Web-Kids (around 200th of ~7,700).

## Stack

**Reverse engineering & security:** IDA Pro · Capstone · Unicorn · Wireshark · ADB · MITM / TLS tooling
**Languages:** Python · C · C++ · Bash · SQL
**Build & infra:** Linux · Docker · PostgreSQL · Flask · React · GitHub Actions
