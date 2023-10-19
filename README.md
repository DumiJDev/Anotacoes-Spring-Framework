[![NPM](https://img.shields.io/npm/l/react)](https://github.com/lucarauj/Anotacoes-Spring-Framework/blob/main/LICENSE)

<h1 align="center">Anotações Spring Framework</h1>

<p align="center"><img width="400px" src="https://github.com/lucarauj/assets/blob/main/Spring.png" /></p>

<br>

<p align="center">
  <a href="#-a">A</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-b">B</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-c">C</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-d">D</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-e">E</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-f">F</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-g">G</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-i">I</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-j">J</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-l">L</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-m">M</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-n">N</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-o">O</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-p">P</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-q">Q</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-r">R</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-s">S</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-t">T</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-v">V</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-w">W</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
</p>

<br>


## 📜 A

- @ActiveProfiles("test"):
>*sobrescreve as propriedades definidas no arquivo application.properties ao executar os testes, usando o perfil "test".*
- @AfterAll:
>*indica que o método será executado depois de todos os testes em uma classe de teste.*
- @AfterEach:
>*indica que o método será executado depois de cada teste em uma classe de teste.*
- @AllArgsConstructor:
>*gera automaticamente um construtor com todos os atributos da classe.*
- @Autowired:
>*delega ao Spring a injeção de dependência e inicialização do objeto.*
- @AutoConfigureMockMvc:
>*injeta o objeto MockMvc no contexto da aplicação para testes de integração.*
- @AutoConfigureJsonTesters:
>*habilita e configura automaticamente os testadores de JSON para os testes.*

<br>

## 📜 B

- @Bean:
>*indica que o método retorna um objeto gerenciado pelo Spring e que deve ser registrado como um bean.*
- @BeforeAll:
>*indica que o método será executado antes de todos os testes em uma classe de teste.*
- @BeforeEach:
>*indica que o método será executado antes de cada teste em uma classe de teste.*

<br>

## 📜 C

- @Captor:
>*captura argumentos de um método para uso em testes.*
- @Cacheable:
>*permite que o resultado de um método seja armazenado em cache pelo Spring para evitar a execução repetida do método com os mesmos parâmetros.*
- @CircuitBreaker:
>*habilita o padrão de circuit breaker em um método de um aplicativo Spring.*
- @CPF:
>*anotação que valida se um valor numérico passado corresponde a um número de CPF válido.*
- @CollectionTable:
>*usada para mapear uma tabela de coleção em uma entidade.*
- @Column:
>*especifica o mapeamento entre um atributo de entidade básico e a coluna correspondente na tabela de banco de dados.*
- @Component:
>*é um estereótipo genérico para qualquer componente gerenciado pelo Spring.*
- @ComponentScan:
>*instrui o Spring a buscar classes anotadas com @Configuration e outras anotações de componentes em um pacote para registrar e gerenciar beans no contexto de aplicação.*
- @Configuration:
>*indica que a classe é uma classe de configuração do Spring que define beans e configurações adicionais.*
- @ConfigurationProperties:
>*usada para mapear um grupo de propriedades em uma classe.*
- @ConvertGroup(from = Default.class, to = ValidationGroups.{parameter}.class):
>*converte de um "grupo de validação" para outro.*
- @ControllerAdvice:
>*permite manipular exceções globalmente em um aplicativo Spring.*
- @CreatedDate:
>*recurso de auditoria fornecido pelo Spring Data JPA que rastreia a data de criação de uma entidade.*
- @CreationTimestamp:
>*registra automaticamente a data e hora em que uma entidade é criada no banco de dados.*
- @CrossOrigin:
>*permite a comunicação entre domínios para métodos manipuladores de solicitações.*

<br>

## 📜 D

- @Data:
>*Gera o código padronizado (getters, setters, toString apropriado, equals e implementações hashCode) para os campos de uma classe.*
- @DataJpaTest:
>*Usada para testar uma interface Repository em um ambiente de teste.*
- @DisplayName("String"):
>*Usada para fornecer um nome personalizado para a classe de teste ou método de teste.*
- @DeleteMapping:
>*Usada para mapear solicitações HTTP DELETE para métodos manipuladores específicos.*
- @DecimalMin:
>*Especifica que a propriedade decorada com essa anotação deve ter um valor maior ou igual ao mínimo especificado.*
- @DisplayName():
>*Nomeia um teste.*
- @DisableIfEnvironmentVariable():
>*Executa o método se as variáveis de ambiente fornecidas forem falsas.*

<br>

## 📜 E

- @EqualsAndHashCode:
>*Gera automaticamente os métodos equals e hashCode para os campos do objeto.*
- @Embeddable:
>*Especifica que um tipo é incorporável e será gerenciado pela entidade proprietária.*
- @Embedded:
>*Especifica que um determinado atributo de entidade representa um tipo incorporável.*
- @EmbeddedId:
>*Especifica que o identificador de entidade é um tipo incorporável.*
- @EnableFeignClients:
>*Habilita o uso do Feign na aplicação.*
- @EnableCaching:
>*Ativa o cache na aplicação.*
- @EnableFeignClients:
>*habilita o processo de criação automática de clientes Feign a partir das interfaces marcadas com @FeignClient.*
- @EnableWebSecurity:
>*Habilita recursos de segurança em uma aplicação.*
- @EnableGlobalMethodSecurity:
>*Habilita o uso de anotações com regras de segurança.*
- @EnableR2dbcAuditing:
>*Configura o mecanismo de auditoria no contexto do Spring para uso com R2DBC.*
- @Enumerated(EnumType.STRING):
>*Especifica que a representação de uma enumeração será armazenada como uma String na coluna correspondente na tabela do banco de dados.*
- @ElementCollection:
>*Especifica que um campo representa uma coleção de elementos embutidos ou básicos.*
- @ElementCollection(fetch = FetchType.EAGER):
>*Especifica que a coleção de elementos embutidos ou básicos deve ser buscada imediatamente.*
- @Entity:
>*Especifica que a classe anotada representa uma entidade.*
- @Email:
>*Verifica se o valor de um campo possui as características de um endereço de e-mail.*
- @EnableIfEnvironmentVariable():
>*Executa o método se as variáveis de ambiente fornecidas forem verdadeiras.*
- @EnableOnOs():
>*Executa o método se os parâmetros informados relacionados ao sistema operacional forem verdadeiros.*
- @EnableOnJre():
>*Executa o método se os parâmetros informados relacionados à JRE forem verdadeiros.*
- @EnableForJreRange():
>*Executa o método se os parâmetros informados relacionados às versões da JRE forem verdadeiros.*
- @EnableEurekaServer:
>*permite que o aplicativo funcione como um servidor de registro para outros serviços.*
- @EnableEurekaClient:
>*permite que o aplicativo se registre em um servidor Eureka e utilize a descoberta de serviços fornecida pelo Eureka.*
- @ExtendWith(MockitoExtension.class):
>*Permite o uso do Mockito como uma extensão para o framework de teste, fornecendo recursos adicionais para criação e uso de objetos simulados (mocks) durante os testes.*
- @ExceptionHandler:
>*Permite que um método trate uma exceção específica quando ela é lançada.*

<br>

## 📜 F

- @FeignClient:
>*Injeta o cliente no contexto do Spring para facilitar a comunicação com serviços HTTP.*
- @Future:
>*Define que a variável só pode receber uma data futura.*

<br>

## 📜 G

- @GeneratedValue(GenerationType.AUTO):
>*Estratégia padrão para geração de valores de identificador. A JPA escolhe a estratégia mais apropriada com base no banco de dados configurado para a aplicação.*
- @GeneratedValue(GenerationType.SEQUENCE):
>*Utiliza uma sequência no banco de dados para gerar os valores dos identificadores. É necessário adicionar a anotação @SequenceGenerator para configurar a sequência.*
- @GeneratedValue(GenerationType.IDENTITY):
>*Usada quando o banco de dados suporta colunas autoincrementais, como AUTO_INCREMENT no MySQL ou IDENTITY no SQL Server.*
- @GeneratedValue(GenerationType.UUID):
>*Indica que o valor do identificador único da entidade será gerado pelo provedor de persistência usando a estratégia UUID.*
- @GeneratedValue(GenerationType.TABLE):
>*Utiliza uma tabela especial no banco de dados para gerar os valores dos identificadores. É necessário adicionar a anotação @TableGenerator para configurar a tabela.*
- @GetMapping:
>*Mapeia solicitações HTTP GET para métodos manipuladores específicos.*
- @Getter:
>*Cria automaticamente os métodos getter para todos os atributos da classe usando o Lombok.*

<br>

## 📜 I

- @Id:
>*Especifica o identificador da entidade. Uma entidade sempre deve ter um atributo identificador.*
- @InjectMocks:
>*Cria e injeta instâncias simuladas para serem usadas em testes com o Mockito.*

<br>

## 📜 J

- @JsonAlias:
>*Mapeia apelidos alternativos para os campos recebidos em JSON.*
- @JsonFormat(pattern = "dd/MM/yyyy HH:mm"):
>*Especifica o formato esperado para a data/hora ao serializar ou desserializar em JSON.*
- @JsonInclude(Include.NON_NULL):
>*Inclui apenas as propriedades não nulas ao serializar em JSON.*
- @JsonProperty(access = READ_ONLY):
>*Indica que o parâmetro é somente leitura.*
- @JsonIgnore:
>*Marca uma propriedade para ser ignorada durante a serialização/desserialização JSON no nível do campo.*
- @JsonIgnoreProperties:
>*Marca uma propriedade ou um grupo de propriedades para serem ignoradas durante a serialização/desserialização JSON.*
- @JoinColumn:
>*Define o mapeamento físico no lado proprietário em um relacionamento um-para-muitos/muitos-para-um.*
- @JoinTable:
>*Define o nome de uma tabela intermediária em um relacionamento muitos-para-muitos.*

<br>

## 📜 L

- @LastModifiedDate:
>*Utilizada para rastrear quando a entidade foi modificada pela última vez.*

<br>

## 📜 M

- @Min:
>*Usada para aplicar validações de valor mínimo a propriedades de um objeto.*
- @Modifying:
>*Informa ao Spring Data que a consulta anotada com @Query é uma operação de escrita (atualização, exclusão, etc.) e não uma consulta de leitura.*
- @Modifying(clearAutomatically = true):
>*indica ao Spring Data JPA que a consulta resultará em uma modificação no banco de dados e que o contexto de persistência deve ser limpo automaticamente após a execução da consulta.*
- @Mock:
>*Cria um objeto simulado (mock) usado para testes com o Mockito.*
- @MockBean:
>*Cria um objeto simulado (mock) de uma classe ou interface e o adiciona ao contexto de aplicação para uso em testes.*
- @ManyToOne:
>*Especifica um relacionamento de banco de dados muitos-para-um.*
- @ManyToMany:
>*Especifica um relacionamento de banco de dados muitos-para-muitos, onde muitos registros de uma entidade estão relacionados com muitos registros de outra entidade.*
- @MappedSuperclass:
>*Usada em classes que contêm campos e métodos que devem ser herdados por entidades filhas.*

<br>

## 📜 N

- @NotBlank:
>*Valida que um atributo do tipo String não pode ser nulo e nem vazio.*
- @NotNull:
>*Checa se o valor anotado não é nulo (null).*
- @NoArgsConstructor:
>*Gera um construtor sem parâmetros automaticamente.*
- @NotEmpty:
>*Valida que a propriedade não é nula nem vazia. Pode ser utilizada com String, Collection, Map ou array.*

<br>

## 📜 O

- @Order:
>*Define a ordem de execução de um componente ou método dentro de um sistema.*
- @OneToMany:
>*Especifica um relacionamento de banco de dados um-para-muitos.*
- @OneToOne:
>*Especifica um relacionamento de banco de dados um-para-um.*

<br>

## 📜 P

- @PathVariable:
>*Indica que o valor da variável virá de uma informação presente na rota.*
- @PageableDefault:
>*Permite informar parâmetros padrão de paginação e ordenação.*
- @Param:
>*Indica que o parâmetro é um parâmetro de um método.*
- @PatchMapping:
>*Mapeia solicitações HTTP PATCH para métodos manipuladores específicos.*
- @Pattern:
>*Checa se a propriedade obedece a uma expressão regular.*
- @Past:
>*Valida se o valor da data está no passado.*
- @PostMapping:
>*Mapeia solicitações HTTP POST para métodos manipuladores específicos.*
- @Positive:
>*Valida se o valor numérico passado é positivo.*
- @PutMapping:
>*Mapeia solicitações HTTP PUT para métodos manipuladores específicos.*
- @PreAuthorize:
>*Verifica a expressão dada antes de executar o método.*
- @Primary:
>*Usada quando existem dois métodos anotados com @Bean que retornam o mesmo tipo de objeto. Indica qual deles será injetado por padrão quando for solicitado.*
- @Profile:
>*Indica em qual perfil (profile) o bean deve ser carregado.*

<br>

## 📜 Q

- @Query:
>*Permite criar instruções SQL personalizadas e expor essas instruções como métodos DAO.*
- @Qualifier:
>*Usada para especificar qual bean deve ser injetado em um componente Spring quando há ambiguidade.*

<br>

## 📜 R

- @RestController:
>*Marca a classe como um controlador no qual cada método retorna um objeto de domínio em vez de uma visão.*
- @RestControllerAdvice:
>*Torna uma classe um componente especializado em tratar exceções e o retorno dos métodos dessa classe deve ser inserido no corpo da resposta HTTP e convertido para JSON.*
- @Repository:
>*Define uma classe como pertencente à camada de persistência (repository).*
- @RequestBody:
>*Indica que o valor do objeto virá do corpo da requisição.*
- @RequestMapping:
>*Mapeia solicitações da web para classes manipuladoras específicas e métodos manipuladores.*
- @RequestParam:
>*Mapeia os parâmetros HTTP para argumentos de métodos.*
- @Required:
>*usada para marcar uma propriedade de bean como obrigatória, exigindo que ela seja definida por meio de injeção de dependência, podendo causar uma exceção de configuração se não for configurada.*
- @RequiredArgsConstructor:
>*Cria um construtor com todos os atributos finais da classe automaticamente.*
- @ResponseBody:
>*Transforma um objeto Java retornado pelo controller em uma representação de recurso solicitada por um cliente REST.*
- @ResponseStatus(HttpStatus.OK):
>*Indica que quando a requisição é bem-sucedida, o código de status HTTP retornado deve ser "200 OK".*
- @ResponseStatus(HttpStatus.CREATED):
>*Retorna um status code que indica que algum recurso foi criado na aplicação.*
- @ResponseStatus(HttpStatus.NO_CONTENT):
>*Retorna um status code que indica que a solicitação HTTP foi concluída com êxito e não há corpo de mensagem.*

<br>

## 📜 S

- @Service:
>*Marca uma classe Java como um serviço que executa alguma lógica de negócio.*
- @SequenceGenerator:
>*Usada para especificar a sequência de banco de dados usada pelo gerador de identificadores da entidade atualmente anotada.*
- @Setter:
>*Cria métodos de configuração (setters) para todos os atributos da classe automaticamente usando o Lombok.*
- @Size:
>*Verifica se a quantidade de elementos está entre um tamanho mínimo e máximo especificado, aplicável a tipos como Strings, Collections, Maps e arrays.*
- @Spy:
>*Cria um "espião" de um objeto, permitindo a verificação de interações com o objeto durante testes.*
- @SecurityRequirement(name = "bearer-key"):
>*Especifica um requisito de segurança (como autenticação do tipo Bearer token) para uma operação.*
- @SpringBootTest:
>*Cria o contexto da aplicação Spring para fins de teste, permitindo a injeção de dependências e outras funcionalidades do framework.*
- @SpringBootApplication:
>*Indica que a classe principal é uma aplicação Spring Boot.*

<br>

## 📜 T

- @Table:
>*Especifica o nome da tabela principal associada à entidade anotada atualmente.*
- @Test:
>*Anotação que define um método como um teste.*
- @TestMethodOrder(MethodOrderer.OrderAnnotation.class):
>*Executa os testes em ordem especificada pela anotação @Order().*
- @TestMethodOrder(MethodOrderer.MethodName.class):
>*Executa os testes em ordem alfabética pelo nome do método.*
- @TestMethodOrder(MethodOrderer.Random.class):
>*Executa os testes em ordem aleatória.*
- @TestMethodOrder(MethodOrderer.DisplayName.class):
>*Executa os testes em ordem especificada pela anotação @DisplayName().*
- @Transactional:
>*Utilizada nos métodos que requerem transações, garantindo que as operações sejam executadas atomicamente.*
- @Transient:
>*Indica que um campo não deve ser persistido na base de dados.*

<br>

## 📜 V

- @Valid:
>*Indica que o valor do objeto virá do corpo da requisição e precisa ser validado de acordo com as regras de validação definidas.*
- @Value:
>*Fornece uma maneira de injetar valores de propriedades em componentes.*

<br>

## 📜 W

- @WithMockUser:
>*Permite a execução de testes usando um usuário fictício autenticado.*

<br>

## 👨‍🎓 Autor

#### Lucas Araujo

<a href="https://www.linkedin.com/in/lucarauj"><img alt="lucarauj | LinkdeIN" width="40px" src="https://user-images.githubusercontent.com/43545812/144035037-0f415fc7-9f96-4517-a370-ccc6e78a714b.png" /></a>
