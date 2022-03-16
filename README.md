# cadastro-clientes-leonardo
CRUD simples para demonstração

# ------------ SISTEMA DE CADASTRO DE CLIENTES ------------

# 1. OBJETIVO DO PROJETO

O projeto atual tem como objetivo apenas demonstrar um 
cadastro simples em Java Web, utilizando o framework 
Spring e bootstrap para a navegação web.

# 2. COMO RODAR O PROJETO

# 2.1. Instale a IDE de sua escolha:

Instale o Eclipse EE ou IntelliJ para importar o projeto, 
em seguida, a própria IDE irá baixar automaticamente as 
dependencias do projeto, que constam no arquivo pom.xml

# 2.2. Instale o servidor de banco de dados e o SGBD

O projeto está configurado para rodar com o banco de 
dados MySQL na versão 8, caso queira utilizar outro banco 
de dados, altere o driver do mesmo no arquivo 
application.properties.

# 2.3. Crie o banco de dados em seu SGBD

Apesar do sistema criar automaticamente as entidades no 
banco de dados, será necessário criar o "schema" para que 
o sistema encontre e se conecte ao seu servidor. No MySQL, 
digite: 

create schema usuarios; (Digite enter)

Pronto! O banco está criado.

# 2.4. Execute o sistema com a IDE

Clique com o botão direito no arquivo Application.java e 
escolha a opção de executar. Agora é só esperar e acessar em 
seu navegador através do link: http://localhost:8080/

# 3. CONSIDERAÇÕES FINAIS

A senha do banco de dados (instância) está configurada da 
seguinte forma no application.properties:

spring.datasource.url=jdbc:mysql://localhost:3306/usuarios
spring.datasource.username=root
spring.datasource.password=Dev2020@

Caso a senha do seu servidor seja diferente, será necessário 
mudar no arquivo application.properties.

# 4. CONTATO
Leonardo de Lima Cavalcante - leonardo.l200018@gmail.com
LinkedIn: https://www.linkedin.com/in/leonardolimacavalcante
