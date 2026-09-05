# CSV para tabela LaTeX

> Conversor de arquivos CSV em tabelas LaTeX prontas para documentos, com cabeçalho em negrito, destaque de uma linha e geração opcional do PDF.

![status](https://img.shields.io/badge/status-concluído-success) ![python](https://img.shields.io/badge/Python-3-blue) ![latex](https://img.shields.io/badge/LaTeX-pdflatex-green)

## Sobre
Utilitário criado em 2019 para levar resultados de experimentos direto para a dissertação. A classe `CSV2TEX` monta o preâmbulo, a tabela ajustada à largura da página (`tabularx`/`xcolor`) e, se `generate_pdf=True`, chama `pdflatex`.

## Estrutura de pastas
```text
CSV2LaTeXTable.py          versão script
CSV 2 LaTeX Table.ipynb    versão notebook com exemplo
```

## Como executar
```python
from CSV2LaTeXTable import CSV2TEX
CSV2TEX('resultados.csv', 'resultados.tex', bold_header=True, generate_pdf=True, importan_row_id=10).run()
```

## Status
Concluído.

## Autor
Ronildo Silva · ronildo.comp@gmail.com
