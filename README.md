<h1 align="center">Welcome to to.do App 👋</h1>
<p>
  <img alt="Version" src="https://img.shields.io/badge/version-1.0.0-blue.svg?cacheSeconds=2592000" />
  <a href="#" target="_blank">
    <img alt="License: MIT" src="https://img.shields.io/badge/License-MIT-yellow.svg" />
  </a>
  <a href="https://twitter.com/\_ianfelix" target="_blank">
    <img alt="Twitter:\_ianfelix" src="https://img.shields.io/twitter/follow/_ianfelix.svg?style=social" />
  </a>
</p>

> App to create tasks

### ✨ [Demo](https://desafio01-trilha-reactjs.vercel.app/)

# challenge

Para esse desafio, temos os seguintes testes:

### Teste TaskList.spec.tsx

- **should be able to add a task**

Para que esse teste passe, você deve permitir que task seja criada e com isso, exibida em tela. As taks criadas devem conter os atributos seguindo o padrão da interface, que é:

```tsx
interface Task {
  id: number;
  title: string;
  isComplete: boolean;
}
```

- **should not be able to add a task with an empty title**

Para que esse teste passe, antes de criar uma nova task, você deve validar se algo foi digitado no input e não permitir a criação da task caso o valor seja vazio, caso o valor digitado seja vazio, você deve impedir a criação da task.

- **should be able to remove a task**

Para que esse teste passe, você deve permitir que ao clicar no botão com ícone de uma lixeira, a task relacionada a esse botão seja removida do estado da aplicação, consequentemente sendo removida da tela.

- **should be able to check a task**

Para que esse teste passe, você deve permitir que ao clicar no checkbox ao lado da task, ela seja marcada como concluída ou não concluída de acordo com seu estado atual, alterando seu valor de `isComplete` de `false` para `true` ou ao contrário, de `true` para `false`.


## Install

```sh
yarn install
```

## Run tests

```sh
yarn test
```

## Author

👤 **Ian Felix**

- Website: Ian Felix
- Twitter: [@\_ianfelix](https://twitter.com/_ianfelix)
- Github: [@ianfelix](https://github.com/ianfelix)
- LinkedIn: [@ian-felix](https://linkedin.com/in/ian-felix)

## Show your support

Give a ⭐️ if this project helped you!

---
