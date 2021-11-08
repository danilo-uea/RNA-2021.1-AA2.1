# RNA-2021.1-AA2.1
## Atividade Avaliativa 2.1
* Instituição: Universidade do Estado do Amazonas - UEA
* Curso: Engenharia de Computação
* Disciplina: Redes Neurais Artificiais
* Docente: Elloá B. Guedes
* Equipe: Danilo Frazão, Rafael Aragão & Yasser Tuma

## Definição
Neste projeto prático, o objetivo é implementar o algoritmo de treinamento mediante Aprendizado Supervisionado do neurônio Perceptron de Rosenblatt aplicado em problemas de classificação.

## Tecnologias
Esta atividade foi desenvolvida em Python por meio do Google Colab [Acesso ao Colab](https://colab.research.google.com/github/danilo-uea/RNA-2021.1-AA2.1/blob/main/RNA_AA_2_1.ipynb). Cada equipe deverá elaborar Jupyter Notebooks com o código-fonte deste algoritmo de treinamento desenvolvido na linguagem de Programação Python e fazendo uso das bibliotecas numpy, random, math e matplotlib. Em particular, a biblioteca numpy será de uso obrigatório para todas as operações de natureza matricial (multiplicação de matrizes, produto escalar, etc). Neste projeto prático, a biblioteca sci-kit learn não deve ser utilizada.

## DataSet
Os DataSets usados nesta atividade foram disponibilizados no google drive [Link do DataSet](https://drive.google.com/drive/folders/1111maX048CuvEJDx2d8X39z6tq3DXHB6?usp=sharing).
Todas as atividades tem como entrada um arquivo txt com conteúdo em binário descrevendo um numpy.ndarray salvo previamente contendo múltiplos exemplos de dimensões (1,3), ou seja, tem dimensões (m,1,3), em que m varia a depender do documento considerado, de 800 a 1000, em média. Cada exemplo representa um ponto no R2 e o seu respectivo rótulo, isto é, tem-se (x1,x2,yd). Os valores de yd correspondem às classes discretas e binárias 0 e 1, em que a classe 0 deve ser denotada na cor vermelha e a classe 1 deve ser denotada na cor azul.
