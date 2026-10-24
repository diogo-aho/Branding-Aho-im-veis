# Logos

> **Pendente:** os arquivos vetoriais originais (AI, SVG ou PDF) ainda não estão no repositório. Peça à KM Designer (sac.kmdesign@gmail.com) os arquivos-fonte do logotipo "Aho", do símbolo e das versões "Aho imóveis".

## Organização esperada

```
logos/
├── fonte/                 ← arquivos originais (.ai, .fig, .pdf)
├── svg/
│   ├── aho-horizontal-preto.svg
│   ├── aho-horizontal-branco.svg
│   ├── aho-horizontal-verde-folha.svg
│   ├── aho-imoveis-vertical-preto.svg
│   ├── simbolo-preto.svg
│   ├── simbolo-branco.svg
│   ├── simbolo-verde-folha.svg
│   └── simbolo-verde-vibrante.svg
└── png/                   ← exportações em 512, 1024 e 2048px, fundo transparente
```

Nome dos arquivos: `<versao>-<cor>.<ext>`, em minúsculas e sem acentos.

Com os SVGs em mãos, as variações de cor podem ser geradas automaticamente a partir dos [tokens](../tokens/cores.json).
