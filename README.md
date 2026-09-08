<h1 align="center">TrustSentinel</h1>
<p align="center"><em>Defensive security &amp; AI-driven network intelligence.</em></p>

<p align="center">
  <a href="https://trustsentinel.eu"><b>trustsentinel.eu</b></a> ·
  Secure connectivity · P2P network intelligence · vulnerability research
</p>

<p align="center">
  <img alt="Go" src="https://img.shields.io/badge/Go-00ADD8?logo=go&logoColor=white">
  <img alt="Python" src="https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white">
  <img alt="Noise Protocol" src="https://img.shields.io/badge/Noise%20Protocol-6E44FF">
  <img alt="DID / SSI" src="https://img.shields.io/badge/DID%20%2F%20SSI-2E7D32">
  <img alt="WebAssembly" src="https://img.shields.io/badge/WebAssembly-654FF0?logo=webassembly&logoColor=white">
</p>

---

I'm **Álvaro López** — security architect (CISSP) and researcher. A decade of
tools spanning distributed systems, IoT and edge, and doctoral research on the
security of decentralized networks. These are the projects worth keeping — small,
sharp, and tested.

### 🔐 Secure connectivity
- **[netso](https://github.com/trustsentinel/netso)** — secure connectivity control plane: isolated peer networks, discovery, mutual-auth Noise, a brokered shell from **CLI or browser**, monitoring, and self-sovereign (DID) device identity. [![CI](https://github.com/trustsentinel/netso/actions/workflows/ci.yml/badge.svg)](https://github.com/trustsentinel/netso/actions/workflows/ci.yml)
- **[stk](https://github.com/trustsentinel/stk)** — browser broker for remote shell: end-to-end Noise, the hub relays only ciphertext. Go + WebAssembly + xterm.js. [![CI](https://github.com/trustsentinel/stk/actions/workflows/ci.yml/badge.svg)](https://github.com/trustsentinel/stk/actions/workflows/ci.yml)
- **[stuk](https://github.com/trustsentinel/stuk)** — port-knocking SSH access manager: knock + TOTP → temporary, auto-revoked access (iptables + `AuthorizedKeysCommand`). [![CI](https://github.com/trustsentinel/stuk/actions/workflows/ci.yml/badge.svg)](https://github.com/trustsentinel/stuk/actions/workflows/ci.yml)
- **[marshmallows](https://github.com/trustsentinel/marshmallows)** — secure mesh for IoT: an encrypted peer overlay with 2FA/U2F (INCIBE 2019).

### 🛰 Network intelligence &amp; research
- **[argos](https://github.com/trustsentinel/argos)** — distributed P2P blockchain scanning &amp; vulnerability pipeline.
- **[eth-rlp](https://github.com/trustsentinel/eth-rlp)** — RLP encoder/decoder for Ethereum node discovery (discv4). [![CI](https://github.com/trustsentinel/eth-rlp/actions/workflows/ci.yml/badge.svg)](https://github.com/trustsentinel/eth-rlp/actions/workflows/ci.yml)
- **[malware-analysis](https://github.com/trustsentinel/malware-analysis)** — static analysis &amp; forensic case studies.

<sub>Recurring themes: the Noise Protocol for lightweight end-to-end encryption, brokered access with no open ports, and self-sovereign identity for devices at the edge.</sub>

---

<p align="center"><sub>Full trajectory &amp; project deep-dives → <a href="https://trustsentinel.eu">trustsentinel.eu</a></sub></p>
