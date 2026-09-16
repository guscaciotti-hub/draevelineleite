# Dra. Eveline Leite

Site estático (HTML, CSS e JS puro), publicado no Vercel.

| Rota   | O que é                                  |
|--------|------------------------------------------|
| `/bio` | Link da bio do Instagram (`bio/index.html`) |
| `/`    | Landing page (ainda não existe; por enquanto redireciona para `/bio`) |

## Estrutura

- `bio/index.html` — página de links
- `bio/assets/` — foto de perfil, marca e favicon
- `vercel.json` — URLs limpas, redirecionamento da raiz e cabeçalhos

## Como editar a bio

Os botões ficam nas seções `#paciente` e `#dentista` de `bio/index.html`.
Cada botão é um `<a class="btn">` com o link no `href`. Os links de WhatsApp
já vêm com a mensagem pré-preenchida no parâmetro `text`.
Cores e fontes estão no bloco `:root` do CSS, no topo do arquivo.

## Landing page

Quando a landing page existir, coloque-a em `index.html` na raiz e remova o
redirecionamento de `/` em `vercel.json`. O link da bio continua em `/bio`.

## Publicar

No Vercel, importe este repositório (Add New → Project → Import). Não há
build: framework "Other", diretório de saída vazio. Cada push na branch de
produção publica sozinho.
