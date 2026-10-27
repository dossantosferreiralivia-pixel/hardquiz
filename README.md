# HardQuiz

Quiz de múltipla escolha sobre **hardware de computadores**, desenvolvido como trabalho acadêmico (CP1 — estrutura e design).

## Tema

**Hardware**: processador, memória RAM, armazenamento (HD/SSD), placa-mãe, placa de vídeo e fonte de alimentação.

## Integrantes

| Nome | GitHub |
|------|--------|
| Lívia Ferreira | @dossantosferreiralivia-pixel |
| Vinicius Marques | @viniciusmarquesdemendonca@gmail.com |
| Hugo Trindade | @hugotrindad3 |
| Alexandre de Paiva Vicco Fontes Junior | @alexandreneagle-blip |

## Links

- Site publicado: https://GRUPO.github.io/hardquiz/
- Repositório: https://github.com/dossantosferreiralivia-pixel/hardquiz

## Estrutura do projeto

```
hardquiz/
├── index.html        # página inicial
├── jogo.html         # estrutura da tela de jogo
├── perguntas.json    # banco de perguntas (contrato para o CP2)
├── css/
│   └── style.css     # identidade visual e CSS base
├── README.md
└── .gitignore
```

## Como executar

1. Clone o repositório: `git clone https://github.com/GRUPO/hardquiz.git`
2. Abra a pasta e dê dois cliques em `index.html` (ou use a extensão Live Server do VS Code).
3. Navegue entre a página inicial e a tela de jogo.

> No CP1 não há lógica de jogo: a tela `jogo.html` mostra apenas a estrutura. O JavaScript será adicionado no CP2.

## Formato do `perguntas.json`

Cada questão tem:

| Campo | Tipo | Descrição |
|-------|------|-----------|
| `id` | número | identificador da questão |
| `pergunta` | texto | enunciado |
| `alternativas` | lista de textos | opções de resposta |
| `resposta` | número | índice (começando em 0) da alternativa correta |
| `explicacao` | texto | explicação exibida no feedback |
| `fonte` | link | referência da informação |

## Identidade visual

- **Paleta:** azul placa `#0e2a47`, azul profundo `#07182b`, dourado `#f2c14e`, azul trilha `#3e7cb1`, branco serigrafia `#f3f6f8`.
- **Tipografia:** Chakra Petch (títulos) e IBM Plex Sans (texto).

## Fluxo de trabalho (Git)

- Uma branch por integrante: `feature/pagina-inicial`, `feature/tela-jogo`, `feature/estilo-base`, `feature/perguntas-json`.
- Ninguém faz commit direto na `main`.
- Sempre começar com `git pull origin main`; nunca usar `push --force` na `main`.
- Entrega marcada com a tag `cp1-entrega`.
