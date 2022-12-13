<h1 align="center">Trabalho 4</h1><br>

![Badge em Desenvolvimento](http://img.shields.io/static/v1?label=STATUS&message=EM%20DESENVOLVIMENTO&color=GREEN&style=for-the-badge)

<h1 align="center">Problema</h1>

<h3>Implementar uma função que cria uma estrutura para o vetor ordenado. Além de funções para inserir e remover números inteiros neste vetor de forma ordenada.</h3><br>

### :warning: Para rodar a aplicação é nescessario ter o `gcc` e o `git` instalado na sua máquina, caso já tenha avance para: 

:small_blue_diamond: [Como rodar a aplicação](#como-rodar-a-aplicação-arrow_forward)

<h1 align="center">instalando o Gcc </h1>

No terminal digite o seguinte comando:

```
sudo apt update 

sudo apt install build-essential
```

<h1 align="center">instalando o Git </h1>

No terminal digite o seguinte comando:

```
sudo apt-get update sudo apt-get install git
```
<h1 align="center">
Como rodar a aplicação :arrow_forward:
</h1>

Clone o projeto no terminal:
```
git clone https://github.com/SamuelSilvaB/trabalho_4.git
```
Logo após clonar o projeto, entre na pasta clonada com o seguinte comando no terminal:
```
cd trabalho_4
```
Em seguida, obtenha as bibliotecas com o seguinte comando:
```
gcc -c trabalho_4.c
```
## Compilação

Cole o comando no terminal para gera um arquivo execultável:

```
gcc ./trabalho_4.o ./main.c -o main
```

## Execução
Cole um dos seguintes comandos para rodar o projeto:

Linux:
```
./main
```

Windows:
```
./main.exe
```

## Mudando o código
Será necessário fazer um vetor ordenado na função main do arquivo `main.c`, para isso dasta ussar a função `VETORD_create` e passar os parâmetros: tamanho do vetor criado e a função de comparação.

### Adicionando e remover elementos no vetor
Para adicionar elementos ao vetor use a função `VETORD_add` e passar a estrutura  do veotor e o valor do interio adicionado como parâmetro.
<br>
Para remover elementos no vetor use a função `VETORD_remove` e passar como parâmetro a estrutura do vetor.

### Imprimir
para imprimir o vetor, basta chamar a função `print` e passar como parâmetro: os elementos do vetor e o tamanho do vetor.

<h2 align="center">✔️ Tecnologia utilizada </h2>

- ``C``
