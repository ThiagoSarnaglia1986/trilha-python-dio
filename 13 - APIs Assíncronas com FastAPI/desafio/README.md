# Desafio: API Bancária Assíncrona com FastAPI

Neste desafio, você irá projetar e implementar uma API RESTful assíncrona usando FastAPI para gerenciar operações bancárias de depósitos e saques, vinculadas a contas correntes. Este desafio[...]

## Objetivos e Funcionalidades

O objetivo deste desafio é desenvolver uma API com as seguintes funcionalidades:

- **Cadastro de Transações:** Permita o cadastro de transações bancárias, como depósitos e saques.
- **Exibição de Extrato:** Implemente um endpoint para exibir o extrato de uma conta, mostrando todas as transações realizadas.
- **Autenticação com JWT:** Utilize JWT (JSON Web Tokens) para garantir que apenas usuários autenticados possam acessar os endpoints que exigem autenticação.

## Requisitos Técnicos

Para a realização deste desafio, você deve atender aos seguintes requisitos técnicos:

- **FastAPI:** Utilize FastAPI como framework para criar sua API. Aproveite os recursos assíncronos do framework para lidar com operações de I/O de forma eficiente.
- **Modelagem de Dados:** Crie modelos de dados adequados para representar contas correntes e transações. Garanta que as transações estão relacionadas a uma conta corrente, e que contas possa[...]
- **Validação das operações:** Não permita depósitos e saques com valores negativos, valide se o usuário possui saldo para realizar o saque.
- **Segurança:** Implemente autenticação usando JWT para proteger os endpoints que necessitam de acesso autenticado.
- **Documentação com OpenAPI:**  Certifique-se de que sua API esteja bem documentada, incluindo descrições adequad
as para cada endpoint, parâmetros e modelos de dados.


## English / Português

# Challenge: Asynchronous Banking API with FastAPI

In this challenge, you will design and implement an asynchronous RESTful API using FastAPI to manage banking operations such as deposits and withdrawals, linked to checking accounts.

## Goals & Features

The aim of this challenge is to develop an API with the following features:

- **Register Transactions:** Allow registering banking transactions like deposits and withdrawals.
- **Account Statement:** Implement an endpoint to show an account statement with all transactions.
- **JWT Authentication:** Use JWT (JSON Web Tokens) to ensure only authenticated users can access protected endpoints.

## Technical Requirements

For this challenge, you should meet the following technical requirements:

- **FastAPI:** Use FastAPI as the framework. Take advantage of its async features for efficient I/O handling.
- **Data Modeling:** Create adequate data models to represent accounts and transactions, ensuring transactions are related to an account.
- **Operation Validation:** Do not allow negative deposit/withdrawal values; validate sufficient balance for withdrawals.
- **Security:** Implement JWT authentication for protected endpoints.
- **OpenAPI Documentation:** Ensure the API is well-documented, with descriptions for endpoints, parameters and data models.
