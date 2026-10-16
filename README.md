# cd2tec.github.io

Página da CD2 Tech para devs: projetos open source da CD2 e da comunidade em volta dela.

Publicada em https://cd2tec.github.io pelo GitHub Pages, a partir da raiz do branch padrão.

## Projetos em destaque

- [cd2tec/archeo-harness-plugins](https://github.com/cd2tec/archeo-harness-plugins): plugins que conectam bancos legados de varejo a assistentes de IA via Archeo MCP Creator, para Claude Code, Claude Cowork, Codex e ChatGPT Work.
- [cd2tec/cd2-ia-de-bolso](https://github.com/cd2tec/cd2-ia-de-bolso): CD2 IA de Bolso, a IA da CD2 rodando 100% no seu computador, direto do pen drive, com conexão somente leitura ao seu banco. [Site do projeto](https://cd2tec.github.io/cd2-ia-de-bolso/).
- [nayamonia/wrapper-code](https://github.com/nayamonia/wrapper-code): CLI para rodar o Claude Code com outros provedores de LLM, criada por Gabriel Fernandes, fundador da CD2.

## Outros repositórios (dinâmico)

A seção "Outros repositórios públicos" não tem lista fixa. O navegador consulta a API pública do GitHub (`/orgs/cd2tec/repos?type=public`) e monta os cards, ordenados pelo último push. Ficam de fora forks, repositórios arquivados, o próprio `cd2tec.github.io` e os projetos em destaque (constante `EXCLUDE` no script do `index.html`). Repositório novo que se torna público aparece sozinho; o que volta a ser privado some. O resultado fica em cache por 10 minutos no `sessionStorage`, por causa do limite de requisições sem autenticação da API.

## Estrutura

- `index.html`: página única, HTML e CSS puros, sem build.
- `en/index.html`: versão em inglês da mesma página (https://cd2tec.github.io/en/). O seletor PT / EN no topo liga as duas; ao mudar o texto de uma, atualize a outra.
- `assets/`: logo oficial (cor e negativa) e favicon com o símbolo da marca.
- `.nojekyll`: publica os arquivos como estão, sem processar com Jekyll.

Visual segue o design system CD2 Identidade Visual: Manrope, Blue Retail `#0000ff`, Yellow Like `#dbff2a`, eyebrow com régua, blocos de conexão e botões em pílula.

## Rodar localmente

```sh
python3 -m http.server 8000
```

Abra http://localhost:8000.
