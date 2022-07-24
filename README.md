# oauth

## What is OAuth.2
OAuth 2.0 is an authorization protocol and NOT an authentication protocol. As such, it is designed primarily as a means of granting access to a set of resources, for example, remote APIs or user’s data.

## The essential components of an OAuth 2.0 system.
Resource: What is need to be accessed.
Resource Owner: The user or system that owns the protected resources and can grant access to them.
An Entity capable of granting access to protected resource.
Example: Whose photo's are in google drive.

Resource Server: The server hosting the protected resource.A server that protects the user’s resources and receives access requests from the Client. It accepts and validates an Access Token from the Client and returns the appropriate resources to it.
Example: Google drive is the resource server.

Client: The client is the system that requires access to the protected resources. To access resources, the Client must hold the appropriate Access Token.
Example: Photo Printing service.

Authorization Server: This server receives requests from the Client for Access Tokens and issues them upon successful authentication and consent by the Resource Owner. The authorization server exposes two endpoints: the Authorization endpoint, which handles the interactive authentication and consent of the user, and the Token endpoint, which is involved in a machine to machine interaction.
Example: Google drive.


