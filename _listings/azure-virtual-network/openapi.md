---
swagger: "2.0"
x-collection-name: Azure Virtual Network
x-complete: 1
info:
  title: NetworkManagementClient
  description: the-microsoft-azure-network-management-api-provides-a-restful-set-of-web-services-that-interact-with-microsoft-azure-networks-service-to-manage-your-network-resources--the-api-has-entities-that-capture-the-relationship-between-an-end-user-and-the-microsoft-azure-networks-service-
  version: 1.0.0
host: management.azure.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Network/routeTables/{routeTableName}:
    delete:
      summary: Route Tables Delete
      description: Deletes the specified route table.
      operationId: RouteTables_Delete
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-networkroutetablesroutetablename-delete
      parameters:
      - in: query
        name: No Name
      - in: path
        name: resourceGroupName
        description: The name of the resource group
      - in: path
        name: routeTableName
        description: The name of the route table
      responses:
        200:
          description: OK
      tags:
      - Route Tables
    get:
      summary: Route Tables Get
      description: Gets the specified route table.
      operationId: RouteTables_Get
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-networkroutetablesroutetablename-get
      parameters:
      - in: query
        name: $expand
        description: Expands referenced resources
      - in: query
        name: No Name
      - in: path
        name: resourceGroupName
        description: The name of the resource group
      - in: path
        name: routeTableName
        description: The name of the route table
      responses:
        200:
          description: OK
      tags:
      - Route Tables
    put:
      summary: Route Tables Create Or Update
      description: Create or updates a route table in a specified resource group.
      operationId: RouteTables_CreateOrUpdate
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-networkroutetablesroutetablename-put
      parameters:
      - in: query
        name: No Name
      - in: body
        name: parameters
        description: Parameters supplied to the create or update route table operation
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: resourceGroupName
        description: The name of the resource group
      - in: path
        name: routeTableName
        description: The name of the route table
      responses:
        200:
          description: OK
      tags:
      - Route Tables
  /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Network/routeTables:
    get:
      summary: Route Tables List
      description: Gets all route tables in a resource group.
      operationId: RouteTables_List
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-networkroutetables-get
      parameters:
      - in: query
        name: No Name
      - in: path
        name: resourceGroupName
        description: The name of the resource group
      responses:
        200:
          description: OK
      tags:
      - Route Tables
  /subscriptions/{subscriptionId}/providers/Microsoft.Network/routeTables:
    get:
      summary: Route Tables List All
      description: Gets all route tables in a subscription.
      operationId: RouteTables_ListAll
      x-api-path-slug: subscriptionssubscriptionidprovidersmicrosoft-networkroutetables-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Route Tables
---