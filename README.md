## Assignment in Advanced Systems Integration & Architecture
1. Define Service Oriented Architecture(SOA).
-According to the article that i have read, Service Oriented Architecture (SOA) is a method of a software development that uses software components called services to create business applications.

2. List and discuss the characteristics of SOA.
-Standardized Service Contract: Services adhere to a service-description. A service needs to have some information that defines what the service is about.

Loose Coupling: Services minimize dependencies on each other. So if the service functionality breaks at several points in time, this should not crush the client application or stop it from running.
Service Abstraction: Services wrap the logic they encapsulate from the unknown external world. The service shouldn't show how it performs its functionality.

Service Reusability: Logic is divided into services to maximize re-use.

Service Autonomy: Services must control the logic they encapsulate.

Service Statelessness: Services should stay stateless. This determines that services should not keep data from one state to the other. This would be required to be done from each client application.

Service Discoverability: Services can be discovered (usually in a service registry). We have previously viewed this in the theory of the UDDI, which performs a registry which can contain information about the web service.

Service Composability: It breaks large problems into tiny problems.

Service Interoperability: Services should use standards that provide different supporters to use the service. This is examined so obviously these days that it is frequently dropped as a principle.

3. Define Microservices.
-Microservices architecture is a variant of the service-oriented architecture structural style.  It is an architectural pattern that arranges an application as a collection of loosely coupled, fine-grained services, communicating through lightweight protocols. It is typically used to build individual applications in a way that makes them more agile, scalable, and resilient.
This approach contrasts with monolithic architectures, where the entire application is developed as a single, tightly integrated unit.

4. List and discuss the benefits of using Microservices.
Independence: Every microservice has its own database and business logic, making it a stand-alone entity. Individual development, deployment, and scalability are made possible by this autonomy.

Decentralized Data Management: Since microservices frequently have their own databases, managing data unique to each service is simpler and dependencies are reduced.


Communication via APIs: Microservices exchange information with one another using well defined APIs (Application Programming Interfaces). As a result, they may collaborate without sacrificing their independence.

Scalability: Rather than scaling the entire application, a microservice may be scaled individually based on its unique requirements because each microservice is a different entity.

Technology Diversity: Different microservices within an application can be developed using different programming languages, frameworks, and technologies, as long as they adhere to the agreed-upon APIs.

Resilience: Microservices can enhance system resilience. If one microservice fails, it doesn't necessarily bring down the entire system. Other services may continue to function as long as they are not directly dependent on the failing service.

Continuous Deployment and Integration: Microservices can be deployed independently of each other, allowing for more frequent releases and updates without affecting the entire application.

5. List and discuss the similarities and differences of SOA and Microservices.
Service Oriented Architecture (SOA) and Microservices are both architectural styles that organize software systems as a collection of services. They share similarities in emphasizing loose coupling, service reusability, autonomy, and scalability. However, they differ in scope, with SOA often associated with larger, enterprise-level systems, while Microservices focus on small, fine-grained services. Technologically, Microservices offer more flexibility, using diverse technology stacks and lightweight protocols, while SOA may rely on standardized protocols like SOAP. Data management varies, with Microservices favoring decentralized databases, and SOA potentially sharing a common data model. Development and deployment practices differ, with Microservices emphasizing rapid development and continuous deployment. Organizational impact varies, with Microservices often leading to smaller, cross-functional teams. Resilience and isolation also differ, as Microservices are designed for resilience, while the failure of one SOA service may have broader consequences. The choice between SOA and Microservices depends on project requirements and goals.
