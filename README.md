<<<<<<< HEAD
# contactlist

```json
{
  "swagger": "2.0",
  "info": {
    "version": "v1",
    "title": "Contact List",
    "description": "A Contact list API based on Swagger and built using Node.js"
  },
  "host": "localhost",
  "schemes": [
    "http",
    "https"
  ],
  "basePath": "/",
  "paths": {
    "/contacts": {
      "get": {
        "tags": [
          "Contacts"
        ],
        "operationId": "contacts_get",
        "consumes": [],
        "produces": [
          "application/json",
          "text/json"
        ],
        "responses": {
          "200": {
            "description": "OK",
            "schema": {
              "type": "array",
              "items": {
                "$ref": "#/definitions/Contact"
              }
            }
          }
        },
        "deprecated": false
      }
    },
    "/contacts/{id}": {
      "get": {
        "tags": [
          "Contacts"
        ],
        "operationId": "contacts_getById",
        "consumes": [],
        "produces": [
          "application/json",
          "text/json"
        ],
        "parameters": [
          {
            "name": "id",
            "in": "path",
            "required": true,
            "type": "integer",
            "format": "int32"
          }
        ],
        "responses": {
          "200": {
            "description": "OK",
            "schema": {
              "type": "array",
              "items": {
                "$ref": "#/definitions/Contacts"
              }
            }
          }
        },
        "deprecated": false
      }
    }
  },
  "definitions": {
    "Contact": {
      "type": "object",
      "properties": {
        "id": {
          "format": "int32",
          "type": "integer"
        },
        "name": {
          "type": "string"
        },
        "email": {
          "type": "string"
        }
      }
    }
  }
}
```
=======
# app-service-api-node-contact-list

## Running this sample
Coming soon...
## Deploy this sample to Azure
Coming soon...
## About the code
Coming soon...
## More information
Coming soon...
>>>>>>> 15e302b323ffa6bf46d67b7ab7a9b28ceea1ee75
