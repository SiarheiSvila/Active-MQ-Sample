# Active MQ sample project for [internal EPAM courses](https://learn.epam.com/detailsPage?id=8b08bddb-f97f-46c0-83bb-734d375ef6ae):

## Installation
### ActiveMQ
This project uses ActiveMQ as a message broker. Install it via official [download link](https://activemq.apache.org/components/classic/download/)

Then use ActiveMQ xml configuration from resources folder.
### Spring Boot
Spring Boot is used as DI container

## Description
Messages are pushed to message broker by Producer and Publisher to queue and topic respectively.
You can invoke them via [JmsController.java](src/main/java/com/epam/activemqdemo/controllers/JmsController.java).
Then QueueListener and TopicListeners consume messages.

Messages can also be pushed via ActiveMQ Web Console (it will be available after ActiveMq startup [documentation page](https://activemq.apache.org/web-console))