# projeto-dao-jdbc-mysql

## O que é o padrão DAO ??
DAO (Data Access Object) é o padrão de projeto que serve para separar Lógica de Negócios da Lógica de Persistência de dados. De forma bem simples: DAO faz com que as "condições" relacionadas a uma classe (por exemplo: Se Cliente pegar 10 produtos, Então ele receberá 10% de desconto na compra total) permaneça a mesma. Ele só interfere em como os Dados relacionados a essa classe (e-mail, senha, etc) serão recuperados após serem salvos em uma página Cadastro, exemplificando.


## O que é JDBC (Java Database Connectivity) ??
O Java Database Connectivity (JDBC) é uma API que funciona como um "intérprete" entre Java e SGBD (Sistemas de Gerenciamento de Banco de Dados). Explicando melhor: Imagine que java fala Inglês, e Mysql fala Japonês. O JDBC é o Intérprete ou a Ponte que liga essas duas camadas. Este também utiliza outras peças importantes para a comunicação entre esses dois elementos, tal como Driver, DriverManager, PreparedStatement e ResultSet.
