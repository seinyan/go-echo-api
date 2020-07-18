# GOLANG BOOT

  GO help
     
      go mod init 

https://github.com/seinyan/go_api.git

go mod init github.com/seinyan/go_api


https://habr.com/ru/post/249449/

    https://github.com/golang-standards/project-layout
    
    .
    ├── cmd                  main applications of the project
    │   └── server           the API server application
    ├── config               configuration files for different environments
    ├── internal             private application and library code
    │   ├── album            album-related features
    │   ├── auth             authentication feature
    │   ├── config           configuration library
    │   ├── entity           entity definitions and domain logic
    │   ├── errors           error types and handling
    │   ├── healthcheck      healthcheck feature
    │   └── test             helpers for testing purpose
    ├── migrations           database migrations
    ├── pkg                  public library code
    │   ├── accesslog        access log middleware
    │   ├── graceful         graceful shutdown of HTTP server
    │   ├── log              structured and context-aware logger
    │   └── pagination       paginated list
    └── testdata             test data scripts
    
    
    
    ├── conf
    │   └── app.conf
    ├── controllers
    │   ├── admin
    │   └── default.go
    ├── main.go
    ├── models
    │   └── models.go
    ├── static
    │   ├── css
    │   ├── ico
    │   ├── img
    │   └── js
    └── views
        ├── admin
        └── index.tpl