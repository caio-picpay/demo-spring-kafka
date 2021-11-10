### Subindo o Kafka localmente
Além de subir, este tutorial ensina a ter um Producer e um Consumer no terminal:
https://kafka.apache.org/quickstart

### Kafka + Spring Boot
Este repositório contém todo código necessário para consumir e produzir mensagens em um tópico Kafka.

Com a aplicação rodando, use esta chamada para ver tudo conectado e funcionando: curl -X POST -F 'message=stuart-little' http://localhost:9000/kafka/publish