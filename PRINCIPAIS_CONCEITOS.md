# Spring Boot JPA and ORM Concepts

Este repositório contém um exemplo básico de aplicação Spring Boot que utiliza JPA (Java Persistence API) e Hibernate para mapeamento objeto-relacional.

## Conceitos Principais

### 1. ORM (Object-Relational Mapping)

ORM é uma técnica de programação que permite mapear objetos de uma aplicação para tabelas em um banco de dados relacional e vice-versa, reduzindo a necessidade de código SQL manual.

### 2. JPA (Java Persistence API)

JPA é uma especificação do Java que descreve um conjunto de funcionalidades para gerenciar dados relacionais em aplicações Java. Ele define como mapear classes Java para entidades de banco de dados.

### 3. Anotações de Mapeamento do JPA

- `@Entity`: Marca uma classe como uma entidade JPA.
- `@Table`: Especifica a tabela no banco de dados para a entidade.
- `@Id`: Marca um campo como chave primária da entidade.
- `@GeneratedValue`: Especifica a estratégia de geração de valores para a chave primária.
- `@Column`: Define o mapeamento entre um campo da entidade e uma coluna na tabela.
- `@OneToOne`, `@OneToMany`, `@ManyToOne`, `@ManyToMany`: Definem relacionamentos entre entidades.
- `@JoinColumn`, `@JoinTable`: Especificam detalhes de junção para relacionamentos entre entidades.
- `@Embedded`, `@Embeddable`: Mapeiam objetos embutidos em entidades.
- `@Transient`: Indica que um campo não deve ser persistido no banco de dados.

### Exemplo de Aplicação

Este repositório contém um exemplo simples de aplicação Spring Boot que demonstra o uso desses conceitos, incluindo:

- Configuração básica do Spring Boot.
- Definição de entidades JPA.
- Repositórios JPA para acesso a dados.
- Serviços e controladores para lógica de negócios e exposição de endpoints REST.

