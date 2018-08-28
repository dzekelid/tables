{
  "info": {
    "name": "Dezrez Search for Actions across the system.",
    "_postman_id": "eb5327da-afc6-44b8-8da8-ce7919203e45",
    "description": "Search for actions across the system..",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "SearchActions",
      "item": [
        {
          "id": "884ec8e9-7b0a-4ed5-8919-a1f88880b9d1",
          "name": "GlobalSearch_AuctionsBydataContract.termBydataContract.pageSizeBydataContract.pageNumberBydataContra",
          "request": {
            "url": "http://api.dezrez.com/api/globalsearch/auctions?dataContract.branchId=%7B%7D&dataContract.excludeArchived=%7B%7D&dataContract.excludeDeleted=%7B%7D&dataContract.groupTypes=%7B%7D&dataContract.lastUpdated=%7B%7D&dataContract.pageNumber=%7B%7D&dataContract.pageSize=%7B%7D&dataContract.serviceType=%7B%7D&dataContract.term=%7B%7D",
            "method": "GET",
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
            "description": "Search for actions across the system.."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "8c9d9b37-80d2-4da4-b210-6e7a64829541"
            }
          ]
        }
      ]
    }
  ]
}