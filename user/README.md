# User Service Technical Requirements Document (TRD)

## Overview

The User Service is responsible for managing user accounts in the ecommerce microservice system. This service allows users to register, login, view and update their profile information, and view their order history.

## Technical Requirements

### API Endpoints

The User Service shall provide the following API endpoints:

#### Register User

Endpoint: `/users/register`

Method: `POST`

Request body:

```json
{
	"username": "string",
	"password": "string",
	"email": "string",
	"full_name": "string",
	"address": "string"
}
```

Response body:

```json
{
	"code": 201
	"message": "ok"
	"responseTime": "20230401"
	"user": {
		"message": "waiting user email verification"
	}
}
```
#### Login User

Endpoint: `/users/login`

Method: `POST`

Request body:

```json
{
	"username": "string",
	"password": "string"
}
```

Response body:


```json
{
	"access_token": "string",
	"user_id": "string",
	"username": "string"
}
```
