---
swagger: "2.0"
x-collection-name: AWS Identity and Access Management
x-complete: 0
info:
  title: AWS Identity and Access Management API List Service Specific Credentials
  version: 1.0.0
  description: |-
    Returns information about the service-specific credentials associated with the
          specified IAM user.
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=CreateServiceSpecificCredential:
    get:
      summary: Create Service Specific Credential
      description: |-
        Generates a set of credentials consisting of a user name and password that can be used
              to access the service specified in the request.
      operationId: createServiceSpecificCredential
      x-api-path-slug: actioncreateservicespecificcredential-get
      parameters:
      - in: query
        name: ServiceName
        description: The name of the AWS service that is to be associated with the
          credentials
        type: string
      - in: query
        name: UserName
        description: The name of the IAM user that is to be associated with the credentials
        type: string
      responses:
        200:
          description: OK
      tags:
      - Service Specific Credentials
  /?Action=DeleteServiceSpecificCredential:
    get:
      summary: Delete Service Specific Credential
      description: Deletes the specified service-specific credential.
      operationId: deleteServiceSpecificCredential
      x-api-path-slug: actiondeleteservicespecificcredential-get
      parameters:
      - in: query
        name: ServiceSpecificCredentialId
        description: The unique identifier of the service-specific credential
        type: string
      - in: query
        name: UserName
        description: The name of the IAM user associated with the service-specific
          credential
        type: string
      responses:
        200:
          description: OK
      tags:
      - Service Specific Credentials
  /?Action=GenerateCredentialReport:
    get:
      summary: Generate Credential Report
      description: Generates a credential report for the AWS account.
      operationId: generateCredentialReport
      x-api-path-slug: actiongeneratecredentialreport-get
      parameters:
      - in: query
        name: Description
        description: Information about the credential report
        type: string
      - in: query
        name: State
        description: Information about the state of the credential report
        type: string
      responses:
        200:
          description: OK
      tags:
      - Credential Reports
  /?Action=GetCredentialReport:
    get:
      summary: Get Credential Report
      description: Retrieves a credential report for the AWS account.
      operationId: getCredentialReport
      x-api-path-slug: actiongetcredentialreport-get
      parameters:
      - in: query
        name: Content
        description: Contains the credential report
        type: string
      - in: query
        name: GeneratedTime
        description: The date and time when the credential report was created, in
          ISO 8601 date-time format
        type: string
      - in: query
        name: ReportFormat
        description: The format (MIME type) of the credential report
        type: string
      responses:
        200:
          description: OK
      tags:
      - Credential Reports
  /?Action=ListServiceSpecificCredentials:
    get:
      summary: List Service Specific Credentials
      description: |-
        Returns information about the service-specific credentials associated with the
              specified IAM user.
      operationId: listServiceSpecificCredentials
      x-api-path-slug: actionlistservicespecificcredentials-get
      parameters:
      - in: query
        name: ServiceName
        description: Filters the returned results to only those for the specified
          AWS service
        type: string
      - in: query
        name: UserName
        description: The name of the user whose service-specific credentials you want
          information about
        type: string
      responses:
        200:
          description: OK
      tags:
      - Service Specific Credentials
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