# Verificação do rebranding

Data: 15/11/2026. Desenvolvimento: `feat/profile-rebranding`. Entrega: `main`.

## Verificado

- Banners desktop e mobile válidos como XML/SVG, com título e descrição.
- Todos os assets locais referenciados pelo README existem.
- Os 12 endereços únicos de projetos, arquivos e animações consultados retornaram HTTP 200.
- Links internos correspondem aos títulos das seções.
- Markdown convertido pela API oficial do GitHub e visualizado localmente com `github-markdown-css`.
- Inspeção visual em desktop (1280 px) e celular (390 px), nos temas claro e escuro.
- Verificação adicional em 320 px: sem overflow horizontal e banner mobile selecionado.
- `git diff --check` sem erros.

## Limites

A prévia local simula o estilo do GitHub e adiciona IDs aos títulos para navegação. A renderização final no perfil público só pode ser conferida após publicação. As aplicações dos projetos destacados não foram executadas nesta entrega. As informações profissionais foram preservadas a partir do README anterior, sem verificação independente.

## Publicação

Publicação direta na `main` autorizada pelo usuário. README e banners entregues no repositório público do perfil. Bio e pins não fazem parte do push: as sugestões de configuração da conta estão em [perfil-github.md](perfil-github.md).
