# axion-test
Este projeto foi desenvolvido como parte do desafio técnico proposto pela Axion, com o objetivo de avaliar habilidades técnicas, organização de código, capacidade de aprendizado e abordagem na resolução de problemas por meio da construção de uma aplicação web integrada a uma API REST.

## Visão Geral

A aplicação consiste em um sistema web desenvolvido com Next.js que consome uma API criada em Strapi. O projeto implementa autenticação de usuário, controle de sessão, proteção de rotas e listagem dinâmica de conteúdos.
O layout foi construído com base no protótipo fornecido no desafio, buscando fidelidade visual e organização estrutural.

## Funcionalidades
- Autenticação via endpoint /auth/local
- Armazenamento de token JWT
- Controle de sessão no front-end
- Proteção de rotas autenticadas
- Logout com remoção de sessão
- Consumo das collections:
  - Foods
  - People
  - Places
- Ordenação crescente e decrescente no front-end
- Layout estruturado com componente reutilizável de header
- Estilização modular utilizando CSS Modules

## Tecnologias Utilizadas
- Next.js
- React
- Strapi (Headless CMS)
- Node.js
- CSS Modules
- JWT (JSON Web Token)

## Estrutura do Projeto
A aplicação foi organizada priorizando separação de responsabilidades, reutilização de componentes e manutenção facilitada.

```bash
src/
 ├── app/
 ├── components/
 ├── styles/
public/
```

Principais conceitos aplicados:
- Componentização
- Layout compartilhado (AppShell)
- Consumo centralizado de API
- Organização modular de estilos
- Estrutura clara e escalável

## Execução do Projeto
Front-end

```bash
npm install
npm run dev
```

A aplicação estará disponível em:
`http://localhost:3000`

Back-end
O back-end foi disponibilizado pela Axion por meio de um projeto Strapi e deve estar rodando localmente na porta 1337.
