Basic authentication works as follows:
If a request requires authentication, the server returns 401 (Unauthorized). The response includes a WWW-Authenticate header, indicating the server supports Basic authentication.
The client sends another request, with the client credentials in the Authorization header.

With Basic Authentication, you pass your credentials (your Apigee account's email address and password) in each request to the Edge API. Basic Authentication is the least secure of the supported authentication mechanisms. Your credentials are not encrypted or hashed; they are Base64-encoded only.
