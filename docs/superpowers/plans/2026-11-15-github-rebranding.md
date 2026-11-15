# GitHub Rebranding Implementation Plan

> Histórico: a direção editorial foi substituída pelo usuário. A entrega atual restaura o README original e adiciona projetos, tecnologias e correções de links, preservando seus elementos visuais. Os banners editoriais foram removidos.

> Execução nesta sessão, com revisão dos arquivos e da renderização entre os blocos.

**Goal:** Aplicar a proposta editorial aprovada ao perfil ViniciusLgo.

**Architecture:** Markdown nativo para conteúdo e navegação; dois banners SVG locais para desktop e celular. Sem dependências de execução novas no repositório.

**Tech Stack:** GitHub Flavored Markdown, HTML compatível com README e SVG.

## Restrições

- Azul profundo #101B2D, verde #7DE2C5, texto #F3F6FA e secundário #B6C4D6.
- Português; projetos públicos verificáveis; estudos e protótipos identificados.
- Manter bonsai e snake em seção recolhível, sem alterar seus workflows.
- Preservar contatos existentes e não publicar informações internas novas.

## Execução

- [x] Criar `assets/brand/header.svg` e `assets/brand/header-mobile.svg`, com título e descrição acessíveis. Validar ambos como XML.
- [x] Reescrever `README.md` usando o texto aprovado: abertura, quatro projetos principais, dois complementares, competências aplicadas, experiência e contato.
- [x] Criar `docs/perfil-github.md` com bio e ordem dos pins prontas para aplicar, diferenciando configurações da conta e conteúdo do README.
- [x] Atualizar o estado da proposta em `docs/rebranding-proposta.md`.
- [x] Renderizar uma prévia local com Markdown convertido e estilo equivalente ao GitHub; revisar desktop e celular, temas claro e escuro, ausência de overflow e links/assets locais.
- [x] Executar `git diff --check` e revisar o diff final. Registrar limites da verificação e estado de publicação.

## Validação

Não criar suíte de testes para conteúdo estático. Usar parsing XML, conferência de links, inspeção visual e revisão de conteúdo. A prévia local não substitui a renderização real do GitHub após publicação.
