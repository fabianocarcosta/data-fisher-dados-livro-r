# Dados do Guia Data Fisher de Programação em R

Este repositório reúne os arquivos CSV usados nos exemplos e exercícios do **Guia Data Fisher de Programação em R**, de Fabiano C. Costa.

## Arquivos

| Arquivo | Conteúdo |
| --- | --- |
| `vendas_datafisher.csv` | Registros didáticos de vendas e projetos de consultoria, com serviços, regiões, horas, descontos, valores e avaliações. |
| `pesquisa_satisfacao.csv` | Base didática de pesquisa de satisfação, com variáveis demográficas, NPS, recomendação e cancelamento. |
| `simulacao_jogos.csv` | Ensaios de moeda e dado para exemplos de aleatoriedade e probabilidade. |

Os dados foram preparados para fins educacionais. Os identificadores são códigos fictícios e os registros não devem ser interpretados como dados operacionais ou pesquisa real.

## Baixar

- [Baixar todos os arquivos (ZIP)](https://github.com/fabianocarcosta/data-fisher-dados-livro-r/archive/refs/heads/main.zip)
- [vendas_datafisher.csv](https://raw.githubusercontent.com/fabianocarcosta/data-fisher-dados-livro-r/main/vendas_datafisher.csv)
- [pesquisa_satisfacao.csv](https://raw.githubusercontent.com/fabianocarcosta/data-fisher-dados-livro-r/main/pesquisa_satisfacao.csv)
- [simulacao_jogos.csv](https://raw.githubusercontent.com/fabianocarcosta/data-fisher-dados-livro-r/main/simulacao_jogos.csv)

## Uso no R

Depois de baixar o ZIP e extraí-lo, carregue os arquivos com `read.csv()`:

```r
vendas <- read.csv("data/vendas_datafisher.csv", stringsAsFactors = FALSE)
pesquisa <- read.csv("data/pesquisa_satisfacao.csv", stringsAsFactors = FALSE)
jogos <- read.csv("data/simulacao_jogos.csv", stringsAsFactors = FALSE)
```
