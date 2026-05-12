# Sistema de Gestão de Membros

Projeto desenvolvido como desafio técnico para vaga de Estágio Full Stack.

O sistema permite cadastrar e listar membros, aplicando regras de negócio como validação de CPF, restrição de idade mínima e controle de status ativo/inativo.

## Funcionalidades

- Cadastro de membros
- Listagem de membros
- Validação de CPF
- Bloqueio de CPF duplicado
- Restrição para menores de 18 anos
- Controle de membro ativo/inativo
- Máscara de CPF para melhor experiência do usuário
- Alertas de validação
- Persistência utilizando H2 Database

## Tecnologias

### Backend
- Java
- Spring Boot
- H2 Database

### Frontend
- React
- TypeScript

## Como executar

### Backend

```bash
cd backend
./mvnw spring-boot:run
```

### Frontend

```bash
cd frontend
npm install
npm run dev
```