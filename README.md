# Bank API

Este é um projeto de exemplo de uma API bancária simples desenvolvida em Kotlin com o framework Spring.

## Tecnologias Utilizadas

- Kotlin
- Spring Boot
- Spring Data JPA
- H2 Database (para ambiente de desenvolvimento)
- JUnit 5 (para testes unitários)

## Funcionalidades

A API oferece os seguintes endpoints para manipulação de recursos:

- `POST /accounts`: Cria uma nova conta bancária.
- `PUT /accounts/{id}`: Atualiza os dados de uma conta existente.
- `GET /accounts/{id}`: Retorna os dados de uma conta específica.
- `GET /accounts/`: Retorna todos os dados existentes.
- `DELETE /accounts/{id}`: Remove uma conta existente.

## Como Executar

1. Clone o repositório:

```bash
git clone https://github.com/HugoPhilipe/bank-api.git
```
2. Navegue até o diretório do projeto:
```bash
cd bank-api
```
3. Execute a aplicação usando o Maven:
```bash
mvn spring-boot:run
```
A aplicação estará disponível em http://localhost:8080.

## Testes Unitários

Para executar os testes unitários, vá até a pasta "test > kotlin > com.eprogramar.bank", clique com botão direito na classe que deseja testar
depois clique no botão "Run"

## Configuração do Banco de Dados
O projeto está configurado para utilizar um banco de dados H2 em memória por padrão. Para alterar as configurações do banco de dados, consulte o arquivo application.properties.

## Contribuição
Sinta-se à vontade para contribuir com melhorias para este projeto através de pull requests!

