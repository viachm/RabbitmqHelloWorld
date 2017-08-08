# Hello world on RabbitMQ

## Run

### Via Intellij Idea

As we have Maven here, you can run it as usual java app with main method - right click on the class;

### Via command line.

There are appropriate *.jar files in downloaded.

#### Compile

```$xslt
javac -cp amqp-client-4.0.2.jar Send.java Recv.java
```

#### Run receiver

```$xslt
java -cp .;amqp-client-4.0.2.jar;slf4j-api-1.7.21.jar;slf4j-simple-1.7.22.jar Recv
``` 
 
#### Run sender
 
```$xslt
java -cp .;amqp-client-4.0.2.jar;slf4j-api-1.7.21.jar;slf4j-simple-1.7.22.jar Send
```
