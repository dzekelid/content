---
swagger: "2.0"
x-collection-name: Azure Automation
x-complete: 0
info:
  title: Azure Automation API Node Reports Get Content
  version: 1.0.0
  description: Retrieve the Dsc node reports by node id and report id.
host: management.azure.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  ? /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Automation/automationAccounts/{automationAccountName}/configurations/{configurationName}/content
  : get:
      summary: Dsc Configuration Get Content
      description: Retrieve the configuration script identified by configuration name.
      operationId: DscConfiguration_GetContent
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-automationautomationaccountsautomationaccountnameconfigurationsconfigurationnamecontent-get
      parameters:
      - in: path
        name: automationAccountName
        description: The automation account name
      - in: path
        name: configurationName
        description: The configuration name
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Dsc
      - Configuration
      - ""
      - Content
  ? /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Automation/automationAccounts/{automationAccountName}/nodes/{nodeId}/reports/{reportId}/content
  : get:
      summary: Node Reports Get Content
      description: Retrieve the Dsc node reports by node id and report id.
      operationId: NodeReports_GetContent
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-automationautomationaccountsautomationaccountnamenodesnodeidreportsreportidcontent-get
      parameters:
      - in: path
        name: automationAccountName
        description: The automation account name
      - in: query
        name: No Name
      - in: path
        name: nodeId
        description: The Dsc node id
      - in: path
        name: reportId
        description: The report id
      responses:
        200:
          description: OK
      tags:
      - Node
      - Reports
      - ""
      - Content
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