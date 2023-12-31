# webapimovies

Ao longo do desenvolvimento de uma API a partir de Controllers, pude definir rotas, utilizando extensões para fazer a inserção de dependências e assim criar as actions para as minhas requests; como o HttpPost, para criar recursos dentro do sistema, além do HttpGet para recuperar dados e para passar alguma informação. 

Foi necessário definir a paginação para que muitos dados de consulta não retornassem de uma só vez. Desse modo, a atualização dos 'objetos' dentro do sistema puderam ser realizadas com os verbos HttpPut e HttpPatch, sendo que o PATCH permite a atualização parcial de informações configuradas previamente, com atributos e valores específicos. O HttpDelete, assim como nos demais verbos de atualização, também foi executado utilizando um 'ID' de identificação do referido objeto em sua URL.

A comunicação com a base de dados local foi estabelecida com o Entity Framework. Os DTOs serviram para a transferência de dados entre as camadas do código, que foi configurado através do appsettings.json, podendo ser carregados em tempo de execução ou no momento de inicialização da aplicação visualizada no Swagger. 

Ainda utilizei o DTOs para criar, ler e atualizar os registros e realizar conversões entre os diferentes tipos requisições,  além do AutoMapper, para mapear as informações entre os diferentes objetos cadastrados na base de dados. 

Este projeto com base em uma API de cadastro de filmes, além de recuperar informações, atualiza dados de diferentes maneiras (com o verbo PUT e com verbo PATCH) e deleta registros. A documentação desta API foi realizada no Swagger.

Esse projeto é público e aberto a contruibuições positívas!
