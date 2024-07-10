# Desafio Empregados TDD

## Descrição do Projeto

Este projeto é um sistema de funcionários e departamentos com uma relação N-1 entre eles. A especificação do que deve ser implementado está no próprio código fonte dos testes automatizados. O objetivo é implementar as funcionalidades para que todos os testes passem.

## Funcionalidades Implementadas

Os testes automatizados a seguir foram desenvolvidos e as funcionalidades correspondentes foram implementadas:

- `updateShouldReturnNotFoundWhenIdDoesNotExist`: Atualizar deve retornar "Not Found" quando o ID não existe.
- `updateShouldUpdateResourceWhenIdExists`: Atualizar deve atualizar o recurso quando o ID existe.
- `deleteShouldReturnBadRequestWhenDependentId`: Deletar deve retornar "Bad Request" quando há um ID dependente.
- `deleteShouldReturnNotFoundWhenNonExistingId`: Deletar deve retornar "Not Found" quando o ID não existe.
- `deleteShouldReturnNoContentWhenIndependentId`: Deletar deve retornar "No Content" quando há um ID independente.
- `insertShouldInsertResource`: Inserir deve inserir o recurso.
- `findAllShouldReturnAllResourcesSortedByName`: Buscar todos deve retornar todos os recursos ordenados por nome.

## Tecnologias Utilizadas

- Java
- Spring Boot
- JUnit
- Maven
- SQL
- Git

## Ferramentas Utilizadas

- SpringToolSuite4 IDEA (ou outra IDE de sua preferência)
- Postman (para testar APIs)
