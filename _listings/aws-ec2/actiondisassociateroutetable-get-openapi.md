---
swagger: "2.0"
x-collection-name: AWS EC2
x-complete: 0
info:
  title: AWS EC2 API Disassociate Route Table
  version: 1.0.0
  description: Disassociates a subnet from a route table.
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=DescribeRouteTables:
    get:
      summary: Describe Route Tables
      description: Describes one or more of your route tables.
      operationId: describeroutetables
      x-api-path-slug: actiondescriberoutetables-get
      parameters:
      - in: query
        name: GatewayId
        description: The ID of the virtual private gateway
        type: string
      - in: query
        name: RouteTableId
        description: The ID of the route table
        type: string
      responses:
        200:
          description: OK
      tags:
      - Route Tables
  /?Action=AssociateRouteTable:
    get:
      summary: Associate Route Table
      description: Associates a subnet with a route table.
      operationId: associateroutetable
      x-api-path-slug: actionassociateroutetable-get
      parameters:
      - in: query
        name: DestinationCidrBlock
        description: The IPv4 CIDR address block used for the destination match
        type: string
      - in: query
        name: DestinationIpv6CidrBlock
        description: The IPv6 CIDR block used for the destination match
        type: string
      - in: query
        name: DryRun
        description: Checks whether you have the required permissions for the action,
          without actually making the request,        and provides an error response
        type: string
      - in: query
        name: EgressOnlyInternetGatewayId
        description: '[IPv6 traffic only] The ID of an egress-only Internet gateway'
        type: string
      - in: query
        name: GatewayId
        description: The ID of an Internet gateway or virtual private gateway attached
          to your VPC
        type: string
      - in: query
        name: InstanceId
        description: The ID of a NAT instance in your VPC
        type: string
      - in: query
        name: NatGatewayId
        description: '[IPv4 traffic only] The ID of a NAT gateway'
        type: string
      - in: query
        name: NetworkInterfaceId
        description: The ID of a network interface
        type: string
      - in: query
        name: RouteTableId
        description: The ID of the route table for the route
        type: string
      - in: query
        name: VpcPeeringConnectionId
        description: The ID of a VPC peering connection
        type: string
      responses:
        200:
          description: OK
      tags:
      - Route Table
  /?Action=CreateRouteTable:
    get:
      summary: Create Route Table
      description: Creates a route table for the specified VPC.
      operationId: createroutetable
      x-api-path-slug: actioncreateroutetable-get
      parameters:
      - in: query
        name: DestinationCidrBlock
        description: The IPv4 CIDR range for the route
        type: string
      - in: query
        name: DestinationIpv6CidrBlock
        description: The IPv6 CIDR range for the route
        type: string
      - in: query
        name: DryRun
        description: Checks whether you have the required permissions for the action,
          without actually making the request,        and provides an error response
        type: string
      - in: query
        name: RouteTableId
        description: The ID of the route table
        type: string
      responses:
        200:
          description: OK
      tags:
      - Route Table
  /?Action=DeleteRouteTable:
    get:
      summary: Delete Route Table
      description: Deletes the specified route table.
      operationId: deleteroutetable
      x-api-path-slug: actiondeleteroutetable-get
      parameters:
      - in: query
        name: DryRun
        description: Checks whether you have the required permissions for the action,
          without actually making the request,        and provides an error response
        type: string
      - in: query
        name: Filter.N
        description: One or more filters
        type: string
      - in: query
        name: RouteTableId.N
        description: One or more route table IDs
        type: string
      responses:
        200:
          description: OK
      tags:
      - Route Table
  /?Action=DisassociateRouteTable:
    get:
      summary: Disassociate Route Table
      description: Disassociates a subnet from a route table.
      operationId: disassociateroutetable
      x-api-path-slug: actiondisassociateroutetable-get
      parameters:
      - in: query
        name: GatewayId
        description: The ID of the virtual private gateway
        type: string
      - in: query
        name: RouteTableId
        description: The ID of the route table
        type: string
      responses:
        200:
          description: OK
      tags:
      - Route Table
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