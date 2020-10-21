<p align="center">
  <img src="imagens/logo-cnj.jpg" alt="Unform" />
</p>

<h3 align="center">
  HACKATHON CNJ 2020 🚀
</h3>

## Overview

Os "notebooks" presentes neste repositório geram as Matrizes de Movimentos Predecessores referentes a cada um dos tribunais disponíveis. Para tanto, são utilizados os arquivos JSON disponibilizados pela organização do Hackaton, que contêm os dados referentes aos processos judiciais cadastrados. Para tanto, os notebooks referentes a cada uma das quatro etapas devem ser executados de forma sequêncial em uma pasta contendo os arquivos JSON referentes a um determinado tribunal, sendo repetido o procedimento para todos os demais tribunais.

Como exemplo, estão presentes neste repositório os arquivos JSON referentes ao TJAC. Como "output" das etapas 01, 02, 03 e 04, são gerados os seguintes arquivos:

  - dfPreliminar.csv
  - dfFinalCivel.csv
  - matrizPredecessor*.json
  
Todos os arquivos com nome no padrão matrizPredecessor*.json (exemplo: matrizPredecessorTJAC.json) gerados devem ser reunidos numa mesma pasta, para que sejam executadas as etapas posteriores, disponíveis em https://github.com/oitentaetres/Hackaton_CNJ_Parte_02 .

## Installation

A linguagem de programção utilizada nesse desenvolvimento foi o Python, por isso caso não possua instalado, pode instalar nesse link: https://www.python.org/downloads/ .

Recomendo instalar também o Anaconda, que possui o ambiente Jupyter Notebook, que foi utilizado no desenvolvimento. Download nesse link: https://www.anaconda.com/products/individual .

Para instalar as bibliotecas python utilizadas, em um console, utilize o comando "pip".

Exemplo:

```
>>> pip install -U pandas
```

Lista de bibliotecas utilizadas nessas etapas:

  - pip install -U ast
  - pip install -U glob
  - pip install -U json
  - pip install -U math
  - pip install -U os
  - pip install -U pandas
  
  
