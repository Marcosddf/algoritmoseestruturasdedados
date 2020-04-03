# Algoritmos e estruturas de dados


Esta página tem como objetivo apresentar algoritmos e estruturas de dados simples, ilustrados na linguagem C++. Os algoritmos implementados baseiam-se em algoritmos existentes na literatura.

# Notebooks em C++

Os notebooks contém extratos de códigos simples, com a descrição de suas características prinicipais. São recomendados para introdução a algoritmos e estruturas de dados de forma iterativa e rápida.


## Disciplina de algoritmos e estruturas de dados III
Este repositório está sendo usado como material de apoio para disciplina CI1057 - _Algoritmos e estruturas de dados III_, do Departamento de Informática da UFPR. Sugestões, correções de bugs encontrados e contribuições são bem-vindos.

A lista abaixo contém uma ordem sugerida de aprendizado.

- [Ponteiros.ipynb](https://github.com/Marcosddf/algoritmoseestruturasdedados/blob/master/Ponteiros.ipynb)
- [Percurso e operações em árvores binárias.ipááriaynb](https://github.com/Marcosddf/algoritmoseestruturasdedados/blob/master/percuso_operacoes_arvores_binarias.ipynb)
- [Árvore binária de busca.ipynb](https://github.com/Marcosddf/algoritmoseestruturasdedados/blob/master/arvore_binaria_busca.ipynb)
- [Rotações e inclusão na raiz de uma BST.ipynb](https://github.com/Marcosddf/algoritmoseestruturasdedados/blob/master/inclusao_na_raiz_rotacoes.ipynb)
- [Percursos iterativos em BST.ipynb](https://github.com/Marcosddf/algoritmoseestruturasdedados/blob/master/percurso_iterativo.ipynb)
- [Árvore RedBlack - COM nós nulos.ipynb](https://github.com/Marcosddf/algoritmoseestruturasdedados/blob/master/arvore_red_black-nos-nulos.ipynb)
- [Árvore RedBlack - SEM nós nulos.ipynb](https://github.com/Marcosddf/algoritmoseestruturasdedados/blob/master/arvore_red_black-nos-nulos.ipynb)
- [Árvore B (e 2-3-4).ipynb](https://github.com/Marcosddf/algoritmoseestruturasdedados/blob/master/arvore_B.ipynb)
- [Árvore TRIE.ipynb](https://github.com/Marcosddf/algoritmoseestruturasdedados/blob/master/arvore_TRIE.ipynb)
- [Heap e HeapSort.ipynb](https://github.com/Marcosddf/algoritmoseestruturasdedados/blob/master/heap_heap_sort.ipynb)
- [Código de Huffman.ipynb](https://github.com/Marcosddf/algoritmoseestruturasdedados/blob/master/huffman.ipynb)
- [MergeSort](https://github.com/Marcosddf/algoritmoseestruturasdedados/blob/master/merge_sort.ipynb)


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

