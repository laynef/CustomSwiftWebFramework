# Custom Web Framework in Swift

## Client Web Server
This web server handles your client only with helpful tools for high performance.
The web server is only a place to dump files while your API server will handle multithreaded API calls.
This gives your web server the highest speeds and performance with minimal functionality.
Your API server is a different URL handling more functionality for any microservice with the web being a client.

Web Server Functionality
- Minimal data dump (Assets & Text files)
- Minifies before server runs
- Helpful tools for server-side JavaScript rendering for SPAs
- Session support for web browser storage (Cookies & Session Storage)

## API Web Server
This web server is built for your API which has all tools available to it.
The server will handle all your security for the connections it makes to other servers
such as your database, proxies, & admin UI panel
