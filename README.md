<p align="center">
    <a href="https://gemini.at7.it" target="_blank"><img src="./gemini_logo.png" height="130" alt="Gemini Logo"></a>
    <br />
    <br />
    <b>A Model Driven Framework to automatically expose CRUD REST APIs and that manages everything else</b>
    <br />
    <br />
</p>

![License](https://img.shields.io/github/license/h4t0n/gemini.svg)
[![Build Status](https://travis-ci.org/gemini-projects/gemini.svg?branch=master)](https://travis-ci.org/gemini-projects/gemini)
[![Twitter](https://img.shields.io/badge/Twitter-@h4t0n-blue.svg?style=flat)](http://twitter.com/h4t0n)
[![Gitter](https://img.shields.io/gitter/room/gemini-framework/general)](https://gitter.im/gemini-framework/general)
![Last Commit](https://img.shields.io/github/last-commit/h4t0n/gemini.svg)
![Version](https://img.shields.io/github/release/h4t0n/gemini)
___

Gemini is a backend REST framework to automatically create CRUD REST APIs from scratch starting from a simple Schema
 definition called Gemini DSL. Briefly Gemini automatically handles for you:
* **Data Storage**: creating all persistence stuff (tables, relations and so on)
* **API controllers**: creating common REST CRUD controllers for each DSL Entity
* **Swagger API documentation**: creating the openapi language-agnostic interface to RESTful APIs 
* **Authentication**: by using Spring OAuth2 and JWT tokens
* **API callbacks**: to add business logic with ease

<p align="center">
   <img src="./gemini_hiw.gif" height="400">
</p>


## Quick Start & Documentation
To use Gemini take a look at the [documentation](https://gemini.at7.it).

You can use Docker to start in minutes.

## Contribute
Gemini is in early stage of development. The best way to contribute is to checkout the project and try it. Then we can
speak about new features, improvements and roadmap on gitter or social platforms.

## License
Apache License 2.0
