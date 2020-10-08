# Tutorial de OpenCV com Python e Jupyter

Este repositório contém um tutorial básico de [OpenCV](https://opencv.org/) utilizando a lingaugem [Python](https://www.python.org/) através de [Jupyter notebooks](https://jupyter.org/). Nele são abordadas as funções básicas da biblioteca.

## Conteúdo

Os assuntos abordados no tutorial são:

 - Carregamento e exibição de imagens
 - Transformação em escala de cinza
 - Binarização
 - Adição de elementos
 - Transformações geométricas
 - Operações aritméticas
 - Exibição de histogramas

## Como reproduzir?

Para reproduzir, basta executar os seguintes passos:

0. Clonar o repositório usando o git:

```
git clone https://github.com/romulofff/tutorial-opencv.git
```

1. Instalar o [Poetry](www.python-poetry.org/) através deste [tutorial](https://python-poetry.org/docs/#installation).
2. Instalar as bibliotecas utilizadas no tutorial e criar o ambiente virtual usando
```
poetry install
```
2. Navegar até a pasta `notebooks/` e executar o jupyter lab via poetry:
```
poetry run jupyter lab
```
