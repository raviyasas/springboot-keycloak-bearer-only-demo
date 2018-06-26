This is a simple demo that describes how to use Keycloak with Spring Boot in REST web applications.

The access type of the client called "app1" is bearer-only.
You have to pass the access token with the request to access the API.
http://localhost:8080/auth/realms/api/protocol/openid-connect/token
You have to provide client_id, username, password, grant_type and client_secret to call above API

Once you receive the token you can use it in Authorization header.
