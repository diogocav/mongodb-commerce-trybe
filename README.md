# Projeto MongoDB Commerce!

Projeto realizado durante módulo de Back-end do curso de desenvolvimento web da Trybe.
Neste projeto, trabalhei com o banco de dados commerce, banco de dados não relacional (MongoDB), que contém dados do cardápio do McDonald's, como ingredientes, valores nutricionais e dados fictícios de vendas. Nele apliquei métodos e operadores de CRUD. 

-----

  **Com Docker:**

  **:warning: Antes de começar, seu docker-compose precisa estar na versão 1.29 ou superior. [Veja aqui](https://www.digitalocean.com/community/tutorials/how-to-install-and-use-docker-compose-on-ubuntu-20-04-pt) ou [na documentação](https://docs.docker.com/compose/install/) como instalá-lo. No primeiro artigo, você pode substituir onde está com `1.26.0` por `1.29.2`.**

- [ ] `docker run -d --name=mongo-commerce -v "$PWD:/app" -p 27017:27017 mongo:5.0`
- [ ] `docker exec -it mongo-commerce bash`
- [ ] `cd app/`
- [ ] `mongorestore -d commerce -c produtos assets/produtos/produtos.bson`

**Localmente:**

**Necessita ter um banco de dados(MongoDb) instalado localmente**

-----
 
Tecnologias usadas no projeto:

- `MongoDb`
- `mongosh`
- `docker`

Operações realizadas:

- Alterar documentos utilizando métodos de update com operadores simples;
- Alterar documentos utilizando operadores complexos e modificadores;
- Construir queries e expressões complexas utilizando índices textuais e expressões regulares.  
