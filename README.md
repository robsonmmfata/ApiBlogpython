#  API de Blog com FastAPI, Tortoise ORM e Python

Este projeto é uma API RESTful construída com FastAPI, Tortoise ORM e Python, projetada para gerenciar um blog.

##  Recursos Principais

* **FastAPI**: Framework web moderno e de alto desempenho para construir APIs. <img align="center" alt="FastAPI" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/fastapi/fastapi-original.svg">
* **Tortoise ORM**: ORM assíncrono inspirado no Django, para interagir com o banco de dados. <img align="center" alt="Python" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg">
* **Python**: Linguagem de programação poderosa e versátil. <img align="center" alt="Python" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg">

##  Tecnologias Utilizadas

* Python 3.9+ <img align="center" alt="Python" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg">
* FastAPI <img align="center" alt="FastAPI" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/fastapi/fastapi-original.svg">
* Tortoise ORM <img align="center" alt="Python" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg">
* Bancos de dados suportados pelo Tortoise ORM (PostgreSQL, MySQL, SQLite, etc.) <img align="center" alt="PostgreSQL" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/postgresql/postgresql-original.svg"> <img align="center" alt="MySQL" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mysql/mysql-original.svg"> <img align="center" alt="SQLite" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/sqlite/sqlite-original.svg">

## ️ Como Instalar

1.  Clone o repositório:

    ```bash
    git clone [https://github.com/robsonmmfata/ApiBlogpython.git](https://github.com/robsonmmfata/ApiBlogpython.git)
    ```

2.  Navegue até o diretório do projeto:

    ```bash
    cd ApiBlogpython
    ```

3.  Crie um ambiente virtual (recomendado):

    ```bash
    python -m venv venv
    source venv/bin/activate  # No Linux/macOS
    venv\Scripts\activate  # No Windows
    ```

4.  Instale as dependências:

    ```bash
    pip install -r requirements.txt
    ```

5.  Configure o banco de dados:

    * Configure as variáveis de ambiente para a conexão com o banco de dados.
    * Execute as migrações do Tortoise ORM para criar as tabelas:

        ```bash
        aerich upgrade
        ```

6.  Execute a API:

    ```bash
    uvicorn main:app --reload
    ```

##  Documentação da API

A documentação da API será gerada automaticamente pelo FastAPI e estará disponível em:

* `http://127.0.0.1:8000/docs` (Documentação Swagger UI)
* `http://127.0.0.1:8000/redoc` (Documentação ReDoc)

##  Contribuição

Contribuições são bem-vindas! Sinta-se à vontade para abrir issues e pull requests.

##  Licença

Este projeto está licenciado sob a [Licença MIT](LICENSE).

---

Feito com ❤️ por Robsonmmfata.
