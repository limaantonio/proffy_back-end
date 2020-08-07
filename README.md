<h1 align="center">
  <img src="github/landing.svg">
</h1>

# Indice
- [Sobre](#-sobre)
- [Tecnologias Utilizadas](#-tecnologias-utilizadas)
- [Como baixar o projeto](#como-baixar-o-projeto)

# 🗒 Sobre

Essa é a API desenvolvida para o **Proffy**, uma aplicação desenvolvida durante a **Next Level Week 2.0** da **Rockseat**. 

# 🚀 Tecnologias Utilizadas

- [NodeJS](https://nodejs.org/en/)
- TypeScript
- [KNEX](http://knexjs.org/)
- SQLite

# 🛠 Funcionalidades

## Conexões

- Rota para listar o total de conexões realizadas;
- Rota para criar uma nova conexão

## Aulas 

- Rota para criar uma aula;
- Rota para listar aulas;
- Filtrar por materia, dia da semana e horario;

# 📦 Como baixar o projeto

```bash

  #Clonar o repositório
  $git clone https://github.com/limaantonio/proffy_back-end
  
  # Entrar no repositório
  $ cd proffy_back-end

  # Instalar as dependencias
  $ yarn install 

  # Crie as migrations
  $ yarn knex:migrate

  # Inciar o projeto
  $ yarn start

```

Desenvolvido por 💻  Antonio Carlos