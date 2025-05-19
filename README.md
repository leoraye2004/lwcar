# Sistema de Aluguel de Veículos

## Requisitos Funcionais:

- **RF01** - Cadastro de usuários (clientes e administradores).
- **RF02** - Cadastro de veículos disponíveis para aluguel.
- **RF03** - Consulta de veículos por categoria, preço e disponibilidade.
- **RF04** - Reserva e confirmação de aluguel de veículos.
- **RF05** - Geração de relatórios sobre os aluguéis realizados.
- **RF06** - Controle de status dos veículos (disponível, alugado, em manutenção).

## Requisitos Não Funcionais:

- **RNF01** - Interface responsiva para dispositivos móveis e desktop.
- **RNF02** - Armazenamento dos dados em um banco de dados.
- **RNF03** - Autenticação e segurança dos dados dos usuários.
- **RNF04** - Boa performance no carregamento das páginas.
- **RNF05** - Código bem estruturado para facilitar futuras manutenções.

## Estratégias de Desenvolvimento

O sistema será desenvolvido utilizando uma **arquitetura monolítica**, pois trata-se de um sistema relativamente simples, onde a separação por módulos independentes não se faz necessária. Dessa forma, todo o back-end será centralizado em um único projeto utilizando **Node.js**.

## Tecnologias Utilizadas e Justificativas

- **Front-end**: HTML, CSS e JavaScript para garantir uma interface responsiva e dinâmica.
- **Back-end**: Node.js com Express para criação de uma API leve e eficiente.
- **Banco de Dados**: MySQL.

## Plano de Trabalho

- **Prototipagem Front-end**: Desenvolvimento do protótipo das páginas. - **Wellerson**.
- **Front-end**: Desenvolvimento da interface e interação com o usuário. - **Ambos**.
- **Back-end**: Criação das APIs para gerenciar usuários, veículos e reservas. - **Wellerson**.
- **Banco de Dados**: Estruturação do armazenamento dos dados. - **Leo**.
- **Autenticação**: Implementação do Firebase Authentication. - **Leo**.
- **Testes e Ajustes**: Verificação de bugs e otimização do sistema antes da apresentação. - **Ambos**.
