# Projeto Python - Calculadora Simples

## Sobre o projeto

Este projeto foi desenvolvido durante o curso de Análise de Dados da EBAC, com o objetivo de praticar os conceitos básicos de programação em Python.

Foi criada uma calculadora simples que permite ao usuário realizar diferentes operações matemáticas entre dois números.

## Operações disponíveis

A calculadora possui as seguintes operações:

* `+` — Soma
* `-` — Subtração
* `*` — Multiplicação
* `/` — Divisão
* `%` — Resto da divisão
* `//` — Divisão inteira
* `**` — Potenciação

## Arquivos do projeto

* `projetocalculadora.py` — arquivo principal com o código da calculadora.
* `executar_calculadora.sh` — script utilizado para executar o programa Python.
* `projetocalculadora (1).ipynb` — versão do projeto desenvolvida inicialmente no Google Colab.

## Como funciona o código

O código foi organizado em funções para facilitar sua utilização e organização.

A função `formatar()` verifica se o resultado possui casas decimais. Quando o número é inteiro, ele é apresentado sem as casas decimais.

A função `calcular()` recebe dois números e o operador escolhido pelo usuário. De acordo com o operador informado, ela realiza a operação matemática correspondente.

A função `main()` é responsável pela interação com o usuário. Ela apresenta as opções disponíveis, solicita os números e o operador e mostra o resultado.

O programa utiliza um laço `while` para permitir que o usuário faça vários cálculos sem precisar reiniciar a calculadora. Para encerrar o programa, basta digitar `sair`.

## Tratamento de erros

O programa também possui tratamento de erros utilizando `try` e `except`.

Foram considerados alguns possíveis erros, como:

* Tentativa de divisão por zero;
* Digitação de valores que não são números;
* Utilização de um operador que não está disponível;
* Outros erros inesperados durante a execução.

Dessa forma, o programa consegue apresentar mensagens de erro ao usuário sem simplesmente encerrar a execução.

## Como executar o arquivo Python

Para executar diretamente o programa Python, é necessário ter o Python instalado no computador.

No terminal, dentro da pasta onde o arquivo está salvo, pode ser utilizado o comando:

```bash
python projetocalculadora.py
```

Em alguns sistemas, pode ser necessário utilizar:

```bash
python3 projetocalculadora.py
```

## Como executar o arquivo .sh

O arquivo `executar_calculadora.sh` foi criado para facilitar a execução do programa Python.

Em sistemas Linux ou macOS, abra o terminal, acesse a pasta onde os arquivos estão salvos e execute:

```bash
bash executar_calculadora.sh
```

O script irá executar o arquivo `projetocalculadora.py`.

## Tecnologias utilizadas

* Python
* Google Colab
* GitHub
* Shell Script (.sh)

## Objetivo do projeto

O objetivo deste projeto foi colocar em prática conhecimentos iniciais de programação em Python, como funções, variáveis, estruturas condicionais, laços de repetição, entrada de dados e tratamento de erros.

Além disso, o projeto permitiu praticar a utilização do GitHub para armazenar e documentar um projeto de programação.
