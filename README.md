# 🖥️ Admin Panel — Cybersecurity Dashboard

> Painel de administração pessoal com estética hacker/terminal para profissionais de cybersecurity.

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)
![Single File](https://img.shields.io/badge/Single_File-0a0a0a?style=flat)

## O que é?

Um dashboard single-file HTML que centraliza **60+ ferramentas** de cybersecurity, OSINT, forense digital, redes, CTF e desenvolvimento — com mural de notícias integrado, Keep Notes, Pomodoro e widgets em tempo real.

Zero dependências. Zero servidor. Abre direto no navegador.

## ⚡ Features

- **60+ ferramentas** em 6 categorias (Chat/AI, OSINT, Network, Forensic, CTF, Dev)
- **Mural de notícias** com iframes navegáveis + links rápidos para portais de cybersec
- **Keep Notes** — notas coloridas, checklists, fixar, busca (estilo Google Keep)
- **Gerenciamento dinâmico** — adicionar e remover ferramentas a qualquer momento
- **3 temas visuais** — Green Hacker, Cyberpunk Cyan, Retro Amber
- **Matrix rain** animado com cor adaptativa ao tema
- **Timer Pomodoro** com notificações do navegador
- **Status bar** — IP público, ping, clima, uptime em tempo real
- **Busca** com Ctrl+K e normalização de acentos
- **Notepad** com auto-save
- **100% client-side** — tudo salvo no localStorage

## 🛠️ Categorias

| Categoria | Ferramentas | Destaques |
|-----------|:-----------:|-----------|
| Chat · AI | 12 | ChatGPT, Gemini, Grok, DeepSeek, Manus |
| Investigação · OSINT | 16 | VirusTotal, Shodan, MITRE ATT&CK, Censys |
| Redes · Network | 8 | Speedtest, MXToolbox, Nmap Online, IPinfo |
| Forense · Analysis | 9 | CyberChef, ANY.RUN, ExploitDB, MalwareBazaar |
| CTF · Challenges | 7 | Hack The Box, TryHackMe, PortSwigger |
| Dev · Tools | 8 | GitHub, Regex101, Postman, Excalidraw |

## 🚀 Como usar

1. Baixe o arquivo `admin-panel.html`
2. Abra no Chrome
3. (Opcional) Configure como página inicial: `Configurações > Inicialização > Abrir página específica`

```
file:///C:/Users/SeuUsuario/Documents/admin-panel.html
```

## 🎨 Preview

- **Layout split 50/50**: ferramentas à esquerda, mural de notícias à direita
- **Terminal header**: `root@hypnosgasp:~/admin-panel█`
- **CRT scanlines** + **matrix rain** + **glow effects**

## 📋 Stack

- HTML5 + CSS3 + Vanilla JS (single-file, ~360 linhas)
- Google Fonts (Fira Code + Share Tech Mono)
- APIs: ipify (IP), Open-Meteo (clima)
- Canvas 2D (matrix rain)
- localStorage (persistência)

## 📝 Licença

Uso pessoal. Feito por **Hypnosgasp**.

---

*Built with ☕ and a terminal mindset.*
