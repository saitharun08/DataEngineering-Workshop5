# Planning API using Swagger


## Overview
Welcome to the second section "Planning API using Swagger"! In this module, we will delve into the crucial aspect of planning your API using Swagger. 

## Why Plan Your API?
A well-organized API design is the foundation for seamless development and effective communication between teams. A well-thought-out API design ensures consistency, scalability, and ease of maintenance throughout the development process.

## An API Specification
An API (Application Programming Interface) specification is a document that outlines the details of how software components should interact with each other. It serves as a contract or agreement between different software systems, defining the rules and requirements for communication.

In the context of Swagger and many modern web APIs, the API specification is often written using the OpenAPI Specification (formerly known as Swagger Specification). The OpenAPI Specification is a standardized format for describing RESTful APIs. It provides a clear and machine-readable way to define the structure of an API, including:

- **Endpoints:** Describes the different URLs (endpoints) exposed by the API, indicating the available resources.
- **Operations/Methods:** Specifies the HTTP methods (GET, POST, PUT, DELETE, etc.) supported by each endpoint, indicating the actions that can be performed.
- **Request and Response Formats:** Defines the structure of the data that should be sent in requests and the expected format of the data in responses.
- **Parameters:** Lists any parameters that can be included in the API requests, such as query parameters, path parameters, or request headers.
- **Authentication:** Specifies the authentication methods supported by the API, if any, and how to include authentication details in requests.
- **Error Handling:** Describes how errors are communicated back to the client, including status codes and error message formats.
- **Documentation:** Provides additional information and descriptions to help developers understand how to use the API effectively.

## API Specification in Swagger
Now let us start working on the Design of the API Specification using Swagger, to cretae the design the we need to use **OpenAPI Specification** (formerly Swagger Specification) which is an API description format for REST APIs and the specification is typically written in YAML or JSON format. We are going to write in YAML.

Throughout this section, we can use the online [`Swagger Editor`](https://editor.swagger.io/) to edit the YAML of the API.


**Metadata**

```yaml
openapi: 3.0.0
```
- Every API definition must include the version of the OpenAPI Specification that this definition is based on
- The OpenAPI version defines the overall structure of an API definition – what you can document and how you document it
- The available versions are 3.0.0, 3.0.1, 3.0.2, and 3.0.3

```yaml
info:
  title: Articales V2
  description: Multiple APIs to get the artical records form the database.
  version: '0.0.1'
```
- The info section contains API information: title, description (optional), version
- title: is your API name.
- description: is extended information about your API
- version: is an arbitrary string that specifies the version of your API

  




