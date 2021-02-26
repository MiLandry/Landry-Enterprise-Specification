## The Landry Enterprise Specification



This project is coming out of a glaring need that, despite the efforts of the creators of tools and platforms, I have yet to find a platform that, in my opinion, is a general platform for solving the majority of problems facing businesses, IE, being enterprise ready.

## Principles


* Provide out-of-the-box solutions to common recurring engineering challenges

* Leverage open source libraries whenever possible

* Follow best practices and update the specification as needed to implement the most common standards and practices

* Use interfaces and plugin architecture to facilitate swapping out modules and implementations for special use cases

* Keep things as simple as possible

## A list of specifications that every project must solve to implement the LES



Software Layer

* Authorization, and Authentication
  * Applications shall implement OAuth2 and OpenID Connect for Authorization Authentication

* Navigation and Routing, if applicable
	* Applications shall implement a home screen, the first screen a user encounters after logging in This screen shall provide.
		* Access to settings
		* Dashboard access if applicable
		* access to search tools
		* feed if applicable

* Component library, if applicable
  * The implementation shall be compatible with a solution that is automated, and leverages open source, community created components.

* State Management

* Code Scaffolding

* Support for reading and storing and configuring Environmental variables. See [The Landry Environment Variable Specification (LEVS)](https://github.com/MiLandry/Landry-Enterprise-Specification/blob/main/LEVS/landry-environment-variables-specfification.readme.md)* Out of the box support for good User Interface and experience

* Following the specification for Material Design, an opensource set of guidelines for layouts.* Declarative and automated support for being able to CReate, Update, and Delete business entities (CRUD)

  * Specifically, it should use REST as a protocol, following the [Open Api Specification](https://swagger.io/resources/open-api/) (OAS)

* Declarative approach to forms

  * Specifically, forms should be generated via the specification created from OAS.

* RESTFUL API Client
  * Auto generated

* Search and query functionality

  * No Guidance aside from, at a minimum, searching, sorting, and filtering should be supported

* Workflow Engine support or Finite state machine support

  * No guidance yet, may add later

* Database drivers

* container ready

* No guidance on a specific vendor

* cloud / infra ready

* No guidance on specifics

## Mindful of developmental processes

* In a means that is 'easy'. No special setup and environmental configuration.* Developer setup is completely automated. The developer only needs to run simple scripts to initialize and start the application.* Hot reloading, instant feedback for changes

* Dependency management

* Scripting for initialization running, debugging, and building

* Linting

* Live Reload

* Code revision Using Git, Pull requests

* Testing Library

  * Mocking
