# RESTful Go API
This repo holds the code content for the RESTful GO API live trainging session.

This content will continue to grow as I learn more and get your feedback.

If any section is not 100% clear open an issue. If you see anything that you can fix, create a PR.

## Structure
In order to gradually build up the conent for optimal learning, I have decided to make use of git branches. Each branch name will have the format `<Topic>-01..n`.

Each topic will be in their own folder and will be a complete go project.

At each level of the workshop the branch should be working code. If it is not I will mention it.

## Sections

1. Standard Library net/http
    - [Getting Started](https://github.com/moficodes/restful-go-api/tree/standard-library-net-http-01/api-with-net-http#run-the-example)
    - [Custom Handler Type](https://github.com/moficodes/restful-go-api/tree/standard-library-net-http-02/api-with-net-http#why-a-struct)
    - [JSON Response](https://github.com/moficodes/restful-go-api/tree/standard-library-net-http-03/api-with-net-http#json)
    - [HTTP Verbs](https://github.com/moficodes/restful-go-api/tree/standard-library-net-http-04/api-with-net-http#http-verbs)
    - [Request Body](https://github.com/moficodes/restful-go-api/tree/standard-library-net-http-05/api-with-net-http#rest-routes)
    - [Handler vs HandlerFunc vs *HandlerMethod](https://github.com/moficodes/restful-go-api/tree/standard-library-net-http-06/api-with-net-http#handler-vs-handlerfunc-vs-handlermethod)
    - [Path Parameter](https://github.com/moficodes/restful-go-api/tree/standard-library-net-http-07/api-with-net-http#path-parameter)
  
2. Gorilla Mux
    - [Why Gorilla Mux](https://github.com/moficodes/restful-go-api/tree/gorilla-mux-01/api-with-gorilla-mux)
    - [Path Parameter](https://github.com/moficodes/restful-go-api/tree/gorilla-mux-02/api-with-gorilla-mux)
    - [Query Parameter](https://github.com/moficodes/restful-go-api/tree/gorilla-mux-03/api-with-gorilla-mux)
    - [Match Query](https://github.com/moficodes/restful-go-api/tree/gorilla-mux-04/api-with-gorilla-mux)
    - [Sub Router](https://github.com/moficodes/restful-go-api/tree/gorilla-mux-05/api-with-gorilla-mux)

3. Middleware and Security

    - [Middleware](https://github.com/moficodes/restful-go-api/tree/middleware-security-01/middleware-security)
    - [Chaining Middlewares](https://github.com/moficodes/restful-go-api/tree/middleware-security-02/middleware-security)
    - [Mux Handlers](https://github.com/moficodes/restful-go-api/tree/middleware-security-03/middleware-security)
    - [JWT Auth](https://github.com/moficodes/restful-go-api/tree/middleware-security-04/middleware-security)

4. Project Structure
    - [Common Project Structures for Go application](https://github.com/moficodes/restful-go-api/tree/project-structure-01/project-structure)

5. Testing and Benchmarking
    - [Unit Testing]()
