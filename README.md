# 📝 Lista de Tarefas

Aplicação web simples para gerenciamento de tarefas, desenvolvida com **HTML, CSS e JavaScript**.

O projeto permite adicionar tarefas, marcá-las como concluídas e removê-las. As tarefas são armazenadas no **Local Storage** do navegador, mantendo os dados mesmo após recarregar a página.

## 🚀 Funcionalidades

* ✅ Adicionar novas tarefas
* ☑️ Marcar tarefas como concluídas
* 🗑️ Remover tarefas
* 💾 Persistir tarefas utilizando `localStorage`
* 🔄 Recuperar as tarefas automaticamente ao recarregar a página
* ⚠️ Validar o tamanho mínimo da tarefa

## 🛠️ Tecnologias

* HTML5
* JavaScript
* Local Storage

## 📂 Estrutura do projeto

```text
listaDeTarefas/
├── index.html
└── index.js
```

## ▶️ Como executar

1. Clone o repositório:

```bash
git clone git@github.com:gizele233/listaDeTarefas.git
```

2. Acesse a pasta do projeto:

```bash
cd listaDeTarefas
```

3. Abra o arquivo `index.html` no navegador.

Não é necessário instalar dependências ou configurar um servidor para executar o projeto.

## 💡 Como funciona

As tarefas são armazenadas em um array de objetos JavaScript no seguinte formato:

```javascript
{
    title: "Estudar JavaScript",
    done: false
}
```

Sempre que uma tarefa é adicionada, concluída ou removida, o estado atualizado é salvo no `localStorage`.
Ao carregar a página, as tarefas salvas anteriormente são recuperadas e renderizadas novamente na interface.

## 📌 Validação

Para adicionar uma tarefa, é necessário informar pelo menos **3 caracteres**.

## 📄 Licença

Este projeto foi desenvolvido para fins de estudo e prática de desenvolvimento web.
