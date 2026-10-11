# cd2tec.github.io

Página da CD2 Tech para devs: projetos open source da CD2 e da comunidade em volta dela.

Publicada em https://cd2tec.github.io pelo GitHub Pages, a partir da raiz do branch padrão.

## Projetos em destaque

- [cd2tec/archeo-claude-plugins](https://github.com/cd2tec/archeo-claude-plugins): plugins para Claude Code que conectam bancos legados de varejo a assistentes de IA via Archeo MCP Creator.
- [nayamonia/wrapper-code](https://github.com/nayamonia/wrapper-code): CLI para rodar o Claude Code com outros provedores de LLM, criada por Gabriel Fernandes, fundador da CD2.

## Estrutura

- `index.html`: página única, HTML e CSS puros, sem build.
- `assets/`: logo oficial (cor e negativa) e favicon com o símbolo da marca.
- `.nojekyll`: publica os arquivos como estão, sem processar com Jekyll.

Visual segue o design system CD2 Identidade Visual: Manrope, Blue Retail `#0000ff`, Yellow Like `#dbff2a`, eyebrow com régua, blocos de conexão e botões em pílula.

## Rodar localmente

```sh
python3 -m http.server 8000
```

Abra http://localhost:8000.
