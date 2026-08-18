# lumeko-apps

Hub de aplicativos da **Lumeko** — página estática para centralizar os links dos aplicativos publicados na Google Play.

## URL

**https://apps.lumeko.app**

## Stack

- HTML semântico
- CSS puro (sem frameworks)
- Zero JavaScript
- Deploy: Cloudflare Pages

## Aplicativos

| App | Google Play |
|---|---|
| **Orça Obra** | [com.marcos.orcaobra](https://play.google.com/store/apps/details?id=com.marcos.orcaobra) |
| **PDF-Ryou** | [com.marcos.pdfryou](https://play.google.com/store/apps/details?id=com.marcos.pdfryou) |

## Estrutura

```
├── index.html       Página principal
├── style.css        Estilos
├── assets/
│   ├── lumeko-icon-512.png
│   ├── favicon.png
│   ├── orcaobra-icon.png
│   └── pdfryou-icon.png
├── .gitignore
└── README.md
```

## Deploy

Este repositório está conectado ao Cloudflare Pages com deploy automático a partir da branch `main`.

Custom domain: `apps.lumeko.app`

## Adicionar novo aplicativo

1. Adicionar o ícone em `assets/`
2. Copiar um `<article class="app-card">` em `index.html`
3. Atualizar nome, descrição, features e link da Play Store
4. Commit e push — deploy automático

## Lumeko

[lumeko.app](https://lumeko.app) · [@lumeko.dev](https://www.instagram.com/lumeko.dev/)
