# Comparação e Análise de Funções de Ordenação de Vetor

Este projeto implementa e compara diferentes algoritmos de ordenação de vetores. O objetivo é analisar o desempenho de cada algoritmo em termos de tempo de execução e eficiência com diferentes tamanhos e tipos de dados.

## Algoritmos de Ordenação Implementados

O projeto inclui a implementação dos seguintes algoritmos de ordenação:

- **Bubble Sort**: Um algoritmo simples de ordenação que compara e troca elementos adjacentes repetidamente.
- **Insertion Sort**: Um algoritmo que constrói a ordenação final de um vetor um elemento por vez.
- **Selection Sort**: Um algoritmo que seleciona repetidamente o menor elemento do vetor não ordenado e o coloca na posição correta.
- **Merge Sort**: Um algoritmo de ordenação eficiente baseado na técnica de divisão e conquista.
- **Quick Sort**: Um algoritmo de ordenação eficiente que utiliza a técnica de partição e recursão.

## Estrutura do Projeto

O projeto está organizado nos seguintes arquivos:

- **`main.c`**: Contém a função principal do programa, que gerencia a execução dos diferentes algoritmos de ordenação e coleta os resultados para análise.
- **`ordenacao.c`**: Implementa as funções de ordenação mencionadas acima.
- **`ordenacao.h`**: Declara as funções de ordenação implementadas em `ordenacao.c`.
- **`Makefile`**: Facilita a compilação do projeto, criando o executável a partir dos arquivos fonte.

## Como Rodar

### Como Compilar
O projeto inclui um `Makefile` para facilitar a compilação. Para compilar o projeto, basta executar o seguinte comando no terminal:
```bash
make
```
Isso gerará o executável a partir dos arquivos fonte fornecidos.

### Como Executar
Após a compilação, execute o programa com o comando:

```bash
./exec
```

## Uso do Programa

O programa permite:

- **Selecionar o algoritmo de ordenação**: Escolha entre os diferentes algoritmos implementados.
- **Inserir os dados**: Especifique o tamanho do vetor e insira os dados ou utilize dados gerados aleatoriamente.
- **Executar a ordenação**: O programa aplicará o algoritmo escolhido e exibirá o vetor ordenado.
- **Analisar o desempenho**: O programa calculará o tempo de execução de cada algoritmo para o conjunto de dados fornecido.

## Estrutura do Código

- **`main.c`**: Gerencia a interação com o usuário e a execução dos algoritmos de ordenação.
- **`ordenacao.c`**: Implementa as funções de ordenação.
- **`ordenacao.h`**: Declara as funções utilizadas em `ordenacao.c`.
- **`Makefile`**: Facilita a compilação do projeto.

