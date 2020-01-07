# rails-101
## Notes on Ruby on Rails

Rails is a Model-View-Controller(MVC) framework built on Ruby.

## The Rails Way

* *Convention over configuration (CoC)*: only unconventional aspects of application need to be specified. Rails is opinionated and abstract. Beginning Rails means trusting the "magic" of how things are done.
* *Don't Repeat Yourself (DRY)*: 
* *Fat models, skinny controllers:* business logic should exist in the models, controllers should be light as possible

## Terminology

### Routes

The application endpoints (URIs) that respond to client requests using HTTP methods (Get, Post).

Note: A Uniform Resource Location (URL) is simply a type of Uniform Resource Identifier (URI)

### Controller

The "CEO" of the application, directing requests

### Model

The "accountant" of the application who does the hard work keeping operations in order

### View

The "marketing agent" of the application who presents data back to user
