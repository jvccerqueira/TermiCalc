<h1 align="center">Calculadora Interativa em Linha de Comando</h1>

<p align="center">
  <img src="https://img.shields.io/badge/python-3.6%2B-blue.svg" alt="Python Version">
  <img src="https://img.shields.io/badge/license-MIT-green.svg" alt="License">
</p>

<p align="center">
  Uma calculadora simples de linha de comando desenvolvida em Python que suporta operações aritméticas básicas, atribuição de variáveis e análise de expressões.
</p>

## Sumário

* [Funcionalidades](#-funcionalidades)
* [Como Executar](#-como-executar)
* [Dependências](#️-dependências)
* [Uso](#-uso)
* [Contribuição](#-contribuição)
* [Licença](#-licença)

## Funcionalidades

* **Operações Aritméticas Básicas**: Suporta adição, subtração, multiplicação e divisão.
* **Ordem de Operações**: Respeita a precedência matemática padrão (PEMDAS/BODMAS).
* **Atribuição de Variáveis**: Permite atribuir valores a variáveis e usá-las em expressões subsequentes.
* **Interface Interativa**: Oferece um prompt de comando para entrada do usuário.
* **Tratamento de Erros**: Fornece feedback para caracteres ilegais e erros de sintaxe.

## Como Executar

1.  **Clone o repositório:**
    ```bash
    git clone git@github.com:jvccerqueira/TermiCalc.git
    cd TermiCalc
    ```

2.  **Instale as dependências:**
    ```bash
    pip install -r requirements.txt
    ```

3.  **Execute a calculadora:**
    ```bash
    python calculator.py
    ```

## Dependências

Este projeto utiliza a biblioteca `ply`. Um arquivo `requirements.txt` é fornecido para facilitar a instalação.

* **ply**: Utilizada para a criação do analisador léxico e sintático.

## Uso

Após iniciar a calculadora, você verá o prompt `calc >`. Digite suas expressões matemáticas ou atribuições e pressione Enter.

### Exemplos de Expressões

* **Cálculos Simples:**
    ```
    calc > 10 + 5 * 2
    20.0
    ```

* **Uso de Parênteses:**
    ```
    calc > (10 + 5) * 2
    30.0
    ```

* **Atribuição de Variáveis:**
    ```
    calc > x = 15
    calc > y = 10
    calc > x * y
    150.0
    ```

* **Sair do Programa:**
    ```
    calc > exit
    ```

## Licença

Este projeto está sob a licença MIT. Veja o arquivo `LICENSE` para mais detalhes.