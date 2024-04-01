# PraticaSql

### **Atividade 1**

<br>

Após receber uma tarefa de aprendizado sobre consultas SQL, decidi explorar a plataforma , W3Schools. Decidi seguir um passo a passo detalhado, aplicando os conceitos aprendidos em consultas .

Explorando o Site:

Ao acessar a seção "SQL Intro" no W3Schools, encontrei uma variedade de recursos que cobrem desde o básico até tópicos mais avançados em SQL. Comecei revisando os fundamentos da linguagem SQL, como SELECT, WHERE, ORDER BY e LIMIT.

Realizando as Consultas:

Para garantir que eu estava compreendendo os conceitos adequadamente, utilizei o recurso "Try it Yourself" disponibilizado em cada tópico. Copiei e colei os exemplos de consulta em um ambiente de teste fornecido pela plataforma e executei as consultas para observar os resultados , Siga abaixo alguns dos testes que fiz. 

Documentando o Processo:

Para consolidar meu aprendizado e criar um recurso de referência pessoal, decidi documentar todo o processo em um repositório no GitHub. Criei um novo repositório chamado "praticaSQL" e incluí um arquivo README.md para fornecer uma visão geral da atividade.


<br>

**Consulta para Selecionar Dados de uma Tabela**

*Esta consulta seleciona todos os registros da tabela "usuarios":*

```sql
SELECT * FROM usuarios;
```

**Explicação:**

- A cláusula `SELECT` é usada para selecionar os dados.
- O `*` indica que queremos selecionar todas as colunas.
- `usuarios` é o nome da tabela da qual estamos selecionando os dados.


**Consulta com Condição WHERE**

*Esta consulta seleciona os usuários cujo ID é igual a 1:*


```sql
SELECT * FROM usuarios WHERE id = 1;
```

**Explicação:**

- A cláusula `WHERE` é usada para filtrar os resultados
  com base em uma condição especificada.
- `id = 1` é a condição. Aqui, estamos selecionando apenas
   os registros onde o valor da coluna "id" é igual a 1. 


**Consulta com Ordenação**

*Esta consulta seleciona todos os usuários ordenados 
por nome em ordem alfabética crescente:*

```sql
SELECT * FROM usuarios ORDER BY nome;
```

**Explicação**

- A cláusula `ORDER BY` é usada para classificar os resultados.
- `nome` é o nome da coluna pela qual queremos ordenar os resultados.


**Consulta com Limitação**

*Esta consulta seleciona os primeiros 5 registros da tabela "usuarios":*


```sql
SELECT * FROM usuarios LIMIT 5;
```

**Explicação:**

- A cláusula `LIMIT` é usada para limitar o número de registros retornados pela consulta.
- `5` é o número de registros que queremos recuperar.

<br>

### **Atividade 2 - 25/03/2024**

Passo 1: Acessei o MySQL e verifiquei quais bancos de dados existentes
Em seguida, digitei a senha que foi  solicitado. Depois de entrar no MySQL, digitei o comando abaixo para verificar quais bancos de dados existem:
```sql
SHOW DATABASES;
```
Passo 2: Criar um novo banco de dados
Criei um novo banco de dados, utilizando o comando `CREATE DATABASE` .
```sql
CREATE DATABASE loja;
```
Passo 3: Criar tabelas
Depois de criar o banco de dados, criei  as tabelas dentro dele.  adicionei  pelo menos três tabelas como solicitado.
```sql
USE loja
CREATE TABLE usuarios (
    id INT AUTO_INCREMENT PRIMARY KEY,
    nome VARCHAR(50),
    email VARCHAR(80),
    telefone VARCHAR(20)
);
```

Repeti o  processo para criar outras tabelas conforme necessário 

**Passo 4: Inserir registros**

eu inseri alguns registros em cada tabela que criei usando o comando abaixo 

```sql
INSERT INTO usuarios (nome, email) VALUES
('João', 'joao@gmail.com', '89 981276778'),
('Maria', 'maria@gamil.com', '89 981638389'),
('Pedro', 'pedro@gmail.com', '86 981268038'),
('Juliana, 'juliana@gmail.com', '86 981543298'),
('Carlos', 'carlos@gmail.com', '86 981652340'),
('Mariana', 'mariana@gmail.com', '89 98111099');
```
<br>

### **Atividade 3 **


