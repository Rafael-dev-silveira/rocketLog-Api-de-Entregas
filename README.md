API do zero para um aplicativo de delivery 
=
Com Docker, Postgres, Prisma e Zod para validação de dados, entre outras ferramentas.
=

A API terá perfis de vendedor e cliente, com níveis de acesso definidos,envio de pedidos, gerenciar status como "processando", "enviado" e "entregue", e registrar as movimentações da entrega. Isso permitirá que os usuários acompanhem o status de suas entregas em tempo real,
e middleware para gerenciar exceções na nossa aplicação.

Biblioteca Zod para validar parâmetros e requisições em nossa aplicação
=
Verificar se um erro é uma instância de ZodError e a retornar mensagens formatadas adequadas. Com isso, aprimoramos nosso tratamento de exceções, garantindo que erros de validação sejam tratados de forma clara e organizada,
construir a estrutura básica da nossa API, focando na criação de rotas e controllers para usuários,começamos a trabalhar com o Docker para rodar um banco de dados Postgres em um container.

Exploramos como configurar uma API para cadastro de usuários utilizando o Prisma e o Zod para validação de dados.Começamos com uma requisição POST e, em seguida, implementamos a validação dos campos nome, e-mail e senha. 

Aprendemos a desestruturar os dados recebidos e a aplicar regras de validação, como comprimento mínimo e formatação correta.

Ao final, testamos as validações no Insomnia, garantindo que os dados atendam aos critérios estabelecidos antes de serem processados.

Implementar rota para enviar pedidos no nosso sistema
=
Focamos no controller de deliveries, onde trabalhamos no método de criação. 

Utilizamos o Prisma para interagir com o banco de dados e realizamos a validação dos dados recebidos. 

Após configurar o método, testamos a funcionalidade usando o Insomnia, enviando um pedido com o ID do usuário e uma descrição. 

Ao final, confirmamos que o registro foi criado corretamente na tabela de entregas.

Implementação de testes automatizados na nossa aplicação
=

Começamos com a instalação das ferramentas necessárias, como o Jest e o Supertest, utilizando o npm.

Instalar as versões específicas e as tipagens correspondentes, tudo como dependências de desenvolvimento. 

Conclusão :
=

Ao final, conferi o package.json para garantir que tudo foi instalado corretamente,
desenvolvi uma aplicação de entregas e Aprendi a criar a API e a implementar testes automatizados, focando nos controllers de usuário e sessões.



