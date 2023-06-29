# Projeto Loja de Games

## Descrição
O projeto Loja de Games é uma aplicação Java que utiliza o framework Spring Boot, o banco de dados MySQL e o Insomnia para testes CRUD. 
O objetivo do projeto é fornecer uma API para gerenciar produtos e categorias de uma loja de games, permitindo a realização de operações de criação, 
leitura, atualização e exclusão de registros.

## Funcionalidades
- CRUD completo para o recurso Produto, com 6 métodos: criar, ler, atualizar e excluir produtos.
- CRUD completo para o recurso Categoria, com 6 métodos: criar, ler, atualizar e excluir categorias.
- Relacionamento do tipo One-to-Many entre as classes Categoria e Produto.
- Utilização do padrão MVC (Model-View-Controller) no Spring: Model, Repository e Controller.
- Testes de toda a API no Insomnia.

## Pré-requisitos
Antes de executar o projeto, verifique se você possui os seguintes requisitos:
- Java Development Kit (JDK) instalado na versão X.X.X ou superior.
- MySQL instalado e configurado.
- Insomnia (ou outro software de teste de API) instalado.

## Instalação e Configuração
Siga os passos abaixo para instalar e configurar o ambiente do projeto:

1. Faça o clone deste repositório.
2. Importe o projeto na sua IDE de preferência.
3. Configure as informações de conexão com o banco de dados MySQL no arquivo `application.properties` (localizado em `src/main/resources`).
4. Execute o script SQL fornecido para criar o banco de dados e as tabelas necessárias.
5. Inicie a aplicação.

## Utilização
Para utilizar a API, siga as instruções abaixo:

1. Abra o Insomnia (ou outro software de teste de API).
2. Importe a coleção de requisições disponível no arquivo `insomnia_collection.json`.
3. Execute as requisições disponíveis para interagir com os recursos de produtos e categorias.
4. Testes Endpoints no Insomnia:

   - PRODUTOS
     - GET - Consultar todos os Produtos (`http://localhost:8080/produtos`)
     - GET - Consultar produtos por ID (`http://localhost:8080/produtos/2`)
     - GET - Consultar produtos por Título (`http://localhost:8080/produtos/titulo/jogo`)
     - POST - Cadastrar Produto (`http://localhost:8080/produtos`)
     - PUT - Atualizar Produto (`http://localhost:8080/produtos`) - JSON file
     - DELETE - Deletar Produto (`http://localhost:8080/produtos/3`)

   - CATEGORIAS
     - GET - Consultar todos as Categorias (`http://localhost:8080/produtos`)
     - GET - Consultar Categorias por ID (`http://localhost:8080/produtos/2`)
     - GET - Consultar Categorias por Descrição (`http://localhost:8080/produtos/titulo/jogo`)
     - POST - Cadastrar Categorias (`http://localhost:8080/produtos`)
     - PUT - Atualizar Categorias (`http://localhost:8080/produtos`) - JSON file
     - DELETE - Deletar a Categoria (`http://localhost:8080/categorias/1`)


## Contribuição
Você pode contribuir para o projeto seguindo os passos abaixo:

1. Faça um fork do repositório.
2. Crie uma branch para realizar suas modificações.
3. Faça as modificações desejadas.
4. Teste as modificações e verifique se estão funcionando corretamente.
5. Submeta um pull request com suas modificações.

## Autora (Exercício da Generation Brasil)

- Elise Flaneuse(https://github.com/eliseflaneuse))
enciado sob a [Licença XYZ](URL da licença).

## Contato
Para entrar em contato com a desenvolvedora do projeto, envie um email para [eliseflaneuse@gmail.com](mailto:eliseflaneuse@gmail.com) ou abra uma issue no repositório.

