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

Clone o progeto no terminal:

```
git clone 



______________________________________________________________________________




## Download
Cole o seguinte comando no terminal para obter o código do projeto.
```
git clone https://github.com/SamuelSilvaB/trabalho_4.git 
```

## Gerar bibliotecas
Cole o seguinte comando no terminal para gerar as bibliotecas do projeto.
```
gcc -c trabalho_4.c
```

## Compilação
Cole o seguinte comando no terminal para gerar o compilado do projeto.
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

## Alterando o código
Primeiramente é necessário criar uma estrutura do tipo vetor ordenado na função main do arquivo `main.c`. Para isso, basta chamar a função `VETORD_create` e passar como parâmetro: o tamanho do vetor que será criado e uma função de comparação. \ 
\
Para adicionar elementos no vetor basta chamar a função `VETORD_add` e passar como parâmetro: a estrutura do vetor e o valor inteiro que será adicionado. \ 
\
Para remover elementos no vetor basta chamar a função `VETORD_remove` e passar como parâmetro: a estrutura do vetor. \ 
\
E para imprimir o vetor, basta chamar a função `print` e passar como parâmetro: os elementos do vetor e o tamanho do vetor.

## Linguagens utilizadas
- `C`
