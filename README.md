# httpStatusCodes
A comprehensive list of http error codes and what they mean.


## Status Code - Short - Meaning

### 1xx
1. 100 - Continue - The HTTP 100 Continue informational status response code indicates that everything so far is OK and that the client should continue                         with the request or ignore it if it is already finished.

2. 101 - Switching protocols - The server understands and is willing to comply with the client’s request, via the Upgrade header field 1, for a change in                                  the application protocol being used on this connection.

4. 102 - Processing - An interim response used to inform the client that the server has accepted the complete request but has not yet completed it.
                      This status code SHOULD only be sent when the server has a reasonable expectation that the request will take significant time to                           complete.

5. 103 - Early Hints - The HTTP 103 Early Hints information response status code is primarily intended to be used with the Link header to allow the user                          agent to start preloading resources while the server is still preparing a response.

### 2xx

1. 200 - Ok - The 200 status code is by far the most common returned. It means, simply, that the request was received and understood and is being                         processed.

2. 201

3. 202

4. 203

5. 204

6. 205

7. 206



Sources(Ordered) : https://developer.mozilla.org/en-US/docs/Web/HTTP/Status/100 - https://www.webfx.com/web-development/glossary/http-status-codes/what-is-a-101-status-code/ - https://www.webfx.com/web-development/glossary/http-status-codes/what-is-a-102-status-code/#:~:text=What%20Is%20a%20102%20Status,take%20significant%20time%20to%20complete. - https://developer.mozilla.org/en-US/docs/Web/HTTP/Status/103 - https://aloneonahill.com/blog/http-status-codes#:~:text=The%20200%20status%20code%20is,understood%20and%20is%20being%20processed.&text=A%20201%20status%20code%20indicates,for%20example%20a%20new%20page). -  
