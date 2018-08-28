---
swagger: "2.0"
x-collection-name: Azure Automation
x-complete: 0
info:
  title: Azure Automation API Credential Get
  version: 1.0.0
  description: Retrieve the credential identified by credential name.
host: management.azure.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  ? /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Automation/automationAccounts/{automationAccountName}/credentials/{credentialName}
  : delete:
      summary: Credential Delete
      description: Delete the credential.
      operationId: Credential_Delete
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-automationautomationaccountsautomationaccountnamecredentialscredentialname-delete
      parameters:
      - in: path
        name: automationAccountName
        description: The automation account name
      - in: path
        name: credentialName
        description: The name of credential
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Credential
    get:
      summary: Credential Get
      description: Retrieve the credential identified by credential name.
      operationId: Credential_Get
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-automationautomationaccountsautomationaccountnamecredentialscredentialname-get
      parameters:
      - in: path
        name: automationAccountName
        description: The automation account name
      - in: path
        name: credentialName
        description: The name of credential
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Credential
x-streamrank:
  polling_total_time_average: 0
  polling_size_download_average: 0
  streaming_total_time_average: 0
  streaming_size_download_average: 0
  change_yes: 0
  change_no: 0
  time_percentage: 0
  size_percentage: 0
  change_percentage: 0
  last_run: ""
  days_run: 0
  minute_run: 0
---