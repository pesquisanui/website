# Website da Pesquisa de Núcleos Urbanos Informais (PNUI)

O website foi desenvolvido utilizando o sistema de publicação científica e técnica de código aberto [Quarto](https://quarto.org/) e o Bootstrap Framework (CSS + html + JavaScript).

Os arquivos estão organizados da seguinte forma:

    .
    ├── assets                   # Arquivos adicionais -- figuras, dados, metadados
    ├── docs                    # Website após renderização (NÃO EDITAR)
      [Configuração]
    ├── .gitignore
    ├── _quarto.yml                     # Configurações do website
    ├── styles.css                    # Configurações adicionais
    ├── styles.scss                   # Configurações adicionais
    ├── website.Rproj
      [Páginas]
    ├── index.qmd                   # Página inicial
    ├── explorar.qmd                   # Explorar
    ├── dados.qmd                   # Dados
    ├── publicacoes.qmd                   # Publicações
    ├── equipe.qmd                   # Equipe
    ├── 404.qmd                   # 404
      [Documentação]
    └── README.md                   

A versão atual do website está publicada na pasta `docs`. Recomendamos não editar os arquivos hospedados nessa pasta -- após a renderização utilizando o Quarto, esses arquivos são substituídos e todas as alterações feitas nos arquivos dessa pasta são perdidas. O desenvolvimento do website deve ser feito utilizando os arquivos hospedados na raíz e pasta `assets` (todos os arquivos fora da pasta `docs`).
