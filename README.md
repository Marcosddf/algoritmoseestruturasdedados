# Algoritmos e estruturas de dados


Esta página tem como objetivo apresentar algoritmos e estruturas de dados simples, ilustrados na linguagem C++. Os algoritmos implementados baseiam-se em algoritmos existentes na literatura.

O objetivo não é descrever todos os detalhes de implementação da linguagem. Para isto tutoriais específicos da linguagem são mais adequados.

# Notebooks em C++

Os notebooks contém extratos de códigos simples, com a descrição de suas características prinicipais. São recomendados para introdução a algoritmos e estruturas de dados de forma iterativa e rápida.


## Disciplina de algoritmos e estruturas de dados III
Este repositório está sendo usado como material de apoio para disciplina CI1057 - _Algoritmos e estruturas de dados III_, do Departamento de Informática da UFPR. Sugestões, correções de bugs encontrados e contribuições são bem-vindos.

## Cópia do repositório

Este repositório pode ser copiado e estendido.

## Execução

Para a execução dos Notebooks, estes deverão ser carregados e iniciados online usando o link abaixo:

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/Marcosddf/algoritmoseestruturasdedados/master)

Também poderá ser feita uma instalação local para execução mais rápida. As instruções detalhadas estão disponíveis no link https://github.com/jupyter-xeus/xeus-cling/. Um passo-a-passo está descrito abaixo.




## Instalação e execução local usando o conda

Baixar o script de instalação do Miniconda https://docs.conda.io/en/latest/miniconda.html, adicionar permissão de execução `chmod +x Miniconda3-latest-Linux-x86_64.sh` e executar o script 

Criar ambiente 'cling'

```
conda create -n cling
conda activate cling  # Or `source activate cling` for conda < 4.6
```

Instalar o ambiente `xeus-cling` e dependências

```
conda install xeus-cling -c conda-forge
```

Instalar o front-end do Jupyter.

```
conda install notebook -c conda-forge
```

Executar o `jupyter notebook` no diretório onde tiver baixado os arquivos.

Copiar do console a URL com o token, para abrir o ambiente no navegador.

O ambiente `cling` deverá ser ativado sempre que um novo terminal for aberto.

