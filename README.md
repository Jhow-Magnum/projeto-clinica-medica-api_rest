# Projeto de API Rest com Spring Boot 3

## Objetivos

O objetivo deste projeto é desenvolver uma API Rest com as seguintes funcionalidades:

- CRUD (Create, Read, Update e Delete)
- Validações
- Paginação e ordenação

Desenvolveremos um CRUD, que são as quatro operações fundamentais das aplicações: cadastro, listagem, atualização e exclusão de informações. Também implementaremos validações utilizando o Bean Validation e aplicaremos paginação e ordenação nas respostas da API.

## Tecnologias e Ferramentas Utilizadas

Durante o desenvolvimento do projeto, utilizaremos as seguintes tecnologias e ferramentas:

- **Spring Boot 3**: A última versão disponibilizada pelo framework.
- **Java 17**: A versão LTS (Long-term support) com maior tempo de suporte disponível.
- **Lombok**: Para geração de códigos repetitivos como getters, setters, toString, entre outros.
- **MySQL/Flyway**: MySQL para armazenar informações da API e Flyway para controle de histórico de evolução do banco de dados (Migration).
- **JPA/Hibernate**: JPA (Java Persistence API) com Hibernate como implementação para a camada de persistência.
- **Maven**: Para gerenciar dependências do projeto e gerar o build da aplicação.
- **Insomnia**: Ferramenta para testar a API, simulando requisições e verificando funcionalidades implementadas.

## Estrutura do Projeto

O projeto será estruturado para ser o mais simples e eficiente possível, utilizando os módulos do Spring Boot. O foco será exclusivamente no desenvolvimento do Back-end, sem interface gráfica (HTML, Front-end ou aplicativo mobile). Todas as funcionalidades da API serão testadas utilizando o Insomnia.

## Notações Utilizadas

- **@SpringBootApplication**: Marca a classe principal de configuração do Spring Boot.
- **@RestController**: Define uma classe como um controlador onde cada método retorna um objeto de domínio em vez de uma visão.
- **@RequestMapping**: Configura o mapeamento de URL para métodos de controlador.
- **@GetMapping, @PostMapping, @PutMapping, @DeleteMapping**: Especificam os métodos HTTP para as operações CRUD.
- **@Autowired**: Injeta automaticamente dependências.
- **@Entity**: Marca uma classe como uma entidade JPA.
- **@Table**: Especifica a tabela principal da entidade.
- **@Id**: Define o identificador primário da entidade.
- **@GeneratedValue**: Configura a geração automática do valor do identificador.
- **@Column**: Configura a coluna de uma tabela.
- **@Bean**: Indica que um método produz um bean gerenciado pelo Spring.
- **@Configuration**: Indica que a classe tem métodos @Bean que devem ser gerenciados pelo Spring.
- **@EnableJpaRepositories**: Habilita a criação de repositórios JPA.

## Instruções para Configuração

1. **Clone o repositório:**
   ```sh
   git clone https://github.com/seu-usuario/nome-do-repositorio.git
   ```

2. **Navegue até o diretório do projeto:**
   ```sh
   cd nome-do-repositorio
   ```

3. **Compile e execute o projeto utilizando Maven:**
   ```sh
   mvn spring-boot:run
   ```

4. **Utilize o Insomnia para testar a API.**

---

Este README foi criado para fornecer uma visão geral do projeto e das tecnologias utilizadas.
