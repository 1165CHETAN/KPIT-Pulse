---
external: false
title: "JWT Authentication"
description: "You can author content using the familiar markdown syntax you already know. All basic markdown syntax is supported."
date: 2023-12-07
---

![jwt](/images/jwt2.jpg)
>JWT (JSON Web Token) is a widely-used standard for secure data transmission, facilitating authentication and authorization between parties in distributed systems.


## Why to go with JWT?
![jwt](/images/jwt3.png)

#### Server-to-Server Authorization: 
JWTs are well-suited for server-to-server or microservice-to-microservice communication, enabling secure transmission of information for authentication and authorization between different servers.

#### Cross-Server Operations: 
When a user is authenticated on SERVER1 and needs to perform an operation on SERVER2, SERVER1 can issue a JWT to authorize access to SERVER2 without the need for shared sessions or constant database lookups.

#### Token Refresh Mechanism: 
JWTs can be used in conjunction with refresh tokens for secure token renewal. After a user logs in, the server generates both an access token (JWT) and a refresh token. The access token has a short expiration time, and when it expires, the client can request a new access token using the refresh token.

#### Efficient Identity Extraction: 
JWTs eliminate the need for constant database lookups by storing user identity and authorization details within the token itself. This efficient extraction process enhances performance by reducing the need for repetitive database queries.

#### Token Revocation Handling: 
To address the non-revocability issue of JWTs, a common solution involves maintaining a database of "revoked tokens." Although this adds an extra database call, it allows for token revocation, enhancing security by denying access if the token is found to be revoked.

## Follow below tutorial

{% youtube url="https://www.youtube.com/embed/x5gLL8-M9Fo?si=G1VVJTBpThhqBgJA" label="Everything is awesome - Lego movie song" /%}

