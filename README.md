# Criptografia de Texto com Matrizes 2x2 em Python

Este projeto implementa um algoritmo simples de **criptografia e descriptografia de texto utilizando matrizes 2x2** em Python.  
O programa converte caracteres em valores numéricos utilizando a **tabela ASCII (Windows-1252)** e aplica operações de **álgebra linear**, como cálculo de determinante, inversa de matriz e multiplicação de matrizes.

A chave criptográfica é gerada dinamicamente a partir de **dados numéricos fornecidos pelo usuário (CPF ou CEP)**, garantindo que a matriz utilizada seja invertível e permitindo a descriptografia do texto.

---

## Funcionamento

1. O usuário informa um **texto para criptografar**.
2. Cada caractere é convertido em um número utilizando a **tabela ASCII (Windows-1252)**.
3. Os números são organizados em **matrizes 2x2**.
4. Uma **matriz chave de criptografia** é gerada a partir de um **CPF ou CEP**.
5. Cada matriz do texto é multiplicada pela matriz chave.
6. O resultado é convertido novamente em caracteres, formando o **texto criptografado**.
7. Para descriptografar, o programa calcula a **inversa da matriz chave** e aplica a operação inversa.

---

## Conceitos Utilizados

- Álgebra linear aplicada à criptografia
- Matrizes 2x2
- Determinante de matriz
- Inversa de matriz
- Multiplicação de matrizes
- Conversão de caracteres usando ASCII (Windows-1252)

---

## Funcionalidades

- Criptografia de texto utilizando multiplicação de matrizes
- Geração de chave criptográfica baseada em **CPF ou CEP**
- Verificação automática para garantir que a matriz seja **invertível**
- Descriptografia do texto utilizando a **matriz inversa**
- Exibição da **data e hora atual no fuso horário de São Paulo**

---

## Tecnologias Utilizadas

- Python
- Biblioteca `datetime`
- Biblioteca `pytz`

---

## Como executar

```bash
python projeto_criptografia_com_python.py
