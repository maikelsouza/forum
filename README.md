# forum-api
Curso sobre Spring Boot API REST da Alura. Esse curso usa as seguintes tecnologias SpringRest, Spring-data-jpa, Jakarta EE (especificações e implementação,  respectivamente: Jakarta Persistence e Hibernate-core, Jakarta Bean Validation e Hibernate-validation),  h2-database e java 8


# Acesso a API
Para acesso a API, sugiro utilizar o software Postman. Você consegue importar o arquivo Forum - Alura.postman_collection.json localizado em: /forum/src/main/resources/postman/ 

# Acesso ao Banco de Dados
Essa API utiliza o h2-database. Basta você usar o usuário "sa" e a senha "" que o Spring cria o banco e o arquivo data.sql, localizado em: /forum/src/main/resources, popula o banco. Para acessar o banco, você consegue fazer isso colocando o seguinte endereço no navegador: http://localhost:8080/h2-console