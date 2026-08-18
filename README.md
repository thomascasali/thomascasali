# Thomas Casali

Computer science teacher at a technical high school in Italy by day, indie developer after hours. I build web and mobile software for sports events and for schools, mostly solo, and I use Claude Code for all of it.

[🇮🇹 Versione italiana più sotto](#-versione-italiana)

## What I'm sharing right now

**[claude-kb-workflow](https://github.com/thomascasali/claude-kb-workflow)**, a memory system for Claude Code. Inside a session the model remembers everything; between sessions nothing survives. The toolkit compiles messy sessions into a wiki and promotes a page to a stable knowledge base only after it has held up in production on a second project. I've been running it since April 2026 on the projects listed below, and it's public from 18 August 2026. Docs in English and Italian.

The same method, told for students: [an interactive presentation in five acts](https://thomascasali.github.io/presentazione-kb-workflow/?lang=en) (English and Italian, [source](https://github.com/thomascasali/presentazione-kb-workflow)).

If you try the toolkit and something breaks, [open an issue](https://github.com/thomascasali/claude-kb-workflow/issues). If you want to talk about how you keep knowledge between sessions, [Discussions](https://github.com/thomascasali/claude-kb-workflow/discussions) is the place.

## What I build

Most of my code runs in production for people who don't care what stack it is. A sample:

| Project | What it does |
|---|---|
| [fivbeach.com](https://fivbeach.com) | Browse international beach volley tournaments |
| [beacharena.it](https://beacharena.it) | Digital ecosystem for a beach arena: events, clubs, athletes, plus the ESP32+RFID system that opens the doors and meters the showers, with a Telegram bot for ops |
| [aibvc.app](https://aibvc.app) | Management platform for the Italian Beach Volley Club association |
| [centrosportivo.online](https://multicentro.centrosportivo.online/portale) | Online booking of courts and classes for sports centres, multi-centre portal |
| [maraffaonline.it](https://maraffaonline.it) | Multiplayer card games in the browser (Node.js + WebSocket), with ELO rankings |
| [TeamToDo](https://teamtodo.work) | Task management for teams, my first published Flutter app: free on the [App Store](https://apps.apple.com/it/app/teamtodo/id6759438222) and [Play Store](https://play.google.com/store/apps/details?id=work.teamtodo.app), plus a [web app](https://app.teamtodo.work) |
| [Fichess](https://github.com/thomascasali/fichess) | Unofficial mobile client for FICS, the Free Internet Chess Server (Flutter) |
| [tornei.app](https://tornei.app) | Multi-tenant platform for running beach volley tournaments |
| School portals | Parents sign school paperwork with an email OTP; an AI assistant reads circulars over Telegram |

Stack, when it matters: Laravel and Node.js on the back end, Vue and React on the web, Flutter on mobile, Docker + Traefik on a couple of VPS, ESP32 for the hardware bits.

## Teaching material

Interactive React presentations I use in class, in Italian, all with a live page: [ISO/OSI simulation](https://thomascasali.github.io/simulazione-iso-osi/), [RSA cryptography](https://thomascasali.github.io/rsa-slides/), [firewalls and ACLs](https://thomascasali.github.io/presentazione-firewall-acl/), [VPN](https://thomascasali.github.io/presentazione-vpn/), [VLAN and subnetting](https://thomascasali.github.io/presentazione-vlan/), [IPv6](https://thomascasali.github.io/presentazione-ipv6/), [security threats](https://thomascasali.github.io/presentazione-minacce-informatiche/), [OOP](https://thomascasali.github.io/presentazione-oop/), [SQLite](https://thomascasali.github.io/dispensa-sqlite/), [Google Workspace](https://thomascasali.github.io/google-workspace-slides/). Full table in the Italian section below.

## Contact

Cesenatico, Italy · casali.thomas@gmail.com · [LinkedIn](https://www.linkedin.com/in/thomascasali/)

---

<a name="italiano"></a>

# 🇮🇹 Versione italiana

Ciao, sono Thomas. Di giorno insegno informatica alle superiori (Sistemi e Reti, TPSIT, GPOI); nei ritagli di tempo sviluppo software per lo sport e per la scuola, quasi sempre da solo, e da tempo con Claude Code. Alleno e organizzo beach volley, che è il motivo per cui metà dei progetti qui sotto ha a che fare con la sabbia.

## Cosa sto condividendo adesso

**[claude-kb-workflow](https://github.com/thomascasali/claude-kb-workflow)**: un sistema di memoria per Claude Code. Dentro una sessione l'AI ricorda tutto; tra una sessione e l'altra non sopravvive niente. Il toolkit trasforma le sessioni sporche in una wiki e promuove una pagina alla knowledge base stabile solo dopo che ha retto in produzione su un secondo progetto. Lo faccio girare da aprile 2026 sui progetti elencati sotto, ed è pubblico dal 18 agosto 2026. Documentazione in inglese e in italiano, e l'italiano non è una traduzione di cortesia.

Lo stesso metodo raccontato per gli studenti: [una presentazione interattiva in cinque atti](https://thomascasali.github.io/presentazione-kb-workflow/) (in italiano e inglese, [sorgente](https://github.com/thomascasali/presentazione-kb-workflow)).

## Progetti

### Sport e community

| Progetto | Descrizione |
|---|---|
| [aibvc.app](https://aibvc.app) | Piattaforma per la gestione dell'attività dell'Associazione Italiana Beach Volley Club |
| [clubseries.it](https://clubseries.it) | Gestione del campionato di beach volley per società Club Series AIBVC |
| [clubseries.app](https://clubseries.app) | Gestione delle Club Series Finals |
| [beacharena.it](https://beacharena.it) | Ecosistema digitale per eventi sportivi, società e atleti, con controllo accessi ESP32+RFID e bot Telegram |
| [palabvu.it](https://palabvu.it) | Ecosistema digitale per la gestione di un centro sportivo |
| [centrosportivo.online](https://multicentro.centrosportivo.online/portale) | Prenotazione online di campi e corsi per centri sportivi, portale multi-centro |
| [fivbeach.com](https://fivbeach.com) | Consultazione dei tornei internazionali di beach volley |

### App e software

| Progetto | Stack | Descrizione |
|---|---|---|
| [TeamToDo](https://teamtodo.work) | Flutter + Firebase | Gestione task per team, la mia prima app Flutter pubblicata: gratuita su [App Store](https://apps.apple.com/it/app/teamtodo/id6759438222) e [Play Store](https://play.google.com/store/apps/details?id=work.teamtodo.app), più [web app](https://app.teamtodo.work) |
| SportCenter Live | Flutter + RTMP | Streaming di eventi sportivi |
| [Fichess](https://github.com/thomascasali/fichess) | Flutter | Client mobile non ufficiale per FICS, il Free Internet Chess Server |
| [tornei.app](https://tornei.app) | Laravel + Vue | Piattaforma multi-tenant per l'organizzazione e la gestione di tornei di beach volley |
| [MaraffaOnline](https://maraffaonline.it) | Node.js + WebSocket | Giochi di carte multiplayer nel browser, con classifiche ELO |

### Didattica interattiva

Presentazioni React animate per le lezioni. Il titolo apre la presentazione live:

| Argomento | Presentazione | Repository |
|---|---|---|
| Simulazione ISO/OSI | [Live](https://thomascasali.github.io/simulazione-iso-osi/) | [GitHub](https://github.com/thomascasali/simulazione-iso-osi) |
| Crittografia RSA | [Live](https://thomascasali.github.io/rsa-slides/) | [GitHub](https://github.com/thomascasali/rsa-slides) |
| Firewall e ACL | [Live](https://thomascasali.github.io/presentazione-firewall-acl/) | [GitHub](https://github.com/thomascasali/presentazione-firewall-acl) |
| VPN | [Live](https://thomascasali.github.io/presentazione-vpn/) | [GitHub](https://github.com/thomascasali/presentazione-vpn) |
| VLAN e subnetting | [Live](https://thomascasali.github.io/presentazione-vlan/) | [GitHub](https://github.com/thomascasali/presentazione-vlan) |
| IPv6 | [Live](https://thomascasali.github.io/presentazione-ipv6/) | [GitHub](https://github.com/thomascasali/presentazione-ipv6) |
| Minacce informatiche | [Live](https://thomascasali.github.io/presentazione-minacce-informatiche/) | [GitHub](https://github.com/thomascasali/presentazione-minacce-informatiche) |
| OOP, programmazione a oggetti | [Live](https://thomascasali.github.io/presentazione-oop/) | [GitHub](https://github.com/thomascasali/presentazione-oop) |
| SQLite | [Live](https://thomascasali.github.io/dispensa-sqlite/) | [GitHub](https://github.com/thomascasali/dispensa-sqlite) |
| Google Workspace | [Live](https://thomascasali.github.io/google-workspace-slides/) | [GitHub](https://github.com/thomascasali/google-workspace-slides) |
| Dare una memoria all'AI | [Live](https://thomascasali.github.io/presentazione-kb-workflow/) | [GitHub](https://github.com/thomascasali/presentazione-kb-workflow) |

## In classe

ITIS: Sistemi e Reti, TPSIT, GPOI, Informatica. Programmazione a oggetti (C#, Java), reti, sicurezza e crittografia, IoT e robotica con ESP32, uso consapevole dell'AI.

## Stack

![Flutter](https://img.shields.io/badge/-Flutter-02569B?style=flat-square&logo=flutter&logoColor=white)
![Firebase](https://img.shields.io/badge/-Firebase-FFCA28?style=flat-square&logo=firebase&logoColor=black)
![React](https://img.shields.io/badge/-React-61DAFB?style=flat-square&logo=react&logoColor=black)
![Vue](https://img.shields.io/badge/-Vue-4FC08D?style=flat-square&logo=vue.js&logoColor=white)
![Node.js](https://img.shields.io/badge/-Node.js-339933?style=flat-square&logo=node.js&logoColor=white)
![Laravel](https://img.shields.io/badge/-Laravel-FF2D20?style=flat-square&logo=laravel&logoColor=white)
![Docker](https://img.shields.io/badge/-Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![MongoDB](https://img.shields.io/badge/-MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)
![MySQL](https://img.shields.io/badge/-MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![C#](https://img.shields.io/badge/-C%23-239120?style=flat-square&logo=c-sharp&logoColor=white)
![Arduino](https://img.shields.io/badge/-Arduino-00979D?style=flat-square&logo=arduino&logoColor=white)

## Contatti

Cesenatico · casali.thomas@gmail.com · [LinkedIn](https://www.linkedin.com/in/thomascasali/)

> *Credo in una tecnologia che serva le persone, nello sport come nella scuola.*
