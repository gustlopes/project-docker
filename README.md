Projeto Full-Stack em Docker:

Gustavo Lopes Melo (1134429)
Fabrício Biasi Brunetto (1135495)

Em resumo; o nosso trabalho é uma aplicação full-stack que integra o frontend em React, o backend utilizando Spring Boot (Java) e o banco de dados MySQL. Tudo organizado com o Docker & Docker Compose.

Nosso projeto utiliza uma arquitetura baseada em APIs RESTful, onde o frontend React se comunica com o backend Spring Boot para manipulação de dados armazenados no banco de dados do MySQL.

Sua forma de execução seria toda feita em dois Docker’s. Um para o funcionamento de todo o backend e frontend (juntamente do DataBase) e o outro iria funcionar para rodar nossa aplicação em Java e assim se conectar com o banco de dados.

Nossa principal fonte foi o repositório do GitHub "awesome-docker", onde pegamos a base total do nosso trabalho e apenas fazendo algumas alterações para seu funcionamento na porta 8080.
