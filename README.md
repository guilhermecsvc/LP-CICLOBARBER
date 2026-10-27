# LP CicloBarber

Landing page do CicloBarber (arquivo único, sem etapa de build).

- `public/index.html`: a página. Configurações (WhatsApp, formulário etc.) ficam no objeto `CONFIG` dentro dele.
- `public/_headers`: cabeçalhos de segurança aplicados pelo Cloudflare.
- `wrangler.jsonc`: diz ao Cloudflare (Workers) para publicar a pasta `public/`.
- Este repositório é público: nunca coloque chaves, senhas ou tokens aqui.
