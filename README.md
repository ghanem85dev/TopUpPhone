# TopUpPhone

This is a sample template to create a DDD Clean Architecture CQRS Microservice application. 
I m using : 

LAYERS 
- Presentation : Api and Contracts
- Application : Orchestrate the business logic
- Domain : Define the Aggregate, entities and ValueObject; Drive and Imlement the business logic
- Infrastructure : DB, Migration, Repositories, External services Interfaces, Logging and Exceptions

DESIGN PATTERNS & TECHNICS
- Mediator : MediaR library 
- CQRS Pattern
- Adapter: Mapster (we could use Automapper)
- Dependecy injection
- Factory
- MVC
- Code First EF Core
- Singleton
- Decorator
- FluentValidation
- Swagger
- TDD
- Fluent Assertion and Xunit 
- ErrorOr
- ..
