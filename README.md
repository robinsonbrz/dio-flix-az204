# DioFlix Filmes - Bootcamp DioAzure
<div width="720" >
  <h1 align="left">Projeto DIO / MS Azure para o bootcamp Az204 </h1>
  <h2 align="left"></h2>
  <br>

Aplicação exemplo para Azure Functions banco de dados de filmes. Desenvolvida em .NET 8 e Azure Cosmos DB.

## Pré-requisitos

- [.NET 8 SDK](https://dotnet.microsoft.com/download/dotnet/8.0)
- [Azure Functions Core Tools](https://docs.microsoft.com/azure/azure-functions/functions-run-local)
- [Azure Cosmos DB](https://azure.microsoft.com/services/cosmos-db/)


## Executando o Projeto

1. Inicie o Azure Functions Core Tools:

func start





## Endpoints

### Todos os Filmes

Recupera todos os filmes.

- **Endpoint:** `GET /api/GetAllMovies`
- **Descrição:** Retorna todos os filmes.

### Adicionar Novo Filme

Adicionando um novo filme.

- **Endpoint:** `POST /api/AddMovie`
- **Descrição:** Adiciona um novo filme ao banco de dados.
- **Corpo da Requisição:**


{
    "id": "string",
    "title": "string",
    "director": "string",
    "releaseYear": "int"
}



### Atualização de Filme

Atualiza um filme.

- **Endpoint:** `PUT /api/UpdateMovie`
- **Descrição:** Atualiza um filme.
- **Corpo da Requisição:**

{
    "id": "string",
    "title": "string",
    "director": "string",
    "releaseYear": "int"
}



### Deletar Filme

Deleta filme.

- **Endpoint:** `DELETE /api/DeleteMovie`
- **Descrição:** Deleta um filme.
- **Parâmetros da Requisição:**

{
    "id": "string"
}



  <div align="center">
    <table>
      </tr>
            <td>
                <a  href="https://www.linkedin.com/in/robinsonbrz/">
            </td>
        <td>
            <a  href="https://www.linkedin.com/in/robinsonbrz/">
            <img src="https://raw.githubusercontent.com/robinsonbrz/robinsonbrz/main/static/img/linkedin.png" width="30" height="auto">
        </td>
        <td>
            <a  href="https://www.linkedin.com/in/robinsonbrz/">
            <img  src="https://avatars.githubusercontent.com/u/18150643?s=96&amp;v=4" alt="@robinsonbrz" width="30" height="auto">
        </td>
        <td>
            <a href="mailto:robinsonbrz@gmail.com">
            <img src="https://raw.githubusercontent.com/robinsonbrz/robinsonbrz/main/static/img/gmail.png" width="30" height="auto" ></a>
        </td>
      </tr>
    </table>
  </div>


</div>