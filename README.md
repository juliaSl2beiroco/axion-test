# Axion test – API + Front-end
Este projeto foi desenvolvido como parte do desafio técnico proposto pela Axion, com o objetivo de avaliar habilidades técnicas, organização de código, capacidade de aprendizado e abordagem na resolução de problemas por meio da construção de uma aplicação web integrada a uma API REST.

## Estrutura do Projeto
axion-teste/       (API construída com Strapi)
axion-frontend/    (Front-end)

## Funcionalidades
- Autenticação integrada ao Strapi
- Armazenamento de token JWT
- Controle de sessão no front-end
- Proteção de rotas autenticadas
- Logout com remoção de sessão
- Consumo das collections:
  - Foods
  - People
  - Places
- Ordenação crescente e decrescente no front-end
- Estilização modular utilizando CSS Modules

## Tecnologias Utilizadas
### Back-end (Strapi)
- Node.js
- Strapi
- SQLite (banco de dados local)

Os objetos estarão no formato:

{
  "name": "Nome do item",
  "link": "URL da imagem"
}
Estes links só funcionarão caso o servidor esteja rodando.

### Front-end
- React
- Next.js
- CSS Modules
- JWT para autenticação


## Como Executar o Projeto Localmente
1. Clonar o Repositório
```bash
git clone https://github.com/seu-usuario/seu-repositorio.git
cd seu-repositorio
```

2. Iniciar o Back-end
```bash 
cd axion-test
npm install
npm run build
npm run develop
```

O servidor estará disponível em:
`http://localhost:1337`

3. Iniciar o Front-end
```bash
cd ../axion-frontend
npm install
npm run dev
```

A aplicação estará disponível em:
`http://localhost:3000`

## Login
Faça login com as seguintes credenciais: 

E-mail: axioner@axion.company
Senha: Axioner123

## Layout
Layout do protótipo para o teste: MarvelApp

Códigos em hexa das cores utilizadas no layout:
```bash
#4A4A4A
#AE23A9
#DC4E1B
#9B9B9B
#FFFFFF
#F9F9F9
```

A fonte usada no layou: [Open Sans – Google Fonts](https://fonts.google.com/specimen/Open+Sans)

## Recursos Visuais

As pastas imgs e assets estão disponíveis no link: https://bit.ly/3oIQyCC

## Observações Técnicas

Os dados estão todos salvos em um banco local SQLite que já se comunica com a API, portanto não é necessário se preocupar com essa parte.

## Considerações Adicionais

Foi implementado um botão de logout para controle explícito de sessão, também foi adicionado um botão de ordenação crescente e decrescente nas listas.
A imagem de background utilizada no layout apresenta leve perda de qualidade, pois foi necessário remover o fundo da imagem original fornecida para adequação ao design.
