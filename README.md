# Desafio TDD Event City

## Descrição do Projeto

Este projeto é um sistema de eventos e cidades com uma relação N-1 entre eles. A especificação do que deve ser implementado está no próprio código fonte dos testes automatizados. O objetivo é implementar as funcionalidades para que todos os testes passem.

## O que é TDD?

TDD, ou Test-Driven Development (Desenvolvimento Orientado por Testes), é uma prática de desenvolvimento de software onde os testes são escritos antes do código funcional. O ciclo básico do TDD consiste em três etapas:

1. **Red**: Escrever um teste que falhe para uma nova funcionalidade ou melhoria.
2. **Green**: Escrever o código mínimo necessário para fazer o teste passar.
3. **Refactor**: Refatorar o código para melhorar a estrutura e a qualidade, mantendo todos os testes passando.

Este processo é repetido para cada nova funcionalidade ou melhoria, garantindo que o código seja continuamente testado e de alta qualidade.

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
