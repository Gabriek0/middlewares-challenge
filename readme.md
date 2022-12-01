<h1 align="center">Middleware Challenge 🧷</h1>

### 💻 Descrição

Resolução do Desafio 2 da trilha de Nodejs da Rocketseat. O desafio consiste em acrescentar código para validação de informações nas funções middlewares: **checksCreateTodosUserAvailability**, **checksTodoExists**, **findUserById**.

### :nut_and_bolt: Tecnologias

Esse projeto foi desenvolvido com as seguintes tecnologias:

- [Yarn][yarn]
- [Node][node]
- [Express][express]

[yarn]: https://yarnpkg.com/
[node]: https://nodejs.org/en/
[express]: https://expressjs.com/pt-br/

#### Requisitos

- [x] Deve ser possível criar um novo usuário
- [x] Deve ser possível buscar um usuário pelo `username`
- [x] Deve ser possível criar uma nova tarefa
- [x] Deve ser possível buscar todos as tarefas
- [x] Deve ser possível atualizar uma tarefa
- [x] Deve ser possível marcar uma tarefa como feita
- [x] Deve ser possível deletar uma tarefa
- [x] Deve ser possível que o usuário `pro` crie um número infinito de tarefas
- [x] Deve ser possível que o usuário `free` crie até 10 tarefas

#### Regras de negócio

- [x] Não deve ser possível criar um novo usuário se o `username` já existir
- [x] Não deve ser possível atualizar uma tarefa que não existe
- [x] Não deve ser possível marcar uma tarefa que não existe como "feita"
- [x] Não deve ser possível deletar uma tarefa que não existe
- [x] Não deve ser possível criar mais que 10 tarefas se o usuário não estiver com o plano pro ativado.

### 🤔 Como rodar o projeto?

```bash

# Clone o repositório
git clone https://github.com/Gabriek0/middlewares-challenge.git

# Mude para o diretório do projeto
cd https://github.com/Gabriek0/middlewares-challenge.git

# Instale as dependências
yarn

# Rode o projeto
yarn dev

```

### 🧑 Autor do Projeto

<table>
  <tr>
    <td align="center">
      <a href="https://github.com/Gabriek0">
        <img src='https://avatars.githubusercontent.com/u/89749843?v=4' width="100px;" alt=""/>
        <br />
          <sub>
            <b>Gabriel Henrique</b>
          </sub>
      </a>
    </td>

  </tr>
</table>
