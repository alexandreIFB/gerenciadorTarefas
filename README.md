# API Gerenciador de Tarefas

Essa será uma aplicação para gerenciar tarefas (em inglês todos). 

### Funcionalidades: 

- [] Criar um novo *todo*;
- [] Listar todos os *todos*;
- [] Alterar o `title` e `deadline` de um *todo* existente;
- [] Marcar um *todo* como feito;
- [] Excluir um *todo*;

Tudo isso para cada usuário em específico (o username será passado pelo header). 

### Estruturação do Usuário:

- id: 'uuid' (v4)
- name: string
- username: string unique 
- todos: todo[]

### Estruturaçaõ da Tarefa(todo):

- id: 'uuid' (v4)
- title: string
- done: boolean default = false
- deadline: date
	created_at: date
  
 ### Algumas regras de negócio
 
 - [] Deve se possivel cadastrar um usuario.
 - [] Não deve se possivel cadastrar um usuario com o mesmo username.
 - [] Para todas requisições de todo deve se verificado se o usuario é valido.
