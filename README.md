# RETSgo
## A minimalistic REST-api framework to quickly build a scalable and maintainable api using [google's go](https://golang.org/)

*I always create more or less the same structure for every api that I made in golang. I got tired, so here is a helper.*

Current Version: 1.0.0

# Features
+ ORM (github.com/jinzhu/gorm)
+ Default middlewares (logging and error handling)
+ Middleware Chaining (github.com/justinas/alice)
+ Mux (github.com/gorilla/mux)
+ Compile-Time Dependency Injection (github.com/google/wire)
+ Scalable configurations for development, testing and production
+ JWT (Coming Soon)


# QuickStart
## Prerequisites :
- Make sure you have go, and the standard packages installed in your system. For guidance, head to [golang guide](https://golang.org/)
- Configure $GOPATH in your system. Try running `echo $GOPATH` (unix) in your terminal  
  It should print out something like /path/to/the/goworkspace

## Quick Start :
Get retsgo package  
`go get github.com/fernandochristyanto/retsgo`

Run `retsgo -v`  
it should print out the version number (if it does not, try restarting your terminal)

Create a new directory to hold your project, e.g:   
`mkdir -p $GOPATH/src/github.com/mygithubusername/newproject`

Generate a new project  
`retsgo newproject github.com/mygithubusername/newproject`