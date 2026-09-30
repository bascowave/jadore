# J'Adore Floral Designers — Landing (preview)

Landing page estática para apresentação ao cliente e deploy no [Coolify](https://coolify.io).

## Conteúdo

- `index.html` — página principal
- `assets/` — logo e assets locais
- `j-adore-design-system.md` — tokens, tipografia e direção visual

## Deploy no Coolify

### Opção A — Dockerfile (recomendado)

1. Nova aplicação → **Public Repository** → URL deste repositório GitHub
2. Tipo de build: **Dockerfile**
3. Porta exposta: **3000**
4. Deploy

### Opção B — Site estático

1. Nova aplicação → repositório GitHub
2. Build pack estático apontando para a raiz (`index.html`)

## Desenvolvimento local

Abra `index.html` no browser ou sirva a pasta:

```bash
npx --yes serve .
```

## Notas

As fotografias do portfólio usam URLs externas (Casamentos.pt, MAIS/Semanário). É necessário ligação à internet para carregar todas as imagens.
