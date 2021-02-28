## The Landry Enterprise Specification

The Landry Enterprise Specification provides a list of requirements that must be satisfied by any project in order to **implement 90 to 95 percent of business systems use cases.** "Enterprise ready", in this context, does not refer to a platform of ONLY being capable of accomplishing technical feats such as "supporting http protocol" or "implementing specific data layer specifications", but can...

* let end users create, update, and delete entities through a user interface and persist the entities in a remote data store.
* search and retrieve said entities.
* execute workflows

... and implicitely supports all technical requierements to achieve this. In this capacity, "Enterprise ready" also requires minimal friction to the development process.

**Any project that implements the Landry Enterprise Specification trivially supports the three use cases supplied above, and can be copied or reused to support the same three use cases regardless of the business domain**

## Principles

Software engineers, and all IT professionals for that matter, must take the 'big picture' into context when creating software systems, meaning that systems are created to solve real world problems, that solutions to those problems are convented into specifications, and that engineers implement the specification, and that the implementation is tested to ensured that the problem is handled. **Therefore, the only sensible way to reason about a platform designed for building systems is in terms of its capacity for solving business problems and NOT in terms of its technical capacities.** To this end, the Landry Enterprise Specification intentionally omits certain features, such as whether Object Oriented Features are supported, or how it compiles its code.

Instead, the Landry Enterprise Specification justifies its requirements through a business-driven set of principles, meaning that solutions oriented torwards use cases are favored over technical imperatives, and that quality, frugality, and efficiency are first class concerns.

To that end the following principles are presented:


* Solve business problemns instead of technical problems. Therefore, platforms must provide out-of-the-box solutions to common recurring engineering challenges.

* Leverage open source libraries whenever possible

* Follow best practices and update the specification as needed to implement the most common standards and practices

* Use interfaces and plugin architecture to facilitate swapping out modules and implementations for special use cases

* Keep things as simple as possible


## Justifications

The reader may find the following reference implementation as working proof of its capacity :
[React front end](https://github.com/MiLandry/cat-wrangler-react)\
[Node back end](https://github.com/MiLandry/cat-wrangler-api)\

The requirements laid out in the Landry Enterprise Specification are a work in progress. In its current state, these requirements were found to be successful, if not inevitably complete nor the absolutely optimized requirement. As the intention of this document is to support projects in delivering results to stakeholders, it also maintains the following about the requirements.

* A requirement explicitely or implicitely identifies a technical or business problem, and then proposes a specific solution as specific as possible to provide the best solution, but no more specific than that.

* Projects should focus on delivering results to the business over 100% implementation of the Landry Enterprise Specification, meaning that alternative solutions to given problems may be more appropriate for a given timeline.

* Not every project should need to tackle every problem in the Landry Enterprise Specification.

As such, a template is provided that projects can use to track requirement process:

[Template ](https://github.com/MiLandry/Landry-Enterprise-Specification/blob/main/implementationtemplate.md)

## The Landry Enterprise Specification requirements


### Software Layer

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

### Tooling

* Automated setup and build, minimal or no environmental dependencies required.

* Dependency management

* Scripting for initialization running, debugging, and building

* Linting

* Live Reload

* Code revision Using Git, Pull requests

* Testing Library

  * Mocking





## License
MIT

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
