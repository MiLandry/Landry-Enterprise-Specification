

## The Landry Enterprise Specification





This project is coming out of a glaring need that, despite the efforts of the creators of tools and platforms, I have yet to find a platform that, in my opinion, is a general platform for solving the majority of problems facing businesses, IE, being enterprise ready.## Principles




* Provide out-of-the-box solutions to common recurring engineering challenges



* Leverage open source libraries whenever possible



* Follow best practices and update the specification as needed to implement the most common standards and practices



* Use interfaces and plugin architecture to facilitate swapping out modules and implementations for special use cases



* Keep things as simple as possible



## A list of specifications that every project must solve to implement the LES





Software Layer



* Authorization, and Authentication



* Following the OAuth Specification



* Navigation and Routing, if applicable
	* Applications shall implement a home screen, the first screen a user encounters after logging in This screen shall provide.
		* Access to settings
		* Dashboard access if applicable
		* access to search tools
		* feed if applicable



* No specific guidance



* Support for reading and storing and configuring Environmental variables. See [The Landry Environment Variable Specification (LEVS)](https://github.com/MiLandry/Landry-Enterprise-Specification/blob/main/LEVS/landry-environment-variables-specfification.readme.md)* Out of the box support for good User Interface and experience



* Following the specification for Material Design, an opensource set of guidelines for layouts.* Declarative and automated support for being able to CReate, Update, and Delete business entities (CRUD)* Specifically, it should use REST as a protocol, following the [Open Api Specification](https://swagger.io/resources/open-api/) (OAS)* Declarative approach to forms



* Specifically, forms should be generated via the specification created from OAS.* Search and query functionality



* No Guidance aside from, at a minimum, searching, sorting, and filtering should be supported



* Workflow Engine support or Finite state machine support



* No guidance yet, may add later



* container ready



* No guidance on a specific vendor



* cloud / infra ready



* No guidance on specifics




## Mindful of developmental processes



* In a means that is 'easy'. No special setup and environmental configuration.* Developer setup is completely automated. The developer only needs to run simple scripts to initialize and start the application.* Hot reloading, instant feedback for changes



* Dependency management



* Scripting for initialization and running




todo turn this into a website



<!--****** To avoid retyping too much info. Do a search and replace for the following:*** github_username, repo_name, twitter_handle, email, project_title, project_description



--><!-- PROJECT SHIELDS --><!--*** I'm using markdown "reference style" links for readability.*** Reference links are enclosed in brackets [ ] instead of parentheses ( ).*** See the bottom of this document for the declaration of the reference variables



*** for contributors-url, forks-url, etc. This is an optional, concise syntax you may use.*** https://www.markdownguide.org/basic-syntax/#reference-style-links



--><!-- [![Contributors][contributors-shield]][contributors-url][![Forks][forks-shield]][forks-url][![Stargazers][stars-shield]][stars-url][![Issues][issues-shield]][issues-url][![MIT License][license-shield]][license-url][![LinkedIn][linkedin-shield]][linkedin-url] --><!-- PROJECT LOGO --><!-- <br /><p align="center"><a href="https://github.com/github_username/repo_name"><img src="images/logo.png" alt="Logo" width="80" height="80"></a><h3 align="center">project_title</h3><p align="center">



project_description



<br  /><a  href="https://github.com/github_username/repo_name"><strong>Explore the docs »</strong></a><br  /><br  /><a  href="https://github.com/github_username/repo_name">View Demo</a>



·



<a  href="https://github.com/github_username/repo_name/issues">Report Bug</a>



·



<a  href="https://github.com/github_username/repo_name/issues">Request Feature</a></p></p>-->

<!-- TABLE OF CONTENTS --><!-- <details open="open"><summary><h2 style="display: inline-block">Table of Contents</h2></summary><ol><li><a href="#about-the-project">About The Project</a><ul><li><a href="#built-with">Built With</a></li></ul></li><li><a href="#getting-started">Getting Started</a><ul><li><a href="#prerequisites">Prerequisites</a></li><li><a href="#installation">Installation</a></li></ul></li><li><a href="#usage">Usage</a></li><li><a href="#roadmap">Roadmap</a></li><li><a href="#contributing">Contributing</a></li><li><a href="#license">License</a></li><li><a href="#contact">Contact</a></li><li><a href="#acknowledgements">Acknowledgements</a></li></ol></details> --><!-- ABOUT THE PROJECT --><!-- ## About The Project



[![Product Name Screen Shot][product-screenshot]](https://example.com)



Here's a blank template to get started:**To avoid retyping too much info. Do a search and replace with your text editor for the following:**`github_username`, `repo_name`, `twitter_handle`, `email`, `project_title`, `project_description`

### Built With



*  []()* []()* []()<!-- GETTING STARTED -->## Getting Started





To get a local copy up and running follow these simple steps.### Prerequisites





This is an example of how to list things you need to use the software and how to install them.* npm



```sh





npm install npm@latest -g



```### Installation





1. Clone the repo



```sh





git clone https://github.com/github_username/repo_name.git



```



2. Install NPM packages



```sh





npm install



```<!-- USAGE EXAMPLES -->## Usage





Use this space to show useful examples of how a project can be used. Additional screenshots, code examples and demos work well in this space. You may also link to more resources.



_For more examples, please refer to the [Documentation](https://example.com)_



--><!-- ROADMAP --><!-- ## Roadmap





See the [open issues](https://github.com/github_username/repo_name/issues) for a list of proposed features (and known issues). --><!-- CONTRIBUTING --><!-- ## Contributing





Contributions are what make the open source community such an amazing place to be learn, inspire, and create. Any contributions you make are **greatly appreciated**.



1. Fork the Project





2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)



3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)



4. Push to the Branch (`git push origin feature/AmazingFeature`)



5. Open a Pull Request



--><!-- LICENSE --><!-- ## License





Distributed under the MIT License. See `LICENSE` for more information.--><!-- CONTACT --><!-- ## Contact





Your Name - [@twitter_handle](https://twitter.com/twitter_handle) - email





Project Link: [https://github.com/github_username/repo_name](https://github.com/github_username/repo_name)-->

<!-- ACKNOWLEDGEMENTS --><!-- ## Acknowledgements



* []()* []()* []() --><!-- MARKDOWN LINKS & IMAGES --><!-- https://www.markdownguide.org/basic-syntax/#reference-style-links --><!-- [contributors-shield]: https://img.shields.io/github/contributors/github_username/repo.svg?style=for-the-badge



[contributors-url]: https://github.com/github_username/repo/graphs/contributors



[forks-shield]: https://img.shields.io/github/forks/github_username/repo.svg?style=for-the-badge



[forks-url]: https://github.com/github_username/repo/network/members



[stars-shield]: https://img.shields.io/github/stars/github_username/repo.svg?style=for-the-badge



[stars-url]: https://github.com/github_username/repo/stargazers



[issues-shield]: https://img.shields.io/github/issues/github_username/repo.svg?style=for-the-badge



[issues-url]: https://github.com/github_username/repo/issues



[license-shield]: https://img.shields.io/github/license/github_username/repo.svg?style=for-the-badge



[license-url]: https://github.com/github_username/repo/blob/master/LICENSE.txt



[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555



[linkedin-url]: https://linkedin.com/in/github_username -->