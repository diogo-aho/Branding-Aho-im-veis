# Branding Aho imóveis

Repositório central da identidade visual da **Aho imóveis**: guia de marca, cores, tipografia, logotipo, aplicações e o histórico de decisões.

> *"Não estamos aqui para vender propriedades, mas para realizar seus sonhos."*
> Assinatura: **Sonhe, realize, Aho!**

## Status

| Item | Situação |
|---|---|
| Identidade 2023 (KM Designer) | Documentada em [`docs/01-historico-2023.md`](docs/01-historico-2023.md) |
| Nova paleta 2026 | **Em revisão** · [`docs/02-cores.md`](docs/02-cores.md) |
| Tipografia | Pendente de decisão · [`docs/03-tipografia.md`](docs/03-tipografia.md) |
| Logotipo e símbolo | Mantidos; cores a redefinir · [`docs/04-logotipo-e-simbolo.md`](docs/04-logotipo-e-simbolo.md) |
| Arquivos do logo 2026 | 4 tipos × 10 versões · [`logos/README.md`](logos/README.md) |

As decisões em aberto estão em [`REVISAO.md`](REVISAO.md).

## Estrutura

```
.
├── README.md                 ← você está aqui
├── REVISAO.md                ← pontos da revisão 2026 e decisões pendentes
├── docs/
│   ├── 01-historico-2023.md  ← resumo da identidade original
│   ├── 02-cores.md           ← paleta 2026, proporções, contraste, combinações
│   ├── 03-tipografia.md
│   ├── 04-logotipo-e-simbolo.md
│   ├── 05-tom-de-voz.md
│   └── 06-aplicacoes.md
├── tokens/
│   ├── cores.css             ← variáveis CSS para site e materiais digitais
│   └── cores.json            ← mesma paleta em JSON (Figma Tokens, Style Dictionary)
├── assets/
│   └── paleta-2026.svg       ← quadro da paleta com proporções
├── logos/                    ← SVG, PNG e PDF oficiais do logo (a receber)
└── referencias/
    ├── 2023-km-designer/     ← páginas da apresentação original (JPG)
    └── 2026/                 ← material da revisão atual
```

## Como usar

- **Designers e agências:** comecem por `docs/02-cores.md` e `docs/04-logotipo-e-simbolo.md`.
- **Site e sistemas:** importem `tokens/cores.css` ou `tokens/cores.json`. Não copiem códigos de cor à mão.
- **Mudanças na marca:** abram um pull request explicando o motivo e atualizem `REVISAO.md`.
