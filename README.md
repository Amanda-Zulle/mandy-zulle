# Flyer de Massagens — Amanda Zulle

Flyer digital em HTML/CSS para divulgação de serviços de massagem ao domicílio.

## Estrutura do Projeto

```
├── index.html       — Página principal
├── style.css        — Estilos base (desktop)
├── responsive.css   — Adaptações para mobile (≤ 500px)
└── amanda.png       — Foto de perfil
```

## Como usar

1. Coloca todos os ficheiros na mesma pasta.
2. Abre `index.html` no browser.

> **Nota:** A foto `amanda.png` deve estar na mesma pasta que o `index.html`.

## Fontes utilizadas

Carregadas automaticamente via Google Fonts:
- **Cormorant Garamond** — títulos e preços
- **Jost** — corpo de texto
- **Montserrat** — número de telefone

## Personalização

| O que alterar | Onde |
|---|---|
| Nome, telefone, zona | `index.html` |
| Preços e descrições | `index.html` |
| Cores e espaçamentos | `style.css` (variáveis CSS em `:root`) |
| Foto | Substituir `amanda.png` |

## Responsividade

O layout é idêntico em desktop e mobile — em ecrãs pequenos apenas os tamanhos de fonte e espaçamentos são reduzidos, sem alterar a estrutura visual.
