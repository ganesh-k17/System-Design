# HTTP Response Status Codes

* Informational responses (100 – 199)
* Successful responses (200 – 299)
* Redirection messages (300 – 399)
* Client error responses (400 – 499)
* Server error responses (500 – 599)

## Informational responses (100 – 199)

100 - Continue
101 - Switching protocols
102 - Processing
103 - Early Hints

## Successful responses

200 - OK (Success)
201 - Created
202 - Accepted

## Redirection messages (300 – 399)

300 - Multiple Choices
301 - Moved permanently *
302 - Found  (moved temporarily and will be restored shortly)
303 - See other (The server sent this response to direct the client to get the requested resource at another URI ith a GET request)
304 - Not Modified (This is used for caching purposes. It tells the client that the response has not been modified, 
      So the client can continue to use the same cached version of the response)
305 - Use Proxy
307 - Temporary Redirect
308 - Permanent Redirect

## Client error responses: 

* 400 - Bad Request
* 401 - Unauthorized
* 403 - Forbidden
* 404 - Not found
* 405 - Methods not allowed
* 406 - Not acceptable
* 408 - Request time out
* 429 - Too many request
* 409 - Conflict

## Server error responses:

* 500 - internal Server Error
* 501 - Not Implemented
* 502 - Bad Gateway
* 503 - Service Unavailable
* 504 - Gateway timeout
* 505 - Http Version Not supported

