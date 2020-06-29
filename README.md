# Prova Agibank

  Esse projeto ilustra a resoluçao proposta conforme a descriçao do problema, seguindo os criterios de avaliaçao:

```shell
Você deve criar um sistema de análise de dados, onde o sistema deve importar
lotes de arquivos, ler e analisar os dados e produzir um relatório.

O conteúdo do arquivo de saída deve resumir os seguintes dados:
● Quantidade de clientes no arquivo de entrada
● Quantidade de vendedor no arquivo de entrada
● ID da venda mais cara
● O pior vendedor
O sistema deve estar funcionando o tempo todo.
Todos os arquivos novos estar disponível, tudo deve ser executado
```
  

```shell
Critérios de Avaliação
● Clean Code
● Simplicity
● Logic
● SOC (Separation of Concerns)
● Flexibility/Extensibility
● Scalability/Performance
```

# Mavenquickstart

Esse projeto ilustra a estrutura gerada através da utilização do arquétipo Quickstart do Maven utilizando o JDK14.

### Getting started

Para executar o projeto, será necessário instalar os seguintes programas:

- [JDK 14: Necessário para executar o projeto Java](https://www.oracle.com/java/technologies/javase-jdk14-downloads.html) 
- [Maven 3.6.3: Necessário para realizar o build do projeto Java](http://mirror.nbtelecom.com.br/apache/maven/maven-3/3.6.3/source/apache-maven-3.6.3-src.zip) 
- [Eclipse 2020-03: Para desenvolvimento do projeto](https://www.eclipse.org/downloads/packages/release/2020-03/m3) 




### Desenvolvimento

Para iniciar o desenvolvimento, é necessário descompactar o projeto em um diretório de sua preferência

```shell
cd "diretorio de sua preferencia"
descompactar arquivo
```


### Construção (Build)

Para construir o projeto com o Maven, executar os comando abaixo:

```shell
{diretorio_maven_3.6.3}\mvn -f {diretorio_projeto} clean install
```

O comando irá baixar todas as dependências do projeto e criar um diretório target com os artefatos construídos, que incluem o arquivo jar do projeto. <p>
Além disso, serão executados os testes unitários, e se algum falhar, o Maven exibirá essa informação no console.


## Configuração

Para executar o projeto, é necessário utilizar o Eclipse, para que o mesmo identifique as dependências necessárias <p>
para a execução no repositório .m2 do Maven. Uma vez importado o projeto, será criado um arquivo *.classpath* que irá informar qual a classe principal para a execução.
<p>
Ao gerar os artefatos, tambem podera rodar o projeto das seguintes formas:

```shell
{diretorio_jdk_14}\java -jar --enable-preview {diretorio_prova}\prova-agibank-0.0.1-SNAPSHOT.jar
ou
{diretorio_maven_3.6.3}\mvn -f {diretorio_projeto} clean package spring-boot:run
```


## Testes

Para rodar os testes, utilize o comando abaixo:

```
{diretorio_maven_3.6.3}\mvn -f {diretorio_projeto} test
```

### Reference Documentation
For further reference, please consider the following sections:

* [Official Apache Maven documentation](https://maven.apache.org/guides/index.html)
* [Spring Boot Maven Plugin Reference Guide](https://docs.spring.io/spring-boot/docs/2.3.1.RELEASE/maven-plugin/reference/html/)
* [Create an OCI image](https://docs.spring.io/spring-boot/docs/2.3.1.RELEASE/maven-plugin/reference/html/#build-image)
* [Spring Boot DevTools](https://docs.spring.io/spring-boot/docs/2.3.1.RELEASE/reference/htmlsingle/#using-boot-devtools)

