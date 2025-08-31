# Hospital API

## Introdução
Hospital API é uma aplicação RESTful desenvolvida em **Java 17** com **Spring Boot 3**, que gerencia informações de pacientes e cirurgias em um contexto hospitalar. O sistema permite identificar se um paciente é da emergência ou eletivo, gerenciar prontuários e atendimentos, e cadastrar informações pessoais de pacientes.

---

## Funcionalidades
- Cadastro de pacientes com informações pessoais:
  - Nome
  - CPF
  - Data de nascimento
  - Nome da mãe
  - Endereço
- Cadastro de cirurgias para pacientes:
  - Nome da cirurgia
  - Tipo (Eletiva ou Urgência)
  - Data da cirurgia
- Geração automática de números de prontuário e atendimento
- Tratamento básico de exceções com respostas padronizadas

---

## Tecnologias
- Java 17
- Spring Boot 3
- Maven
- H2 Database (para testes locais)
- VS Code (IDE sugerida)
- Railway (para deploy online gratuito)

---

## Como executar localmente
1. Clone o projeto:
```bash
git clone <https://github.com/luizcarvalhosilva/Hospital-API-Java/tree/main>
cd hospital-api
