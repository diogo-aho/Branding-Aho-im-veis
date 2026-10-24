# Branding Aho imóveis

Repositório central da identidade visual da **Aho imóveis**: guia de marca, cores, tipografia, logotipo, aplicações e o histórico de decisões.

> *"Não estamos aqui para vender propriedades, mas para realizar seus sonhos."*
> Assinatura: **Sonhe, realize, Aho.**

## Status

| Item | Situação |
|---|---|
| Identidade 2023 (KM Designer) | Documentada em [`docs/01-historico-2023.md`](docs/01-historico-2023.md) |
| Nova paleta 2026 | **Aprovada** · [`docs/02-cores.md`](docs/02-cores.md) |
| Tipografia | **Aprovada**: Manrope + Geist Mono · [`docs/03-tipografia.md`](docs/03-tipografia.md) |
| Logotipo e símbolo | Mantidos; Preto musgo como padrão · [`docs/04-logotipo-e-simbolo.md`](docs/04-logotipo-e-simbolo.md) |
| Apresentação Branding 2026 | **Pronta**: 38 slides · [`apresentacao/`](apresentacao/README.md) |
| Arquivos do logo 2026 | 4 tipos × 12 cores, SVG + PNG · [`logos/README.md`](logos/README.md) |

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
├── apresentacao/             ← apresentação Branding 2026 (PDF) + imagens e créditos
├── guia/
│   └── 03-tipografia.pdf     ← guia de tipografia em slides (+ visão geral em PNG)
├── tokens/
│   ├── cores.css             ← variáveis CSS para site e materiais digitais
│   ├── cores.json            ← mesma paleta em JSON (Figma Tokens, Style Dictionary)
│   └── tipografia.css        ← fontes e escala tipográfica
├── logos/                    ← logos 2026 (com fundo e transparentes, SVG + PNG) e originais
└── referencias/
    ├── 2023-km-designer/     ← páginas da apresentação original (JPG)
    └── 2026/                 ← material da revisão atual
```

## Como usar

- **Designers e agências:** comecem por `docs/02-cores.md` e `docs/04-logotipo-e-simbolo.md`.
- **Site e sistemas:** importem `tokens/cores.css` ou `tokens/cores.json`. Não copiem códigos de cor à mão.
- **Mudanças na marca:** abram um pull request explicando o motivo e atualizem `REVISAO.md`.
