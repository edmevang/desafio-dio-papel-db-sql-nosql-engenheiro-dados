# Desafio - O Papel dos Bancos de Dados SQL e NoSQL na Engenharia de Dados
## Bootcamp Database Experience na Dio.me


### Contexto geral sobre banco de dados
O Engenheiro de dados deve saber lidar com o banco de dados pois há muitas opções no mercado.
O ideal é usar a ferramenta certa para o problema certo; isso aplica-se a banco de dados.

Não deve haver preferências ou restrições mas deve aliar aos benefícios e ao contexto em que a empresa se encontra na escolha do banco de dados.

É encontrado na maioria das empresas os bancos de dados em ambiente híbrido, ora on-promise (local) ou em serviços cloud (na nuvem).

## Bancos Relacionais (SQL)
É aquele em que informações a serem armazenadas possuem relacionamentos entre si, onde há normalização das informações e o esquema de dados rígido.
Ex. sistema transacional como um e-comerce com pedidos online e seus produtos.
São bancos transacionais conhecidos como OLTP.


### Exemplos:
* MySQL
* Postgres

## Bancos Não Relacionais (NoSQL)
É uma alternativa aos bancos relacionais mas não é substituto, os conceitos e os propósitos entre eles são diferentes.
Tem escalabilidade horizontal além de armazenar um volume maior de informações não estruturadas (não rígida ou que não conhecemos).
Ex. vídeos, fotos, etc.
A complexidade das consultas é reduzida ao passo que as vezes no modelo relacional temos vários que fazer vários joins para relacionar as variadas tabelas.
A performance está ligada a forma como as chaves/valor estão dispostas no caso dos bancos deste tipo e são cuidados a serem tomados na modelagem destes bancos.

### Exemplos:
* MongoDB
* Cassandra
* Redis e Neo4J