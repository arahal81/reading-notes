# Reading 13

1. In your own words, describe what each group of status code represents:
    * 100’s = the request has been recieved from the client and waiting the server to comply
    * 200’s = Standard response for successful HTTP requests.
    * 300’s = redirection , which means that the request that have been srnt to the server is invalid.
    * 400’s = client error , invalid request.
    * 500’s = server errors.
2. What is a status code 202?
    * 202 Accepted is used for asynchronous processing. This code tells the client that the request was valid, The request might or might not be eventually acted upon, and may be disallowed when processing occurs
3. What is a status code 308?
    * Permanent Redirect, this tells the client to use another URL to access the resource and not use the current URL anymore.
4. What code would you use if an update didn’t return data to a client?
    * 204 No Content
5. What code would you use if a resource used to exist but no longer does?
    * 410 Gone
6. What is the ‘Forbidden’ status code?
    * 403 Forbidden.
