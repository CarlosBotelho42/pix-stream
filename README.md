## Sobre o projeto

pix-produtor é um projeto para fins de aprendizado relacionado ao apache kafka.

---

## Funcionalidades

- [x] Envio de solitação de um pix para o broker;
- [x] Validar Pix;
- [x] Cadastrar chaves Pix;
- [x] Validar chaves Pix;


---

## Layout

O projeto desse repositório é apenas a API Backend.

---

## Tecnologias

As seguintes tecnologias foram utilizadas no desenvolvimento do projeto:

- **[Java 17](https://www.oracle.com/java)**
- **[Spring Kafka 3](https://spring.io/projects/spring-boot)**
- **[Maven](https://maven.apache.org)**



## Alterações

- [x] Integrar o Spring com o Kafka, utilizando bibliotecas específicas que facilitam a integração do Kafka com uma aplicação Spring, de acordo com seus padrões de inversão de controle e injeção de dependência.;

## Lições

- No processamento stream os dados são processados à medida que estão chegando, como na visualização de vídeos na internet, por meio de streamings e na análise de logs. Esse tipo de processamento pode gerar informações importantes em tempo real e pode ser empregado em diversos tipos de aplicações, como na detecção de fraudes em tempo real, na avaliação e aprovação de crédito e no streaming de mídias como áudio e vídeo.
- Com o Kafka Stream é possível realizar operações como agrupamento e soma de valores, sem a necessidade de processar dados históricos, agregando os valores conforme os pagamentos vão chegando. Para cada uma dessas operações o Kafka disponibiliza métodos, como o filter para filtrar os dados, o groupBy para agrupamento e o map para a transformação dos dados.
-  Fazer agregações com o Kafka Streams, que podem ser utilizadas para realizar cálculos em um conjunto de dados em tempo real. Por exemplo, na aplicação do PIX, podemos usar a agregação para somar todos os valores transferidos por uma chave específica, ou agrupar todas as transações feitas na última hora. Para isso, os métodos principais são o groupBy, que pode agrupar os dados por uma chave, e o aggregate, que executa uma função de agregação como soma, média e maior ou menor valor.