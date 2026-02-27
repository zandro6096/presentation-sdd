# SDD - Spec Driven Development & SpecKit ⭐

Apresentação dinâmica criada com **Reveal.js** sobre **SDD (Spec Driven Development)** e **SpecKit**, com tema de **Star Wars** 🌌 e animações.

## 🌐 Ver Online

Acesse a apresentação diretamente pelo GitHub Pages:

👉 **https://zandro6096.github.io/presentation-sdd/**

## ⌨️ Navegação por Teclado

| Tecla | Ação |
|-------|------|
| `→` | Próximo slide |
| `←` | Slide anterior |
| `Space` | Avançar (fragmentos e slides) |
| `Esc` | Visão geral dos slides |
| `F` | Tela cheia |
| `S` | Notas do apresentador |
| `Home` | Primeiro slide |
| `End` | Último slide |

## 📂 Estrutura do Projeto

```
presentation-sdd/
├── index.html                  # Página principal (estrutura HTML)
├── css/
│   └── starwars-theme.css      # 🌌 Tema Star Wars (cores, animações, efeitos)
├── js/
│   └── main.js                 # Inicialização do Reveal.js
├── .github/
│   └── workflows/
│       └── deploy.yml          # Deploy automático no GitHub Pages
├── README.md
└── .gitignore
```

## Como usar localmente

```bash
# Opção 1: abrir diretamente
open index.html

# Opção 2: servir via Python
python3 -m http.server 8080
# Acesse http://localhost:8080
```

## 🎬 Slides

| # | Slide | Descrição |
|---|-------|-----------|
| 1 | ⭐ Título | SDD & SpecKit |
| 2 | 🌌 O que é SDD? | Definição e fluxo |
| 3 | 🛡️ Por que usar SDD? | Benefícios principais |
| 4 | 🔧 O que é SpecKit? | Visão geral da ferramenta |
| 5 | 🚀 `speckit init` | Inicializar projeto |
| 6 | ⚙️ `speckit generate` | Gerar código |
| 7 | ✅ `speckit validate` | Validar especificação |
| 8 | 🎭 `speckit mock` | Servidor mock |
| 9 | 🧪 `speckit test` | Testes de conformidade |
| 10 | 📖 `speckit docs` | Gerar documentação |
| 11 | 🔄 Fluxo SDD | Ciclo completo |
| 12 | 💫 Benefícios | Vantagens do SDD + SpecKit |
| 13 | ⌨️ Navegação | Atalhos de teclado |
| 14 | ⭐ Encerramento | "Que a Spec esteja com você" |

## 🎨 Tema Star Wars

O tema visual fica em `css/starwars-theme.css` e inclui:

- 🌠 Fundo de campo estelar com estrelas animadas
- ⚔️ Efeitos de sabres de luz (azul, verde e vermelho)
- ✨ Cores temáticas (amarelo Jedi, azul, verde, vermelho Sith)
- 📡 Efeito holograma com flicker
- 🔤 Fonte Orbitron com brilho neon

## Tecnologias

- [Reveal.js 5.1.0](https://revealjs.com/) (via CDN)
- HTML5 / CSS3 com animações
- Google Fonts (Orbitron)
- GitHub Pages (deploy automático)