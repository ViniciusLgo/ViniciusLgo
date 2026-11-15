# Verificação do rebranding

## Curadoria de stacks, ordem e projetos

Pedido seguinte do usuário: reorganizar o perfil, atualizar stacks e métricas, escolher projetos e preservar bonsai/snake.

- Reconsultados os repositórios públicos, manifesto do MeuSemestre e documentação de SGQ, Microcrédito, portfólio pessoal e RoboEstudo.
- Mantidos quatro projetos públicos principais, com experiência DAX em seção própria e estudos em bloco compacto.
- Stacks organizadas por aplicação; ranking oculto; linguagens em barras compactas; gráfico de contribuições redundante removido.
- Bonsai com largura própria e snake em linha separada para manter a leitura no celular, ambos fora de seções recolhíveis.
- Apresentação substitui a tabela aninhada por texto e badges; links internos de navegação adicionados.
- Doze endereços GitHub retornaram HTTP 200; demo MeuSemestre acessível; assets e âncoras locais conferidos.

Os registros seguintes documentam versões anteriores.

## Correção de identidade solicitada pelo usuário

- Recuperado o README anterior ao rebranding, usando `ee1fba3` como referência.
- Restaurados cabeçalho e rodapé em ondas, texto digitando, badges, contatos, ícones de tecnologias, métricas e apresentação profissional original.
- Bonsai e snake novamente visíveis, sem seção recolhível. Workflows e arquivos de animação preservados.
- Mantidos os quatro projetos originais e adicionados SGQ, Microcrédito, Thiago Guinchos e GuinchoTrack, com ícones no estilo existente.
- Atualizada a stack com C#/.NET, Python, Three.js e Terraform.
- Corrigidas as descrições de notificações do MeuSemestre e de testes do MovieFlix com base na revisão anterior do código.
- Os endpoints antigos de estatísticas retornaram HTTP 402 e o gráfico de atividade retornou HTTP 404. Substituídos por cards SVG funcionais, preservando a seção de métricas.
- Prévia revisada em desktop e celular: bonsai carregado e fora de qualquer seção recolhível, nenhuma imagem quebrada e nenhuma rolagem horizontal da página em 390 px. A tabela original de apresentação mantém rolagem interna no celular.
- Os banners editoriais rejeitados foram removidos. Os registros abaixo se referem à primeira versão, substituída.

## Histórico da primeira versão

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
