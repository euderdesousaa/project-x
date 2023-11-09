# Project-X

## Descrição
Este projeto é uma rede social estilo Twitter, construída utilizando as seguintes tecnologias: Java 17, Spring Boot, MySQL para o armazenamento de dados, RabbitMQ para mensageria assíncrona, Docker para a containerização e OAuth2 para autenticação.

## Funcionalidades
- **Criar Perfil:** Os usuários podem criar perfis personalizados.
- **Criar Post:** Poste mensagens para compartilhar com outros usuários.
- **Editar e Deletar:** Capacidade de editar ou excluir posts.
- **Feed:** Visualize um feed de posts de outros usuários.

## Documentação da API

A documentação da API está disponível através do Swagger. Você pode explorar a API localmente ou acessar a versão hospedada no Render.com.

### Acesso via Render.com

Se você não quiser clonar o repositório e prefere acessar a API diretamente no Render.com, siga estas etapas:

1. Abra o navegador e acesse [https://sua-api-no-render.render.com/swagger-ui.html](https://api-projectx.onrender.com)

A interface Swagger fornecerá informações detalhadas sobre os endpoints disponíveis, os parâmetros necessários e exemplos de solicitações e respostas.

### Acesso Local

Se você preferir executar a aplicação localmente, siga as etapas abaixo:

1. Certifique-se de que o aplicativo está em execução.
2. Abra o navegador e acesse http://localhost:8080/swagger-ui.html

## Uso
Crie um perfil.
Faça login via Google e explore as funcionalidades de criar, editar e deletar posts.
Confira o feed para ver os posts de outros usuários.

## Tecnologias Utilizadas
- **Docker** é uma plataforma de virtualização que permite executar aplicativos em containers isolados.
- **MySQL** é um sistema de gerenciamento de banco de dados relacional.
- **Java 17** é a versão mais recente da linguagem de programação Java.
- **Spring** é um framework de desenvolvimento Java que facilita a construção de aplicações web e de microsserviços.
- **RabbitMQ** é um servidor de mensageria AMQP.
- **OAuth2** é um protocolo de autorização que permite que os usuários compartilhem suas credenciais com aplicativos de terceiros.
- **Swagger** é uma ferramenta que permite documentar APIs REST.

## Instalação e Execução
1. Clone este repositório.
   ```bash
   git clone https://github.com/euderdesousaa/project-x
   
2. Navegue até o diretório do projeto.
      ```bash
   cd project-x
      
3. Configure as variáveis de ambiente para MySQL, RabbitMQ e OAuth2.

5. Execute o aplicativo.
   ```bash
   docker-compose up
