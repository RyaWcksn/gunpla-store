


# Gunpla Store

An E-Commerce for _Gunpla_ lovers to buy and sell their Gunplas

## Reason to build this project

I want to learn and try _Event Driven Architecture_ microservice for keep up to date with startups needs

## Stack

Currently i'm going to use `GO` as main language, with `MongoDB` as database, `Apache Kafka` for message broker, `Docker` for containerization, `Docker Compose` for container orchestration tool (i was thinking to use `Kubernete` or `K3s` for the orchestration tool), `Datadog` for distributed tracing tool

**Summary**

- `GO`
- `MongoDB`
- `Apache Kafka`
- `Docker`
- `Docker Compose`
- `Datadog`

**Footnote**

At first i was thinking about using ELK (ElasticSearch, Logstash, Kibana) stack for the architecture, but i drop the idea

## Services

- User

User service for authorization and user details such as address, name, etc. And for seperate if the user is Customer or Seller

- Inventory

This service would be responsible for managing the inventory of products in the system. It would maintain information about available stock levels, pricing, and product details

- Product

Product service would handle the management of product information, including descriptions, images, and specifications. It would be responsible for updating the product catalog and making sure that product information is up-to-date and accurate

- Order

This service would be responsible for managing the order process, including accepting and processing orders, tracking order status, and handling payment processing


## Diagrams

*TO BE ANNOUNCE*

## Database

*TO BE ANNOUNCE*
