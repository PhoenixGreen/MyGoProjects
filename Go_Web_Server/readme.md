My first attemp at building a web server in Go. This is a very basic setup but should be a very good base to start building future web applications. It includes the basic server functionality - starting a server, caching, middleware and session management.


Includes:

* Two template web pages - home and about
* cmd/web - houses the main server setup and includes the files - main.go, middleware.go, routes.go
* go.mod -  houses all the external modules for this server
* pkg - are my server modules - handlers, config, models, render
* templates - houses my web templates - base, home, about


To run this server - cmd/web/*.go
