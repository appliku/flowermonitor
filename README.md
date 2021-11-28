Celery Flower monitoring and administration tool

## Usage:
 - Create an application from this repo
 - Add environment variable BROKER_URL pointing to RabbitMQ or Redis instance
 - Add environment variable RESULT_BACKEND pointing to Redis instance
 - Add environment variable FLOWER_BASIC_AUTH in format USERNAME:PASSWORD. This will be used to authenticate Celery Flower web interface

