
### O que é um banco de dados (DB) ?

	Coleção organizada de informações ou estrutura de dados geralmente armazenados em um sistema eletrônico/ sistema de PC. O principal objetivo é facilitar o armazenamento, recuperação e gerenciamento inteligente de dados.


## Tipos de banco de dados

	DB(relacional) SQL -> utiliza tabelas para o armazenamento de dados com   relacionamentos bem definidos.
	DB(não relacional) noSQL -> Projetado para armazenar grande volume de dados sem uma estrutura rígida, ex: MongoDB, Redis, Cassandra. 

## Sistema Gerenciador de Banco De Dados Relacional (SGBDR)

É um software que tem como objetivo criar, gerenciar e manipular dbr, exemplos:

	- MySQL
	- SQLite
	- PostgreSQL
	- SQL Server
	- Oracle Database
	
	-> Garantia da integridade e consistência dos dados
	-> Controle de concorrência
	-> Suporte a transações (ACID)

## Db vs SGBD

Banco de dados é qualquer conjunto de dados organizados.

	SGDB -> gerencia e manipula os bancos de dados
	Regra de segurança
	O SGDB diminui a complexidade dos dados pela camada de abstração
	SGDB Dados concisos, não deixa ter duplicatas, usuários inválidos por exemplo.

## Abstração de dados

#### Relacionamento entre informações
	A abstração de dados envolve a organização dos dados em diferentes níveis para permitir um gerenciamento eficiente.
	
##### Nível externo ou de visão
	Descreve as partes do banco de dados que o usuário tem permissão de acesso.

##### Nível conceitual
	Define a estrutura geral do db, incluindo entidades, relacionamentos e regras de integridade.

##### Nível interno ou físico
	Descreve como os dados são realmente armazenados no hardware do sistema.


## Normalização de Dados
	A normalização é um processo para reduzir redundância e melhorar a integridade dos dados.

### Formas Normais

## Gerenciador de transação

...

#### Propriedades de transação - ACID

	- Atomicidade
	O conjunto de operações agrupados em uma transação, devem ser realizados integralmente ou não realizados
	- Consistência
	- Isolamento
	- Durabilidade


