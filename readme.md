# Query_Result_To_Excel

**Descrição:**

Este script é uma ferramenta para se conectar em múltiplas databases e extrair uma planilha com os resultados do SELECT de forma rápida.

---

**Estrutura:**

- conn.json: Arquivo que contém os dados para se conectar ao banco de dados.

- script.py: Script principal que se conecta ao banco de dados, executa a query e gera as planilhas.

- requirements.txt: Lista de dependências para rodar o projeto.

- query.sql: Arquivo no qual possui a query a ser executada.

---

**Requisitos:**

- Python 3
- PIP

---

**Instalação:**

- Clone o repositório ou faça o download na sua máquina.
- Acesse a pasta do projeto via terminal e instale as dependências com o comando: `pip install -r requirements.txt`

---

**Como usar:**

1. Insira as credenciais para acessar o banco de dados no arquivo "conn.json".

- No parâmetro "db_type", informe o tipo de banco de dados("mysql" ou "postgres").

- No parâmetro "databases", informe o nome de cada database desejada, separado por vírgulas.

- Ex: ["database1","database2","database3"]

2. Insira a consulta desejada no arquivo "query.sql".

3. Rode o "script.py" e aguarde a geração das planilhas na pasta do projeto.
