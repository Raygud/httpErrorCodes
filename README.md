# httpStatusCodes
A comprehensive list of http error codes and what they mean.


## Status Code - Short - Meaning

### 1xx

## 100 - Continue.
The HTTP 100 Continue informational status response code indicates that everything so far is OK and that the client should continue                         with the request or ignore it if it is already finished.

## 101 - Switching protocols.
The server understands and is willing to comply with the client’s request, via the Upgrade header field 1, for a change in                                  the application protocol being used on this connection.

## 102 - Processing. 
An interim response used to inform the client that the server has accepted the complete request but has not yet completed it.
This status code SHOULD only be sent when the server has a reasonable expectation that the request will take significant time to                           complete.

## 103 - Early Hints.
The HTTP 103 Early Hints information response status code is primarily intended to be used with the Link header to allow the user                          agent to start preloading resources while the server is still preparing a response.

### 2xx

## 200 - Ok.
The 200 status code is by far the most common returned. It means, simply, that the request was received and understood and is being                         processed.

## 201 - Accepted.
A 201 status code indicates that a request was successful and as a result, a resource has been created (for example a new page).

## 202 - Non-Authoritative Information.
The status code 202 indicates that server has received and understood the request, and that it has been accepted for processing, although it may not be processed immediately.

## 203 - Non-Authoritative Information.
A 203 status code means that the request was received and understood, and that information sent back about the response is from a third party, rather than the original server. This is virtually identical in meaning to a 200 status code.

## 204 - No Content.
The 204 status code means that the request was received and understood, but that there is no need to send any data back.

## 205 - Reset Content.
The 205 status code is a request from the server to the client to reset the document from which the original request was sent. For example, if a user fills out a form, and submits it, a status code of 205 means the server is asking the browser to clear the form.

## 206 - Partial Content.
A status code of 206 is a response to a request for part of a document. This is used by advanced caching tools, when a user agent requests only a small part of a page, and just that section is returned.





Sources(Ordered) : https://developer.mozilla.org/en-US/docs/Web/HTTP/Status/100 - https://www.webfx.com/web-development/glossary/http-status-codes/what-is-a-101-status-code/ - https://www.webfx.com/web-development/glossary/http-status-codes/what-is-a-102-status-code/#:~:text=What%20Is%20a%20102%20Status,take%20significant%20time%20to%20complete. - https://developer.mozilla.org/en-US/docs/Web/HTTP/Status/103 - https://aloneonahill.com/blog/http-status-codes#:~:text=The%20200%20status%20code%20is,understood%20and%20is%20being%20processed.&text=A%20201%20status%20code%20indicates,for%20example%20a%20new%20page).(2xx) -   
