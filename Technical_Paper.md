# REST Architecture

## Introduction
REST stands for Representational State Transfer. It is a software architectural style that defines the set of rules to be used for creating web services. REST uses HTTP requests to access and manipulate data.

## Architectural Constraints of RESTful API

### Client-Server Architecture
* REST follows a client-server model. 
* The client handles the user interface, and the server manages data storage and processing. 
* This separation allows scalability and independent development of client and server components. 
* Client doesn't need to know anything about business logic and server doesn't need to know anything about frontend UI.

### Statelessness
* The necessary state to handle the request is contained within the request itself and server would not store anything related to the session. 
* There is a drawback when the client need to send too much data to the server so it reduces the scope of network optimization and requires more bandwidth.

### Cacheability
* Responses in REST can be explicitly marked as cacheable or non-cacheable.
* This reduces server load and improves performance.

### Layered System
* REST allows multiple layers, such as proxies and gateways, between client and server.
* Each layer can improve scalability and security.

## HTTP Methods in REST

 **GET**: Retrieve data from the server.
 **POST**: Create a new resource on the server.
 **PUT**: Update an existing resource.
 **DELETE**: Remove a resource from the server.

## Advantages of REST

* Simple to implement and use.
* Works with standard HTTP protocols.
* Scalable for web applications.
* Supports multiple data formats such as JSON, XML, HTML.

## Disadvantages of REST

* Stateless nature can increase the number of requests.
* Security must be handled separately using HTTPS. 

## Conclusion
REST is a widely adopted architecture for web APIs due to its simplicity, scalability, and flexibility.

## References
* REST APIs - [GeeksforGeeks](https://medium.com/@shikha.ritu17/rest-api-architecture-6f1c3c99f0d3)
* Rest API Architecture - [Medium](https://medium.com/@shikha.ritu17/rest-api-architecture-6f1c3c99f0d3)

