# Sistema de Pagamentos para E-commerce com Microsservicos, Java, Spring-Boot, IaC, CDK e AWS

## Descrição
Este é um microserviço responsável pela gestão de pedidos do Alura Food.

## Dependências
O projeto foi desenvolvido utilizando o Spring Boot e as seguintes dependências:

- `spring-boot-starter-data-jpa`: Starter do Spring Boot para suporte a acesso a dados com JPA.
- `spring-boot-starter-validation`: Starter do Spring Boot para validações de dados.
- `spring-boot-starter-web`: Starter do Spring Boot para criação de aplicativos da web, incluindo RESTful.
- `flyway-core`: Biblioteca de controle de versão para bancos de dados.
- `spring-boot-devtools`: Ferramenta do Spring Boot para desenvolvimento que permite o reinício automático do aplicativo quando há alterações no código.
- `mysql-connector-java`: Driver JDBC do MySQL para conexão com o banco de dados MySQL.
- `lombok`: Biblioteca que fornece anotações para redução de código repetitivo.
- `spring-boot-starter-test`: Starter do Spring Boot para testes de unidade.
- `modelmapper`: Biblioteca para mapeamento de objetos Java.
- `spring-cloud-starter-netflix-eureka-client`: Starter do Spring Cloud para integração com o serviço Eureka, responsável pelo registro e descoberta de microserviços.

## Requisitos
- Java 17 ou superior.

## Instalação
1. Clone este repositório em sua máquina local.
2. Execute o seguinte comando para construir o projeto e baixar as dependências:
   ```
   mvn clean install
   ```
3. Execute o seguinte comando para iniciar o aplicativo:
   ```
   mvn spring-boot:run
   ```

## Configuração
Para executar o microserviço corretamente, é necessário configurar o acesso ao banco de dados MySQL. Verifique os detalhes de configuração no arquivo `application.properties` localizado no diretório `src/main/resources`.

## Documentação da API
A documentação da API do microserviço está disponível em [http://localhost:8080/swagger-ui/](http://localhost:8080/swagger-ui/) após iniciar o aplicativo localmente.

## Contribuição
Se desejar contribuir para o projeto, siga os passos abaixo:

1. Crie um fork do repositório.
2. Crie um branch com sua contribuição: `git checkout -b minha-contribuicao`.
3. Faça suas alterações e commite: `git commit -m "Minha contribuição"`.
4. Envie seu branch para o repositório remoto: `git push origin minha-contribuicao`.
5. Crie um pull request no repositório original.

## Licença
Este projeto está licenciado sob a Licença MIT - veja o arquivo [LICENSE](LICENSE) para mais detalhes.
