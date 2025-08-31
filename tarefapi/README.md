# UTILIZAÇÃO DA API TAREFAS

API tarefas serve para cadastrar, visualizar, atualizar e deletar tarefas.

### Demonstração dos Endpoints

GET http://localhost:8080/tarefas

- Lista todas as tarefas cadastradas, retorna status 200 ok, a lista de tarefas cadastradas ou lista vazia se não houver tarefas cadastradas..

POST http://localhost:8080/tarefa

- Deve enviar no corpo um JSON com (nome, dataEntrega, responsavel), em caso de sucesso a api retorna status 200 ok e os dados contidos no corpo


PUT http://localhost:8080/tarefas/{id}

- Atualiza os dados de uma tarefas especificada pelo id, o corpo deve conter (nome, dataEntrega, responsavel), em caso de sucesso a api retorna status 200 ok e os dados contidos no corpo.

DELETE http://localhost:8080/tarefas/{id}

- Deleta a tarefa especificado pelo id, em caso de sucesso retorna status 200 ok.