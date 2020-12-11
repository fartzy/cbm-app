# kafka-cbm-poc

This application routes messages to a consumer based on rules. The rules are contained within the yaml configuration file.  The producer of the messages is the load generator service. The load generator service creates a configurable amount of messages, in a configurable format. 

## Business Tier service

The yaml is read into the business tier service and the rules are applied to the proper messages.  The consumer and producer API is used to implement the service

## Kafka consumer 
