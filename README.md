![image](https://github.com/user-attachments/assets/688d2784-7ccb-4389-8880-3bd2aca31ca9)



# API REST com Spring 

Esta é uma API REST desenvolvida em Spring Framework, que implementa operações CRUD completas (Create, Read, Update, Delete) para gerenciar tópicos. A API segue as melhores práticas do modelo REST, incluindo validações de regras de negócio, persistência em uma base de dados relacional e autenticação/autorização.

## Funcionalidades

- **Criar um novo tópico**  
  Permite a criação de um novo tópico com as informações fornecidas pelo usuário.

- **Listar todos os tópicos descritos**  
  Retorna uma lista completa de todos os tópicos cadastrados na base de dados.

- **Consultar um tópico específico**  
  Busca e exibe as informações de um tópico com base no identificador fornecido.

- **Atualizar um tópico**  
  Permite modificar os dados de um tópico existente, identificando-o pelo seu ID.

- **Excluir um tópico**  
  Remove um tópico da base de dados com base no identificador fornecido.

## Tecnologias Utilizadas

- **Java**: Linguagem principal da aplicação.
- **Spring Boot**: Framework utilizado para a criação da API.
- **Banco de Dados Relacional**: Utilizado para persistência dos dados.
- **Spring Security**: Implementação de autenticação e autorização.
- **Hibernate**: Para mapeamento objeto-relacional (ORM).

## Recursos Principais

- **Operações CRUD**  
  Implementação completa das operações básicas: criar, ler, atualizar e excluir tópicos.

- **Modelo RESTful**  
  Rotas e métodos HTTP (GET, POST, PUT, DELETE) implementados seguindo as melhores práticas REST.

- **Validações de Regras de Negócio**  
  Garantia de que as informações contidas respeitam os critérios definidos.

- **Persistência de Dados**  
  Uso de um banco de dados relacional para armazenar informações de forma segura.

- **Autenticação e Autorização**  
  Restrição de acesso às rotas da API, garantindo segurança e controle sobre os dados.

## Como Rodar a Aplicação

### Pré-requisitos

- JDK 17 ou superior
- Banco de dados relacional configurado (ex.: MySQL, PostgreSQL)
- Ferramenta para realizar requisições HTTP (ex.: Postman ou cURL)

### Passos

1. **Clonar este repositório:**

   ```bash
   git clone <url-do-repositorio>


2. **Configure o arquivo application.propertiescom as credenciais do banco de dados.**

Execute o comando Maven para compilar e iniciar o projeto:
  ```bash
  mvn spring-boot:run
```

3. **Acessar a API via:**  

   Após iniciar o projeto, a API estará disponível no endereço:  
   [http://localhost:8080](http://localhost:8080).  

### Observações
- Certifique-se de que o banco de dados está configurado corretamente e em execução.
- Utilize ferramentas como **Postman** ou **cURL** para testar as rotas da API.
- Para acessar rotas protegidas, obtenha um token de autenticação, se necessário, seguindo o fluxo de autenticação configurado no projeto.

Agora você pode explorar e utilizar os endpoints da API REST para gerenciar tópicos conforme as funcionalidades descritas!

