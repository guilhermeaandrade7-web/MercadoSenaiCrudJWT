# MercadoSenaiCrudJWT
Projeto SENAI Desenvolvimento de sistemas.

Projeto: Sistema de Gerenciamento [Mercado]
1. Visão Geral
Este projeto consiste no desenvolvimento de uma aplicação baseada na arquitetura CRUD (Create, Read, Update, Delete), projetada para otimizar o fluxo de informações.  O foco principal é oferecer uma interface intuitiva aliada a um backend robusto e seguro.

2. Objetivo
O objetivo central é aplicar os conhecimentos técnicos adquiridos no SENAI, focando na persistência de dados e na implementação de regras de negócio que simulem desafios reais da indústria 4.0, garantindo a integridade e a disponibilidade das informações.

3. Arquitetura e Segurança (JWT)
Diferente de sistemas básicos, esta aplicação implementa o protocolo JWT (JSON Web Token) para autenticação e autorização.

Segurança: O acesso às rotas do sistema é protegido, garantindo que apenas usuários autenticados possam manipular os dados.

Eficiência: Por ser um método stateless, o JWT permite que o servidor não precise armazenar sessões, tornando a aplicação mais leve e preparada para futuras expansões.

Integridade: Cada requisição é validada através de um token criptografado, impedindo acessos não autorizados e garantindo a privacidade do usuário.

4. Tecnologias Utilizadas
Frontend: [Postman] – Interface responsiva e focada na experiência do usuário (UX).

Backend: [ Node.js / Java   /] – Lógica de negócio e gerenciamento de requisições.

Banco de Dados: [Ex: MySQL / PostgreSQL] – Armazenamento estruturado dos dados.

Autenticação: JWT para geração e validação de tokens de acesso.

5. Funcionalidades Principais
Criação (Create): Cadastro de novos registros com validação de campos.

Leitura (Read): Listagem dinâmica e busca de informações.

Atualização (Update): Edição de dados existentes com rastreabilidade.

Exclusão (Delete): Remoção segura de registros do banco de dados.

Login Seguro: Tela de autenticação que gera o token de acesso temporário.

6. Conclusão
O projeto demonstra a viabilidade técnica de uma solução moderna, que não apenas resolve o problema da gestão de dados, mas o faz seguindo as melhores práticas de segurança da informação exigidas pelo mercado de trabalho atual.
