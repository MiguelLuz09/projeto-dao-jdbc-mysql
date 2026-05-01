# projeto-dao-jdbc-mysql

## MVC ??
Model View Controller é um padrão de arquitetura que organiza o projeto em partes com difrentes funções. Começando pela View, que é a parte visual, aquilo que o usuário enxerga, como por exemplo um botão colorido. O Controller é responsável pelo Funcionamento desse botão (como enviar dados de cadastro), assim ele recebe e envia ao Model. O Model é a camada que guarda tudo o que foi digitado (senha, cpf, nome, entre outros), ele avisa o Controller que por sua vez "ativa" a função do botão e devolve a resposta dessa ação para o View (esclarecendo, mostra ao usuário a mensagem "Cadastro Concluído!!!").

## DAO ??
DAO (Data Access Object) é o padrão de projeto que serve para separar Lógica de Negócios da Lógica de Persistência de dados. De forma bem simples: DAO faz com que as "condições" relacionadas a uma classe (por exemplo: Se Cliente pegar 10 produtos, Então ele receberá 10% de desconto na compra total) permaneça a mesma. Ele só interfere em como os Dados relacionados a essa classe (e-mail, senha, etc) serão recuperados após serem salvos em uma página Cadastro, exemplificando.


## JDBC ??
O Java Database Connectivity (JDBC) é uma API que funciona como um "intérprete" entre Java e SGBD (Sistemas de Gerenciamento de Banco de Dados). Explicando melhor: Imagine que java fala Inglês, e Mysql fala Japonês. O JDBC é o Intérprete ou a Ponte que liga essas duas camadas. Este também utiliza outras peças importantes para a comunicação entre esses dois elementos, tal como Driver, DriverManager, PreparedStatement e ResultSet.

# Mapa Conceitual


## Fontes de Pesquisa:

https://www.devmedia.com.br/introducao-ao-padrao-mvc/29308

https://www.devmedia.com.br/dao-pattern-persistencia-de-dados-utilizando-o-padrao-dao/30999

https://www.imperva.com/learn/application-security/business-logic/

https://www.blip.ai/blog/tecnologia/persistencia-de-dados/

https://www.alura.com.br/artigos/conhecendo-o-jdbc
