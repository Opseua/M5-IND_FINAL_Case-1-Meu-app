# M5-IND_FINAL_Case-1-Meu-app



# [ API ] Mercado
### 📑 Descrição
Desenvolvimento da <em>**API REST**</em> no **padrão MVC** que retorna informações das entidades de um mercado e efetua todas as operações **CRUD**: ``filiais``, ``funcionarios``, ``mercadorias``.




**[ Tecnologias ]**

<samp>
  
- <em>Node.js</em> | <em>SQLite3</em> | <em>Express</em> | <em>Postman</em> | <em>CORS</em> | <em>npm</em> | <em>Nodemon</em>
  
</samp>

<details>
<summary>  
  <strong>Estrutura do Diretório</strong>
</summary>
<br>

```
src/
├─ controllers/
│  ├─ FiliaisController.js
│  ├─ FuncionariosController.js
│  ├─ MercadoriasController.js
├─ dao/
│  ├─ FiliaisDAO.js
│  ├─ FuncionariosDAO.js
│  ├─ MercadoriasDAO.js
├─ models/
│  ├─ Filiais.js
│  ├─ Funcionarios.js
│  ├─ Mercadorias.js
├─ database/
│  ├─ create-and-populate.js
│  ├─ config.js
│  └─ database.db
├─ routes/
│  ├─ filiais.js
│  ├─ funcionarios.js
│  └─ mercadorias.js
└─ main.js
```

</details>


### 🎲 Iniciando o Projeto


<samp>
  
> **Warning** 
> Pré-Requisitos: Git, Node.js e um editor de código.

</samp>

```bash
# Clone o repositório
$ git clone https://github.com/Opseua/M5-IND_FINAL_Case-1-Meu-app

# Acesse a pasta do projeto no terminal/cmd
$ cd M5-IND_FINAL_Case-1-Meu-app

# Instale as dependências
$ npm install

# Execute a aplicação 
$ npm start

# Acesse o servidor
$ <http://localhost:6020>
```

## Rotas CRUD

### [ 1 ] <em>Filiais</em>

| Método | Rota | Descrição |
| ------ | ----- | ----------- |
| **`GET`** | **/filiais** | Retorna todos as filiais. |
|  **`GET`** | **/filial/id** | Retorna uma filial. |
|  **`POST`** | **/filial** | Cria uma nova filial.  |
|  **`PUT`** | **/filial/id** | Altera os dados da filial.
|  **`DELETE`** | **/filial/id** | Remove a filial.
  
### [ 2 ] <em>Funcionarios</em>

| Método | Rota | Descrição |
| ------ | ----- | ----------- |
|  **`GET`** | **/funcionarios** | Retorna todos os funcionarios. |
|  **`GET`** | **/funcionario/id** | Retorna um funcionario. |
|  **`POST`** | **/funcionario** | Cria um novo funcionario.  |
|  **`PUT`** | **/funcionario/id** | Altera os dados do funcionario.
|  **`DELETE`** | **/funcionario/id** | Remove o funcionario.
  
  
### [ 3 ] <em>Mercadorias</em>

| Método | Rota | Descrição |
| ------ | ----- | ----------- |
|  **`GET`** | **/mercadorias** | Retorna todas as mercadorias. |
|  **`GET`** | **/mercadoria/id** | Retorna uma mercadoria. |
|  **`POST`** | **/mercadoria** | Cria uma nova mercadoria.  |
|  **`PUT`** | **/mercadoria/id** | Altera os dados da mercadoria.
|  **`DELETE`** | **/mercadoria/id** | Remove a mercadoria.

