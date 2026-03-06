# Deploy no Cloudflare

## Pré-requisitos

- Node.js instalado
- Conta no Cloudflare

## Passos

### 1. Login no Cloudflare

```bash
npx wrangler login
```

Isso abre o navegador para autenticar.

### 2. Build do projeto

```bash
npm run build
```

### 3. Deploy

```bash
npx wrangler deploy
```

## URL do projeto

https://lauraricarte-com.dralauraricarte.workers.dev
