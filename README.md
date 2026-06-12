# Design System Acessível para Baixa Visão

Design System acessível e protótipo de alta fidelidade voltados a usuários com **baixa visão**, desenvolvidos com base em princípios de **UX** e nas diretrizes **WCAG**. O objetivo é apoiar equipes de design e desenvolvimento na construção de interfaces digitais mais inclusivas.

> Artefato resultante do trabalho *"Design System acessível como estratégia de inclusão digital: uma abordagem baseada em UX para usuários com baixa visão"*, conduzido pelo método Design Science Research (DSR).

---

## Por que este projeto existe

Em 2024, levantamento da BigDataCorp em parceria com o Movimento Web para Todos mostrou que apenas **2,9%** dos sites brasileiros foram aprovados em todos os testes de acessibilidade aplicados. Esses testes verificam, entre outros aspectos, contraste mínimo, texto alternativo, rotulação de formulários, foco visível e estrutura semântica — exatamente as barreiras que mais afetam usuários com baixa visão.

A literatura já diagnostica bem essas barreiras, mas raramente as traduz em soluções sistematizadas e reutilizáveis. Este repositório preenche essa lacuna: transforma o diagnóstico em **tokens, componentes e padrões de interação** documentados, deslocando a acessibilidade de uma etapa corretiva para uma propriedade estrutural do projeto.

## O que tem aqui

| Pasta | Conteúdo |
|---|---|
| [`tokens/`](tokens/) | Tokens de design (cor, tipografia, espaçamento) em formato reutilizável |
| [`docs/`](docs/) | Guia de estilo: visão geral, tokens, componentes e mapeamento WCAG |
| [`docs/componentes/`](docs/componentes/) | Especificação dos 6 componentes, com estados e anotações de acessibilidade |
| [`prototipo/`](prototipo/) | Link do protótipo no Figma e telas exportadas |
| [`diagramas/`](diagramas/) | Mapa do site e fluxogramas de tarefa |
| [`pesquisa/`](pesquisa/) | Matriz de barreiras, avaliação de navegação, checklist e auditorias |
| [`artigo/`](artigo/) | Versão final do artigo (PDF) |

> **Nota:** as pastas `tokens/` e `artigo/` ainda precisam receber seus arquivos. Os documentos `.md` deste repositório já estão prontos.

## Como reutilizar

Este Design System foi pensado para ser inspecionado, reutilizado e adaptado. O caminho recomendado:

1. **Importe os tokens.** Consuma `tokens/cores.css` (variáveis CSS) ou `tokens/tokens.json` (formato de Design Tokens) no seu projeto. É a partir deles que contraste, tipografia e espaçamento entram na sua interface.
2. **Consulte cada componente.** Em [`docs/componentes/`](docs/componentes/), cada componente traz especificação, estados visuais e anotações de acessibilidade para implementação em código.
3. **Rastreie cada decisão.** O arquivo [`docs/mapeamento-wcag.md`](docs/mapeamento-wcag.md) liga cada barreira ao critério WCAG e ao componente que a resolve.
4. **Abra o protótipo.** Duplique componentes e telas direto no Figma (link em [`prototipo/`](prototipo/)).
5. **Valide.** Use o checklist em [`pesquisa/`](pesquisa/) para verificar a conformidade da sua implementação.

## Protótipo no Figma

Protótipo de alta fidelidade navegável:

🔗 https://www.figma.com/design/4pSnEk9FHmJxpGM9FUaanA/TCC-II---Design-System-e-Prot%C3%B3tipo?node-id=0-1&t=2CxUGE3rGojH299V-1

## Avaliação

O artefato foi avaliado por um **Checklist de Conformidade Heurística com 110 itens**, em seis categorias, com escala ordinal de 0 a 2. Resultado global: **94,5% de conformidade** (104 itens plenamente atendidos, 6 parcialmente, nenhum não atendido). As categorias Contraste e Legibilidade, Formulários e Feedback e Conteúdo e Multimídia atingiram 100%.

## Como citar

Use o arquivo `CITATION.cff` na raiz do repositório (o GitHub exibe um botão **"Cite this repository"** automaticamente). Referência sugerida:

> MOREIRA, Ana Beatriz Marques; RIBEIRO, Tayse Virgulino. Design System acessível como estratégia de inclusão digital: uma abordagem baseada em UX para usuários com baixa visão. *Revista Sociedade Científica*, v. 9, n. 1, 2026.

## Licença

Material disponibilizado sob licença de uso livre. Sugestão: **Creative Commons Attribution 4.0 (CC BY 4.0)** para documentação e design, permitindo uso, adaptação e redistribuição mediante atribuição. Adicione o arquivo `LICENSE` correspondente à raiz do repositório.

## Autoria

- **Ana Beatriz Marques Moreira** — anamarques@unitins.br
- **Tayse Virgulino Ribeiro** — taysevr@unitins.br

Universidade Estadual do Tocantins (UNITINS), Palmas, Brasil.

## Alinhamento com os ODS

O projeto contribui para os Objetivos de Desenvolvimento Sustentável da ONU:

- **ODS 4 — Educação de Qualidade:** oferece um modelo transferível para contextos informacionais e educacionais.
- **ODS 9 — Indústria, Inovação e Infraestrutura:** opera como infraestrutura projetual reutilizável.
- **ODS 10 — Redução das Desigualdades:** reduz barreiras de acesso à informação e aos serviços digitais para pessoas com baixa visão.
