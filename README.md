# rabbitcon

A Python program that collectes the amount of consumers available for RabbitMQ Queues.

You can run this program without any argument to get all available consumers for all the queues or set the name of a
specific queue to get only its consumers. That's it :)

## Configuration

The following environment variables are required:

- export RABBITMQ_USER=
- export RABBITMQ_PWD=
- export RABBITMQ_URL=
- export RABBITMQ_PORT=

## Requirements

These Python libraries are required:

 - os
 - subprocess
 - json
 - time
 - sys
 
 ## Usage 
 
 rabbitcon or rabbitcon name-of-the-queue
 
 For more details: rabbitcon --help
