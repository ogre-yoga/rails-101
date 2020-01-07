# rails-101: Notes on Ruby on Rails

Rails is a Model-View-Controller(MVC) framework built on Ruby.

## *The Rails Way*

* *Convention over configuration (CoC)*: only unconventional aspects of application need to be specified. Rails is opinionated and how it expresses those opinions can be abstract. Beginning Rails means trusting the "magic" of how things are done.
* *Don't Repeat Yourself (DRY)*: 
* *Fat models, skinny controllers:* business logic should exist in the models, controllers should be light as possible.

## Terminology

### Routes

The application endpoints (URIs) that respond to client requests using HTTP methods (Get, Post).

Aside: A Uniform Resource Location (URL) is technically a type of Uniform Resource Identifier (URI). The Web Hypertext Application Technology Working Group (WHATWG) prefers the use of URL over URI. 

### Controller

The "CEO" of the application, directing requests. 

### Model

The "accountant" of the application who does the hard work knowing their keeping operations in order.

### View

The "marketing agent" of the application who presents data back to user.
