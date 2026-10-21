# F&H TRADER 10.0

Painel macroeconômico gratuito, estático e sem login.

## Publicação gratuita no Cloudflare Pages

1. Acesse https://dash.cloudflare.com/ e crie uma conta gratuita.
2. Abra **Workers & Pages → Create → Pages → Connect to Git**.
3. Autorize o GitHub e selecione `Ferffffffff/fh-trader`.
4. Framework: **None**. Build command: deixe em branco. Output directory: `/` (ou `.` se solicitado).
5. Clique em **Save and Deploy**. O Cloudflare fornecerá um endereço `*.pages.dev`.

## Fontes e limitações

O site incorpora os widgets oficiais públicos do TradingView. A disponibilidade de cada símbolo depende do TradingView e dos acordos de dados da bolsa. Os widgets não fornecem um feed de dados para cálculo do placar macro; por isso o velocímetro permanece neutro, sem cotações ou sinais inventados. O site não utiliza API privada nem scraping não autorizado.

## Arquivos

- `index.html`: página completa, sem dependências de build.

## Atualizações

Novos commits na branch `main` serão publicados automaticamente depois que o repositório for conectado ao Cloudflare Pages.
