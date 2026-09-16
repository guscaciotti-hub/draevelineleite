# Dra. Eveline Leite — link da bio

Página única (HTML, CSS e JS puro) usada como link na bio do Instagram.

- `index.html` — a página
- `assets/avatar.jpg` — foto de perfil
- `assets/marca.png` — marca ao fundo do cabeçalho
- `assets/favicon.svg` — ícone da aba

## Como editar

Os botões ficam dentro das seções `#paciente` e `#dentista` em `index.html`.
Cada botão é um `<a class="btn">` com o link no `href`. Os links de WhatsApp
já vêm com a mensagem pré-preenchida no parâmetro `text`.

Cores e fontes estão no bloco `:root` do CSS, no topo do arquivo.

## Publicar

Não precisa de build. Qualquer host de site estático serve: Vercel, Netlify,
GitHub Pages ou Cloudflare Pages. Basta apontar para a raiz do repositório.
