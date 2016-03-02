# Spring Boot / REST / Data JPA seed project

This shows a bare example of how to expose a REST interface to a database through Spring Data JPA. It's a simple 
todo-list with the following calls:

| Method | Route     | Action                     |
|--------|-----------|----------------------------|
| GET    | /todo     | List all stores todo's     |
| GET    | /todo/:id | Gets a specific todo by ID |
| POST   | /todo     | Creates a new todo         |
| PUT    | /todo/:id | Updates a todo             |
| DELETE | /todo/:id | Deletes a todo             |

## Running

To run the example you can either run Application.main from your IDE or build a runnable jar using maven. It uses
the spring boot maven plugin to build a fat jar: just type "mvn clean install" in the root and you should end up
with a runnable jar in the target/ directory.

