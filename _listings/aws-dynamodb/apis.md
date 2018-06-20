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
tags: Items
created: "2018-06-20"
modified: "2018-06-20"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/items/master/_listings/aws-dynamodb/apis.md
specificationVersion: "0.14"
apis:
- name: Amazon DynamoDB API Batch Get Item
  x-api-slug: amazon-dynamodb-api
  description: |-
    The BatchGetItem operation returns the attributes of one or more items from one or
          more tables.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AmazonDynamoDB.png
  humanURL: https://aws.amazon.com/dynamodb/
  baseURL: ://///?Action=BatchGetItem
  tags: Batch Items
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/items/master/_listings/aws-dynamodb/actionbatchgetitem-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/items/master/_listings/aws-dynamodb/actionbatchgetitem-get-openapi.md
- name: Amazon DynamoDB API Batch Write Item
  x-api-slug: amazon-dynamodb-api
  description: The BatchWriteItem operation puts or deletes multiple items in one
    or more tables.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AmazonDynamoDB.png
  humanURL: https://aws.amazon.com/dynamodb/
  baseURL: ://///?Action=BatchWriteItem
  tags: Batch Items
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/items/master/_listings/aws-dynamodb/actionbatchwriteitem-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/items/master/_listings/aws-dynamodb/actionbatchwriteitem-get-openapi.md
- name: Amazon DynamoDB API Delete Item
  x-api-slug: amazon-dynamodb-api
  description: Deletes a single item in a table by primary key.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AmazonDynamoDB.png
  humanURL: https://aws.amazon.com/dynamodb/
  baseURL: ://///?Action=DeleteItem
  tags: Items
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/items/master/_listings/aws-dynamodb/actiondeleteitem-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/items/master/_listings/aws-dynamodb/actiondeleteitem-get-openapi.md
- name: Amazon DynamoDB API Get Item
  x-api-slug: amazon-dynamodb-api
  description: |-
    The GetItem operation returns a set of attributes for the item with the given primary
              key.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AmazonDynamoDB.png
  humanURL: https://aws.amazon.com/dynamodb/
  baseURL: ://///?Action=GetItem
  tags: Items
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/items/master/_listings/aws-dynamodb/actiongetitem-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/items/master/_listings/aws-dynamodb/actiongetitem-get-openapi.md
- name: Amazon DynamoDB API Put Item
  x-api-slug: amazon-dynamodb-api
  description: Creates a new item, or replaces an old item with a new item.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AmazonDynamoDB.png
  humanURL: https://aws.amazon.com/dynamodb/
  baseURL: ://///?Action=PutItem
  tags: Items
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/items/master/_listings/aws-dynamodb/actionputitem-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/items/master/_listings/aws-dynamodb/actionputitem-get-openapi.md
- name: Amazon DynamoDB API Update Item
  x-api-slug: amazon-dynamodb-api
  description: Edits an existing item's attributes, or adds a new item to the table
    if it does not already exist.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AmazonDynamoDB.png
  humanURL: https://aws.amazon.com/dynamodb/
  baseURL: ://///?Action=UpdateItem
  tags: Items
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/items/master/_listings/aws-dynamodb/actionupdateitem-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/items/master/_listings/aws-dynamodb/actionupdateitem-get-openapi.md
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
  tags: Items
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/items/master/_listings/aws-dynamodb/openapi.md
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