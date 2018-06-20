---
name: AWS DynamoDB
x-slug: aws-dynamodb
description: Amazon DynamoDB is a fast and flexible NoSQL database service for all
  applications that need consistent, single-digit millisecond latency at any scale.
  It is a fully managed cloud database and supports both document and key-value store
  models. Its flexible data model and reliable performance make it a great fit for
  mobile, web, gaming, ad tech, IoT, and many other applications. Start today by downloading
  the local version of DynamoDB, then read our Getting Started Guide.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AmazonDynamoDB.png
x-kinRank: "10"
x-alexaRank: "0"
tags: Tables
created: "2018-06-20"
modified: "2018-06-20"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/tables/master/_listings/aws-dynamodb/apis.md
specificationVersion: "0.14"
apis:
- name: Amazon DynamoDB API Create Table
  x-api-slug: amazon-dynamodb-api
  description: The CreateTable operation adds a new table to your account.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AmazonDynamoDB.png
  humanURL: https://aws.amazon.com/dynamodb/
  baseURL: ://///?Action=CreateTable
  tags: Tables
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/tables/master/_listings/aws-dynamodb/actioncreatetable-get-openapi.md
- name: Amazon DynamoDB API Delete Table
  x-api-slug: amazon-dynamodb-api
  description: The DeleteTable operation deletes a table and all of its items.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AmazonDynamoDB.png
  humanURL: https://aws.amazon.com/dynamodb/
  baseURL: ://///?Action=DeleteTable
  tags: Tables
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/tables/master/_listings/aws-dynamodb/actiondeletetable-get-openapi.md
- name: Amazon DynamoDB API Describe Table
  x-api-slug: amazon-dynamodb-api
  description: Returns information about the table, including the current status of
    the table, when it was created, the primary key schema, and any indexes on the
    table.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AmazonDynamoDB.png
  humanURL: https://aws.amazon.com/dynamodb/
  baseURL: ://///?Action=DescribeTable
  tags: Tables
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/tables/master/_listings/aws-dynamodb/actiondescribetable-get-openapi.md
- name: Amazon DynamoDB API List Tables
  x-api-slug: amazon-dynamodb-api
  description: Returns an array of table names associated with the current account
    and endpoint.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AmazonDynamoDB.png
  humanURL: https://aws.amazon.com/dynamodb/
  baseURL: ://///?Action=ListTables
  tags: Tables
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/tables/master/_listings/aws-dynamodb/actionlisttables-get-openapi.md
- name: Amazon DynamoDB API Update Table
  x-api-slug: amazon-dynamodb-api
  description: Modifies the provisioned throughput settings, global secondary indexes,
    or DynamoDB Streams settings for a given table.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AmazonDynamoDB.png
  humanURL: https://aws.amazon.com/dynamodb/
  baseURL: ://///?Action=UpdateTable
  tags: Tables
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/tables/master/_listings/aws-dynamodb/actionupdatetable-get-openapi.md
- name: Amazon DynamoDB API
  x-api-slug: amazon-dynamodb-api
  description: Amazon DynamoDB is a fast and flexible NoSQL database service for all
    applications that need consistent, single-digit millisecond latency at any scale.
    It is a fully managed cloud database and supports both document and key-value
    store models. Its flexible data model and reliable performance make it a great
    fit for mobile, web, gaming, ad tech, IoT, and many other applications. Start
    today by downloading the local version of DynamoDB, then read our Getting Started
    Guide.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AmazonDynamoDB.png
  humanURL: https://aws.amazon.com/dynamodb/
  baseURL: :///
  tags: Tables
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/tables/master/_listings/aws-dynamodb/openapi.md
x-common:
- type: x-best-practices
  url: https://aws.amazon.com/dynamodb/developer-resources/#BestPractices
- type: x-blog
  url: https://aws.amazon.com/dynamodb/developer-resources/#BlogPosts
- type: x-community
  url: https://aws.amazon.com/dynamodb/community/
- type: x-documentation
  url: http://docs.aws.amazon.com/amazondynamodb/latest/APIReference/Welcome.html
- type: x-documentation
  url: http://docs.aws.amazon.com/dynamodbstreams/latest/APIReference/
- type: x-faq
  url: https://aws.amazon.com/dynamodb/faqs/
- type: x-getting-started
  url: https://aws.amazon.com/dynamodb/getting-started/
- type: x-labs
  url: https://aws.amazon.com/dynamodb/developer-resources/#SelfPacedLabs
- type: x-partners
  url: https://aws.amazon.com/dynamodb/partners/
- type: x-pricing
  url: https://aws.amazon.com/dynamodb/pricing/
- type: x-sdk
  url: https://aws.amazon.com/dynamodb/developer-resources/#SDK
- type: x-slides
  url: https://aws.amazon.com/dynamodb/developer-resources/#Slides
- type: x-videos
  url: https://aws.amazon.com/dynamodb/developer-resources/#Videos
- type: x-website
  url: https://aws.amazon.com/dynamodb/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---