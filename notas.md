
<img src="https://i.ibb.co/vLTswQJ/quebra-cabeca.png" alt="Lógica" width="140">


# Lógica de Programação

## Índice

- [Introdução ao curso de Lógica](#introducao-ao-curso-de-logica)
  - [Algoritmos](#algoritmos)
  - [Diagramas de Blocos](#diagrama-de-blocos)
  - [Pseudocódigo](#pseudocodigo)
    - [Regras para construção](#regras-para-construcão)
 - [Entrada de dados](#entrada-de-dados)
  - [O que é uma função?](#o-que-e-uma-funcao)
  - [Como funciona?](#como-funciona)
- [Fluxogramas](#fluxogramas)
- [Tipos de Dados](#tipos-de-dados)
  - [Constantes](#constantes)
  - [Variáveis](#variáveis)
    - [Tipos de variáveis](#tipos-de-variáveis)



  
## Introdução ao curso de Lógica

A **lógica de programação** e a utilização de algoritmos são a estrutura básica para o desenvolvimento de programas, pois ele é construído sem vínculo a nenhuma linguagem de programação. Sendo assim, tudo o que será aprendido sobre lógica de programação e a construção de algoritmos pode ser usado para qualquer linguagem de programação.

> "Lógica de programação é a técnica de encadear pensamentos, em uma sequência de instruções que devem ser seguidas, para atingir determinado objetivo."

Uma **instrução** é a unidade básica de informação que indica ao computador uma ação elementar a ser executada. Contudo, uma instrução isolada pode não ser suficiente para alcançar um objetivo útil; é necessário um conjunto de instruções organizadas de forma lógica e coerente. Esse conjunto, quando estruturado adequadamente, permite que o computador realize tarefas específicas, levando a resultados desejados.

> "Sequência lógica são passos executados até atingir um objetivo ou solução de um problema."

### Algoritmos

Um algoritmo é uma sequência finita de passos, ordenados de forma lógica, que levam a execução de uma tarefa.

Por exemplo: 
#### **Algoritmo: Cálculo da Média de Dois Números**

1. **Início**
2. Solicitar ao usuário que informe o primeiro número e armazená-lo em uma variável chamada `numero1`.
3. Solicitar ao usuário que informe o segundo número e armazená-lo em uma variável chamada `numero2`.
4. Calcular a média somando os dois números e dividindo por 2, armazenando o resultado em uma variável chamada `media`.
5. Exibir o valor da `media` ao usuário.
6. **Fim**

Existem diferentes formas de representar um algoritmo:

Linguagem natural: A que usamos no dia a dia.
Diagramas de blocos: Usam formas geométricas diferentes para as diversas ações.
Pseudocódigo: Representação próximo a escrita de programas.

### Diagramas de Blocos

A principal função, do diagrama de blocos é a de facilitar a visualização dos passos de um procedimento. 

É a forma gráfica padronizada e eficaz para representar os passos lógicos de um determinado processamento. Com o diagrama, representamos o algoritmo como uma sequência de símbolos, com significado bem definido.

![Diagrama](https://i.ibb.co/c278pfS/Imagem-1-Formas-utilizadas-em-fluxogramas.png)
![Diagrama2](https://i.ibb.co/s5sP4dZ/Diagrama-de-blocos.png)

### Pseudocódigo

Essa forma de representação de um algoritmo assemelha-se muito à forma com que os programas são escritos e consiste na descrição dos passos do algoritmo através de frases construídas sob uma sintaxe rigorosamente definida. 

![Pseudocódigo](https://i.ibb.co/XZqxXcg/Diagrama-de-blocos-para-pseudoc-digo.png)

### Regras para construção

Ao montar um algoritmo é preciso dividir o problema apresentado em três fases fundamentais: 

Entrada > Processamento > Saída

Receber valores N1 e N2 > Media = (n1+n2) /2 > Escrever media

É importante ao criar uma sequência lógica:
- Ler atentamente ao enunciado.
- Retirar do enunciado a relação das entradas de dados.
- Determinar o que deve ser feito.
- Testar (executar) o algoritmo.

## Entrada de dados

- Declarar = "Reservar um espaço" para um dado.
- Ler = "Pedir algo" para o usuário.
- Imprimir = "Mostrar algo" na tela.
- Limpar = "Organizar" apagando tudo da tela.

### O que é uma função?

Uma função é como um **atalho** que você cria para fazer algo no seu programa. Em vez de repetir o mesmo código várias vezes, você coloca tudo dentro da função e só chama ela quando precisar.

### Como funciona?

1. **Criar a função** (dizer o que ela faz).
2. **Usar a função** (pedir para ela fazer o trabalho).

## Fluxogramas

- Auxiliam na compreensão do código.
- São de linguagem universal
- Pode se encaixar em multilinguagens de programação

Os fluxogramas trazem várias vantagens para a programação, como:

1. **Clareza**: Facilitam a visualização da lógica do programa.
2. **Comunicação**: Ajudam a explicar o processo a equipes e stakeholders.
3. **Planejamento**: Permitem organizar ideias antes da codificação.
4. **Identificação de Problemas**: Ajudam a detectar erros e gargalos no processo.
5. **Documentação**: Servem como registro para manutenção futura.
6. **Facilidade de Aprendizado**: Simplificam conceitos para iniciantes.
7. **Qualidade do Código**: Melhoram a consistência da implementação.

Em resumo, fluxogramas tornam o desenvolvimento mais claro, organizado e eficiente.

## Tipos de Dados

As informações armazenadas na memória de um computador são convertidas em dados, permitindo que o computador as processe, analise e use para tomar decisões de forma eficiente.

- Os dados manipulados pelo computador são: Constantes e Variáveis.

### Constantes

Uma constante é um tipo de dado cujo valor permanece inalterado durante toda a execução de um programa. Dependendo de seu tipo, as constantes podem ser classificadas como numéricas, lógicas ou literais.

**Exemplos de constantes:**

1. (P1 + P2 + P3) / 3: Constante numérica
2. O nome é “**Maria**”: Constante Literal
3. A lâmpada está **ACESSA**: Constante lógica

### Variáveis

Uma variável é um espaço reservado na memória do computador para armazenar um tipo de dado determinado. Variáveis devem receber nomes para
poderem ser referenciadas e modificadas quando necessário.
Um programa deve conter declarações que especificam de que tipo são as variáveis que ele utilizará e às vezes um valor inicial.

![Variável](https://i.ibb.co/Jm9m0qK/Vari-vel.png)

### Tipos de variáveis
- Numéricas: Específicas para armazenamento de números, que posteriormente poderão ser utilizados para cálculos. Podem ser ainda classificadas como Inteiras ou Reais. As variáveis do tipo inteiro são para armazenamento de números inteiros e as reais são para o armazenamento de números que possuam casas decimais.
- Alfabéticas: Especificas para armazenamento de conjunto de caracteres que não contenham números (literais) e símbolos (*, %, &, @, etc.). Ex: nomes.
- Alfanuméricas: Especificas para dados que contenham qualquer tipo de caractere. Se usada somente para armazenamento de números, não poderá ser utilizada para operações matemáticas.
- Lógicas: Armazenam somente dados lógicos que podem ser Verdadeiro ou Falso
