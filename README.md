<div align="center">

<img src="./banner.svg" width="100%" alt="agrcnw - IT Platform Development Apprentice | IT Solutions & Cybersecurity | Switzerland" />

<br />

[Oryph](https://oryph.com) &nbsp;·&nbsp; [vdlsm.org](https://vdlsm.org) &nbsp;·&nbsp; [cnw.bio](https://cnw.bio)

</div>

<br />

## Projects

<p align="center">
<a href="https://oryph.com"><img src="./oryph.svg" width="32%" alt="Oryph - Owner / The Core - the parent company behind all my projects" /></a>
<a href="https://vdlsm.org"><img src="./vdlsm.svg" width="32%" alt="vdlsm.org - Owner / Encrypted Text Sharing" /></a>
<a href="https://cnw.bio"><img src="./cnw.svg" width="32%" alt="cnw.bio - Owner / Link-in-Bio" /></a>
</p>

<details>
<summary><b>How vdlsm.org encryption works</b></summary>
<br />

```mermaid
flowchart LR
    A["Your note"] --> B["Browser encrypts<br/>AES-256-GCM"]
    B -->|encrypted bytes only| S["Server"]
    B -->|random 256-bit key| L["Link, after the #"]
```

Your browser generates a random 256-bit key and encrypts the note with **AES-256-GCM** before anything is uploaded. The server only receives encrypted bytes. The key is put into the link after the `#`, a part browsers never send to a server.

</details>

<br />

## IT Experience

<img src="./stack.svg" width="100%" alt="IT experience: Huawei switches, Ubiquiti, Fortinet firewalls, Kaspersky Antivirus, Office 365, 1st to 3rd level support, PC building, server setups, Synology NAS, backup solutions" />

<br />

<div align="center">

<sub>Switzerland</sub>

</div>
