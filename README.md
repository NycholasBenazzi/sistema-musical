# Sistema Musical

Sistema web estático para cadastro e gestão de artistas e músicas, com interface em HTML e CSS. O projeto simula uma área administrativa para registrar artistas, associar músicas e consultar uma biblioteca musical.

## Visão geral

Este projeto foi desenvolvido como uma aplicação front-end de demonstração, com telas para:

- login de acesso
- menu principal
- cadastro de artistas
- cadastro de músicas
- listagem e filtro da biblioteca musical

A aplicação é totalmente estática e serve como base para aprendizado de estrutura de páginas web, formulários, layouts, tabelas e navegação entre telas.

## Funcionalidades

- Tela de login com usuário e senha de demonstração
- Menu principal com acesso às áreas do sistema
- Cadastro de artistas com nome, gênero, país e foto
- Cadastro de músicas com artista, título, álbum, gênero, link do YouTube e capa
- Listagem de músicas em tabela
- Filtros por busca, artista e gênero
- Interface responsiva e visual consistente em todas as telas

## Credenciais de acesso

Para acessar a área principal, o sistema usa as credenciais de teste abaixo:

- Usuário: `admin`
- Senha: `123`

## Tecnologias utilizadas

- HTML5
- CSS3
- JavaScript (não obrigatório para a lógica principal; o projeto é focado em layout e navegação)

## Estrutura do projeto

```text
sistema-musical/
├── index.html
├── login.html
├── cadastro_artista.html
├── cadastro_musica.html
├── listagem_musical.html
├── styles.css
└── README.md
```

## Como executar

### Opção 1: abrir diretamente no navegador

1. Acesse a pasta do projeto.
2. Abra o arquivo `login.html` em qualquer navegador.

### Opção 2: usar um servidor local

No terminal, dentro da pasta do projeto:

```bash
python -m http.server 8000
```

Depois abra no navegador:

```text
http://localhost:8000/login.html
```

## Observações

- O projeto é front-end estático; os dados exibidos são demonstrativos.
- Não há persistência real em banco de dados ou backend.
- Os formulários usam `action="#"` e possuem comportamento visual de demonstração.

## Objetivo do projeto

Esse sistema funciona como exemplo didático de:

- organização de telas em HTML
- uso de formulários e validações básicas
- estilização em CSS
- estrutura de tabelas e filtros
- navegação entre páginas

## Autor

Projeto desenvolvido em contexto acadêmico/educacional para prática de desenvolvimento web.
