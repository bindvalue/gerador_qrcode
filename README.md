# GERADOR_QR_N8N

Projeto estático pronto para deploy no Cloudflare Pages.

## Arquivos principais
- `index.html` — página de entrada do aplicativo.
- `style.css` — estilos separados em arquivo externo.
- `qr_gen.html` — cópia alternativa da página, também referenciando `style.css`.

## Deploy no Cloudflare Pages
1. Crie um repositório Git e envie este projeto.
2. No Cloudflare Pages, conecte o repositório.
3. Configure o diretório de publicação como `/`.
4. Não há comando de build: deixe em branco ou use `none`.

## Observações
- A página usa apenas HTML, CSS e JavaScript estático.
- O formulário envia requisições para os webhooks do n8n.
- O botão "Parar geração" interrompe o polling do QR code.
