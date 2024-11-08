# PRUEBAS-API

# Descripción del proyecto

Es este proyecto trabajaremos con Urban Grocers, una aplicación para la entrega de productos por catálogo y kits preparados.
Imaginemos que "el área de desarrollo ha agregado una nueva función en la API de Urban.Grocers, así que nos compartieron una nueva versión de la API para que la pruebes." Aquí están los requisitos del back-end : https://practicum-content.s3.us-west-1.amazonaws.com/new-markets/qa-sprint-3/QA_3.1.1_Requisitos_para_el_back-end_de_Urban.grocers.pdf

# Funcionalidades

Estas son las nuevas funcionalidades: 

* Trabajar con los kits: la capacidad de agregar comestibles a un kit. El endpoint es POST /api/v1/kits/{id}/products. El endpoint devolverá 400 Bad Request (Solicitud no válida) cuando la longitud de la lista de productos resultante (no las cantidades acumuladas de cada producto) sea superior a 30.
* Trabajar con los servicios de entrega: la capacidad de comprobar si el servicio de entrega Order and Go está disponible y cuánto cuesta. El endpoint es POST /order-and-go/v1/delivery.

# Tecnologias usadas

* POSTMAN
* Google sheets
* JIRA

# Conclusiones

Las API son los conectores que permiten que los sistemas de software se comuniquen e intercambien datos, por lo que para garantizar una experiencia de usuario placentera y exitosa con su aplicación de software, es importante probarla minuciosamente antes de ser lanzada al público
