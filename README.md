# 🛡️ Contador - Tratamento de Erros em Java

Este repositório contém um projeto simples em Java que demonstra o uso de tratamento de exceções (`Exception`). O programa realiza uma contagem de valores informados pelo usuário, garantindo que o segundo parâmetro seja sempre maior que o primeiro.

## 🧠 Objetivo

* Introduzir o conceito de exceções em Java
* Criar e lançar exceções customizadas
* Utilizar `try-catch` para tratar erros de forma controlada

## 📄 Descrição do Projeto

O programa solicita dois números inteiros ao usuário:

1. Primeiro parâmetro
2. Segundo parâmetro

Caso o segundo parâmetro seja menor ou igual ao primeiro, uma exceção customizada `ParametrosInvalidosException` é lançada e tratada, exibindo uma mensagem de erro apropriada. Caso contrário, o programa imprime a sequência numérica de `1` até a diferença entre os dois parâmetros.

### 📋 Classes Principais

* `Contador.java`: contém o método `main`, a lógica de leitura e invocação do método de contagem dentro de um bloco `try-catch`.
* `ParametrosInvalidosException.java`: exceção customizada que estende `Exception`.

---

## ▶️ Exemplo de Execução

```bash
Digite o primeiro parâmetro: 5
Digite o segundo parâmetro: 3
```

**Saída Esperada em Erro:**

```
O segundo parâmetro deve ser maior que o primeiro
```

```bash
Digite o primeiro parâmetro: 2
Digite o segundo parâmetro: 7
```

**Saída Esperada no Fluxo Normal:**

```
1  2  3  4  5  
```

---

## 📁 Estrutura do Projeto

```
ContadorException/
├── Contador.java
└── ParametrosInvalidosException.java
```

---
