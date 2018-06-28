# Technical Test Fullstack Developer

## Objetivo 
La prueba consistirá en crear un simple aplicación web de notas, la prueba se dividirá en 2 funcionalidades basicas y 3 funcionalidades adicionales (opcionales) 

## Instrucciones

Algunas instrucciones a tener en cuenta:

- Elegir el lenguaje y el framework de su preferencia tanto para back como para front.
- Elegir la BD de su preferencia 
- Elegir los servicios adicionales de su preferencia.
- Tienes libre disponiblidad de usar otros recursos en internet.
- **Tiempo máximo:** 2 horas

## 1. Funcionalidades basicas

**Usuario y Autenticación**

Crear API en REST donde me permita autenticarme por POST desde una interfaz web

**Notas**

Back:
Se desea crear endpoints para poder administrar **notas** (crear y listar como mínimo) usar una BD para almacenar dichos datos.

**Nota:** Los campos usados en la BD son irrelevantes y son propuestos por el evaluado, ejemplo: Descripción, titulo, tags, etc.

Front: 
Se desea una interfaz web donde consuman estos endpoints de listar y crear una nota


## 2. Funcionalidades adicionales

Las siguientes funcionalidades se construirán sobre la funcionalidad base.

**Serialización y validación**

Se desea validar los datos que se reciben via POST y mostrar los errores al usuario que usa el API, serializar la lista de objetos para enviarlas como json (los criterios de validacion son propuestos por el evaluado)


**Autorización**

Se desea asociar una **nota** con un **usuario**, de tal manera que cada usuario solo pueda ver sus propias notas.

**JWT**

Se desea que el usuario se autentifique mediante json web tokens.