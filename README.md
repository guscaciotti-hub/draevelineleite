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

### Opção 1: GitHub Pages (já configurado)

1. No GitHub, abra **Settings → Pages**.
2. Em **Build and deployment → Source**, escolha **GitHub Actions**.
3. Vá em **Actions**, abra o workflow "Publicar site" e clique em **Run workflow**.

O endereço fica `https://guscaciotti-hub.github.io/draevelineleite/`.
Todo push na branch republica sozinho.

### Opção 2: Netlify (endereço draevelineleite.netlify.app)

Já existe um site chamado `draevelineleite` na conta do Netlify.
Em **Site configuration → Build & deploy → Link repository**, conecte este
repositório. O `netlify.toml` já diz para publicar a raiz sem build.

### Domínio próprio

Nos dois casos dá pra apontar um domínio (ex.: `draevelineleite.com.br`)
nas configurações do host. Em `index.html`, não há nada dependente do endereço.
