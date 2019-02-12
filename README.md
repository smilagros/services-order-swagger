# Swagger JSON
This is a swagger JSON built by the [swagger-codegen](https://github.com/swagger-api/swagger-codegen) project.# services-order-swagger

La integracion ha sido realizada

katideas-service-order-api-1.0-swagger.yaml
15 KB
katideas-service-order-api-1.0-...tty=true
20 KB
Para la integración se utilizo como documentacion

https://swagger.io/blog/api-development/go-serverless-with-swaggerhub-and-amazon/

Problemas

Se tuvo problemas con la integración debido a que Swagger trabaja con la version 4.3 y para realizar la integración con API Gateway se requiere la version 8.10

En el test se realizo la integración con Python 3.7

Se trato de cambiar el runtime en la funciones Lambda a Node 8.10 ,se obtuvo errores de compilación,No se realizo mas modificaciones.
