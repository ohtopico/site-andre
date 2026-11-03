# Site do André Monteiro Seo

Site estático (um único `index.html`, sem build) para os serviços de impressão 3D, modelagem no Blender e marketing do André em Candelária, Novo Cabrais e região, com vitrine de produtos digitais.

## Publicar no GitHub Pages
1. Settings → Pages → Source: "Deploy from a branch", branch `main`, pasta `/ (root)`.
2. Em "Custom domain" coloque `andreseo.com.br`, salve e marque "Enforce HTTPS" quando liberar.
3. O arquivo `CNAME` deste repositório já aponta para `andreseo.com.br`.

## DNS no Registro.br (andreseo.com.br)
Em registro.br → domínio → "Editar zona" (DNS do Registro.br), crie:

| Tipo  | Nome | Valor |
|-------|------|-------|
| A     | (vazio) | 185.199.108.153 |
| A     | (vazio) | 185.199.109.153 |
| A     | (vazio) | 185.199.110.153 |
| A     | (vazio) | 185.199.111.153 |
| CNAME | www  | ohtopico.github.io |

A propagação leva de minutos até algumas horas. O certificado HTTPS do GitHub sai depois que o DNS propagar.

## Pendências (procure por `TODO` no `index.html`)
- Número real do WhatsApp (texto e link `wa.me`).
- @ real do Instagram.
- Links de checkout dos produtos digitais (Hotmart, Kiwify ou Mercado Pago).
- Confirmar nomes, conteúdos e preços dos produtos.
