# Http - Hypertext Transfer Protocol
- It send request & receive response
- Http works based on request /response pairs
- Stateless protocol [no request needed (to connect with another)]
- Client-server protocol
### Protocol
- System of rules
### Hypertext
- Text display on screen
#### Methods (commonly used)
- **GET**
- **PUT**
- **POST**
- **DELETE**
- **PATCH**	
- **HEAD**
### Http headers
- Type of client request,
	configuration,
	cookies etc.
## HTTP/2
- Developing for performance	[fast & secure]
- Multiple file at same time	[multiplex + server push]
## Terminology
##### *Browser* 
-  Access and navigate between HTML documents
##### *UserAgent* 
- Agent of user, typically a browser [eg : google]
##### *TCP* 
- (Transmission Control Protocol) 
##### *IP* 
- (Internet Protocol) Transfer data between computers over a network 
##### *URL* 
- (Uniform Resource Locator) Address pointing at resource on web
##### *DNS* 
- (Domain Name Server) Point to IP address of servers
##### *Resource* 
- File available on a server following URL 
##### *Server* 
- Internet running some form of data storage and sharing application
##### *Proxy* 
- Software or Hardware service acting as middle person between client and server
## Request - Response Pairs
* client --->(communicate HTTP)--->Server
- [request -sent , response -returned]
## Header
* Both Request, response -> uses HTTP header to pass information back and forth
* Every HTTP contains method, what action sender wants to perform on resource
## Status Response Code
- Numerical code in 100 to 500 range describing what type of response the server sent back to client
## Cache
- Method for storing data on client /server to speed up
## Cookie
- String of data passed back and forth between client and server to create a stateful session
## Default Port
- HTTP - 80
- HTTPS - 443
- Specified = localhost:8080
- eg:	https : ....../......./....../?something
	- https: ->protocol declaration
	- ?something ->url query
## Get the specified resource if available	
* GET
-	Success								
	- 200	
- Fail
  - 404 not found
  - 405 not allowed
  - 403 Forbidden 
## Create a new resource 
* POST
- Success			
  - 201 created	
- Fail 
  - 401 unauthorized
  - 409 conflict
  - 404 not found
## Update an existing resource
* PUT
-	Success								
	- 200 	ok
- Fail
	- 204 no content
   - 404 not found
   - 405 method not allowed
## Modify an existing resource
* PATCH (same as PUT status)
-	Success							
	- 200 				
- Fail
  - 204 no content
  - 404 not found
  - 405 method not allowed
## Delete a  resource 
* DELETE
- Success	 
  - 200 	
- Fail 
  - 401 unauthorized
  - 405 method not allowed
  - 404 not found
## Response header from  resource 
* HEAD
-	Success								
	- 200
-	Fail
	- 404 not found	
## Hint for  some status
	1xx = Information
	2xx = Success
	3xx = Redirection
	4xx = client error
	5xx = server error
### Category of status
* 2 ---> 200 k | 201 created | 204 No content	
* 3 ---> 301 moved permanently | 302/303 found at this other URI  | 307 temporary redirect | 308 permanent redirect
* 4 ---> 400 Bad request | 401 unauthorized | 403 forbidden | 404 not found | 405 method not allowed
* 5 ---> 500 Internal server error | 502 Bad gateway | 503 service unavailable

## For practice 
- use postman app
