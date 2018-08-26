{
  "info": {
    "name": "Dezrez Delete Security Credentials",
    "_postman_id": "b8369e1d-63e0-4b93-a724-f77b0079b711",
    "description": "Delete security credentials.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Security",
      "item": [
        {
          "id": "2669fd18-bc3f-4c3d-bbb6-3a455056da1c",
          "name": "Credentials_DeleteUsernamePasswordByname",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.dezrez.com",
              "path": [
                "api/credentials/deleteusernamepassword/:name"
              ],
              "variable": [
                {
                  "id": "name",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "DELETE",
            "header": [
              {
                "key": "Rezi-Api-Version",
                "value": "{}",
                "description": "Specifies which version of the API to call",
                "disabled": false
              },
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Delete security credentials."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "7a1a14d6-84be-4506-a77a-90d61d1eac29"
            }
          ]
        }
      ]
    }
  ]
}