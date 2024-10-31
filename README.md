
# Desafio de Código: Controle de Compras com Cartão de Crédito

Este projeto é um **desafio de código** focado em exercitar **listas** e **ordenamento de listas** em Java. O programa simula um sistema de cartão de crédito que registra e organiza compras, controlando o saldo e listando as compras em ordem de valor.

## Objetivo

Praticar:
- Criação e manipulação de listas (`ArrayList`).
- Ordenação de listas com `Comparable` e `Collections.sort`.
- Organização de classes e encapsulamento em Java.

## Estrutura do Programa

### Classes

- **Compra**: representa uma compra, com descrição e valor. Implementa `Comparable` para permitir ordenação pelo valor da compra.
- **CartaoDeCredito**: gerencia o limite, saldo e lista de compras realizadas no cartão.
- **Principal**: classe principal que interage com o usuário para registrar e listar compras ordenadas.

### Funcionalidades

- **Registro de compras**: permite adicionar compras ao cartão verificando o saldo disponível.
- **Ordenação**: exibe compras em ordem crescente de valor.
- **Exibição do saldo final**.

## Exemplo de Uso

1. Insira o limite do cartão, por exemplo: `500`.
2. Adicione compras com descrição e valor.
3. Ao encerrar, o sistema lista as compras e o saldo restante.

### Exemplo de Saída

```
Compras realizadas:
Cinema - 20.0
Supermercado - 80.0

Saldo do cartão: 400.0
```

## Tecnologias

- Java 

## Como Executar

1. Compile e execute o programa:
   ```bash
   javac Principal.java
   java Principal
   ```

---

Este desafio é ideal para reforçar conhecimentos sobre listas e ordenação em Java!
