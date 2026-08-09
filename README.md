# Faladoc

Aplicação web do ecossistema FALADOC IA, voltada a médicos como usuários finais.

## Stack

- [Next.js 16](https://nextjs.org) (App Router, Turbopack)
- React 19 + TypeScript
- Tailwind CSS v4
- ESLint (`eslint-config-next`)

## Como rodar

Requer Node.js 22+.

```bash
npm install
npm run dev
```

A aplicação sobe em http://localhost:3000.

## Scripts

| Comando | Descrição |
| --- | --- |
| `npm run dev` | Servidor de desenvolvimento |
| `npm run build` | Build de produção |
| `npm start` | Serve o build de produção |
| `npm run lint` | Checagem de lint |

## Estrutura

```
src/app/         Rotas e layouts (App Router)
src/app/globals.css  Estilos globais e tokens do Tailwind
public/          Arquivos estáticos
```

## Status

Projeto em fase inicial: base técnica configurada, escopo funcional em definição.
