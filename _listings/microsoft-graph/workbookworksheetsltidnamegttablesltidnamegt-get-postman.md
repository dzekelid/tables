{
  "info": {
    "name": "Microsoft Graph API Get Table",
    "_postman_id": "9291e6ca-89ab-49b2-9447-1a9c3332dae9",
    "description": "Get Table Retrieve the properties and relationships of table object.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Attachment",
      "item": [
        {
          "id": "0cd03ffd-6dde-40c7-a117-c642d7097e43",
          "name": "GetAttachment",
          "request": {
            "url": {
              "protocol": "http",
              "host": "graph.microsoft.com",
              "path": [
                "me/events/:id/attachments/:id"
              ],
              "variable": [
                {
                  "id": "id",
                  "value": "id",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "header": [
              {
                "key": "Authorization",
                "value": "Authorization",
                "description": "Bearer",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Get attachment\nRead the properties and relationships of an attachment, attached to an event,\nmessage, or post."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "b33fa0c5-e8e2-401e-b8cb-cd2a9f228634"
            }
          ]
        },
        {
          "id": "9917bf2a-a648-4b7a-986e-010de91c8843",
          "name": "GetAttachment",
          "request": {
            "url": {
              "protocol": "http",
              "host": "graph.microsoft.com",
              "path": [
                "users/:id | userPrincipalName/events/:id/attachments/:id"
              ],
              "variable": [
                {
                  "id": "id",
                  "value": "id",
                  "type": "string"
                },
                {
                  "id": "id | userPrincipalName",
                  "value": "id | userPrincipalName",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "header": [
              {
                "key": "Authorization",
                "value": "Authorization",
                "description": "Bearer",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Get attachment\nRead the properties and relationships of an attachment, attached to an event,\nmessage, or post."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "937cadc5-05b6-4c74-808d-7d50f7e5a86f"
            }
          ]
        },
        {
          "id": "5e8f27f5-719e-48f3-86d7-4fcd68efcbae",
          "name": "GetAttachment1",
          "request": {
            "url": {
              "protocol": "http",
              "host": "graph.microsoft.com",
              "path": [
                "groups/:id/events/:id/attachments/:id"
              ],
              "variable": [
                {
                  "id": "id",
                  "value": "id",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "header": [
              {
                "key": "Authorization",
                "value": "Authorization",
                "description": "Bearer",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Get attachment\nRead the properties and relationships of an attachment, attached to an event,\nmessage, or post."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "dfc836c2-c544-4218-840f-a9a29b6606a6"
            }
          ]
        },
        {
          "id": "21483383-1dd6-444e-b602-2ad74f5f6526",
          "name": "GetAttachment2",
          "request": {
            "url": {
              "protocol": "http",
              "host": "graph.microsoft.com",
              "path": [
                "me/calendar/:id/events/:id/attachments/:id"
              ],
              "variable": [
                {
                  "id": "id",
                  "value": "id",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "header": [
              {
                "key": "Authorization",
                "value": "Authorization",
                "description": "Bearer",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Get attachment\nRead the properties and relationships of an attachment, attached to an event,\nmessage, or post."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "dc1db5aa-f6a0-4cc3-a083-7e8de5a7395f"
            }
          ]
        },
        {
          "id": "a73ffcc2-f399-4083-b70b-f204b1d62b2f",
          "name": "GetAttachment1",
          "request": {
            "url": {
              "protocol": "http",
              "host": "graph.microsoft.com",
              "path": [
                "users/:id | userPrincipalName/calendar/events/:id/attachments/:id"
              ],
              "variable": [
                {
                  "id": "id",
                  "value": "id",
                  "type": "string"
                },
                {
                  "id": "id | userPrincipalName",
                  "value": "id | userPrincipalName",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "header": [
              {
                "key": "Authorization",
                "value": "Authorization",
                "description": "Bearer",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Get attachment\nRead the properties and relationships of an attachment, attached to an event,\nmessage, or post."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "45415b67-dc63-4881-a58e-3458f7ee46d5"
            }
          ]
        },
        {
          "id": "4ff84032-5f30-4c32-ada4-7f428627dd5a",
          "name": "GetAttachment3",
          "request": {
            "url": {
              "protocol": "http",
              "host": "graph.microsoft.com",
              "path": [
                "groups/:id/calendar/events/:id/attachments/:id"
              ],
              "variable": [
                {
                  "id": "id",
                  "value": "id",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "header": [
              {
                "key": "Authorization",
                "value": "Authorization",
                "description": "Bearer",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Get attachment\nRead the properties and relationships of an attachment, attached to an event,\nmessage, or post."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "8fe9f376-466a-4699-9a07-5c419bbe457e"
            }
          ]
        },
        {
          "id": "c4831f04-4a13-40f4-b587-144422728823",
          "name": "GetAttachment4",
          "request": {
            "url": {
              "protocol": "http",
              "host": "graph.microsoft.com",
              "path": [
                "me/calendars/:id/events/:id/attachments/:id"
              ],
              "variable": [
                {
                  "id": "id",
                  "value": "id",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "header": [
              {
                "key": "Authorization",
                "value": "Authorization",
                "description": "Bearer",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Get attachment\nRead the properties and relationships of an attachment, attached to an event,\nmessage, or post."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "98a551ce-64fe-4947-a08f-3962477b3909"
            }
          ]
        },
        {
          "id": "fe19e7d8-7754-41d7-b3e5-117fbcb91bd6",
          "name": "GetAttachment2",
          "request": {
            "url": {
              "protocol": "http",
              "host": "graph.microsoft.com",
              "path": [
                "users/:id | userPrincipalName/calendars/:id/events/:id/attachments/:id"
              ],
              "variable": [
                {
                  "id": "id",
                  "value": "id",
                  "type": "string"
                },
                {
                  "id": "id | userPrincipalName",
                  "value": "id | userPrincipalName",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "header": [
              {
                "key": "Authorization",
                "value": "Authorization",
                "description": "Bearer",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Get attachment\nRead the properties and relationships of an attachment, attached to an event,\nmessage, or post."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "7330ac61-de2b-4fa7-b4a5-a502bce2b54f"
            }
          ]
        },
        {
          "id": "247a6769-01bc-4d01-996a-ef3adaffdaea",
          "name": "GetAttachment5",
          "request": {
            "url": {
              "protocol": "http",
              "host": "graph.microsoft.com",
              "path": [
                "me/calendargroup/calendars/:id/events/:id/attachments/:id"
              ],
              "variable": [
                {
                  "id": "id",
                  "value": "id",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "header": [
              {
                "key": "Authorization",
                "value": "Authorization",
                "description": "Bearer",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Get attachment\nRead the properties and relationships of an attachment, attached to an event,\nmessage, or post."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "905a25ec-53ea-406f-9372-c65e41182158"
            }
          ]
        },
        {
          "id": "8212da13-26ed-4a87-b73e-3840ed62f046",
          "name": "GetAttachment3",
          "request": {
            "url": {
              "protocol": "http",
              "host": "graph.microsoft.com",
              "path": [
                "users/:id | userPrincipalName/calendargroup/calendars/:id/events/:id/attachments/:id"
              ],
              "variable": [
                {
                  "id": "id",
                  "value": "id",
                  "type": "string"
                },
                {
                  "id": "id | userPrincipalName",
                  "value": "id | userPrincipalName",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "header": [
              {
                "key": "Authorization",
                "value": "Authorization",
                "description": "Bearer",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Get attachment\nRead the properties and relationships of an attachment, attached to an event,\nmessage, or post."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "c42253d5-fee1-4bfe-87dc-a5ebe2ca4143"
            }
          ]
        },
        {
          "id": "678394a5-aa55-492a-86a2-ad37625cb360",
          "name": "GetAttachment6",
          "request": {
            "url": {
              "protocol": "http",
              "host": "graph.microsoft.com",
              "path": [
                "me/calendargroups/:id/calendars/:id/events/:id/attachments/:id"
              ],
              "variable": [
                {
                  "id": "id",
                  "value": "id",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "header": [
              {
                "key": "Authorization",
                "value": "Authorization",
                "description": "Bearer",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Get attachment\nRead the properties and relationships of an attachment, attached to an event,\nmessage, or post."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "6a700b31-ece9-4b0f-8366-a39f94d65e9f"
            }
          ]
        },
        {
          "id": "7109a66a-e167-48bf-85f1-4e62f342f319",
          "name": "GetAttachment4",
          "request": {
            "url": {
              "protocol": "http",
              "host": "graph.microsoft.com",
              "path": [
                "users/:id | userPrincipalName/calendargroups/:id/calendars/:id/events/:id/attachments/:id"
              ],
              "variable": [
                {
                  "id": "id",
                  "value": "id",
                  "type": "string"
                },
                {
                  "id": "id | userPrincipalName",
                  "value": "id | userPrincipalName",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "header": [
              {
                "key": "Authorization",
                "value": "Authorization",
                "description": "Bearer",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Get attachment\nRead the properties and relationships of an attachment, attached to an event,\nmessage, or post."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "7c9558c2-ff32-4cee-bae9-ed3fe7ee70ff"
            }
          ]
        },
        {
          "id": "35a61a43-558b-4795-a57c-64f963cdc7f6",
          "name": "GetAttachment7",
          "request": {
            "url": {
              "protocol": "http",
              "host": "graph.microsoft.com",
              "path": [
                "me/messages/:id/attachments/:id"
              ],
              "variable": [
                {
                  "id": "id",
                  "value": "id",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "header": [
              {
                "key": "Authorization",
                "value": "Authorization",
                "description": "Bearer",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Get attachment\nRead the properties and relationships of an attachment, attached to an event,\nmessage, or post."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "6584ab59-37bf-49cb-ac3a-c5e6e1586a26"
            }
          ]
        },
        {
          "id": "941e0df9-377b-4db4-8621-7f527ace76e0",
          "name": "GetAttachment5",
          "request": {
            "url": {
              "protocol": "http",
              "host": "graph.microsoft.com",
              "path": [
                "users/:id | userPrincipalName/messages/:id/attachments/:id"
              ],
              "variable": [
                {
                  "id": "id",
                  "value": "id",
                  "type": "string"
                },
                {
                  "id": "id | userPrincipalName",
                  "value": "id | userPrincipalName",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "header": [
              {
                "key": "Authorization",
                "value": "Authorization",
                "description": "Bearer",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Get attachment\nRead the properties and relationships of an attachment, attached to an event,\nmessage, or post."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "9ff6fd60-b830-4918-a4b3-d016bf89ec4a"
            }
          ]
        },
        {
          "id": "a8d2aceb-be45-4c21-ab3c-490394d2ed48",
          "name": "GetAttachment8",
          "request": {
            "url": {
              "protocol": "http",
              "host": "graph.microsoft.com",
              "path": [
                "me/mailFolders/:id/messages/:id/attachments/:id"
              ],
              "variable": [
                {
                  "id": "id",
                  "value": "id",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "header": [
              {
                "key": "Authorization",
                "value": "Authorization",
                "description": "Bearer",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Get attachment\nRead the properties and relationships of an attachment, attached to an event,\nmessage, or post."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "e963fee2-df6e-4304-b688-e683727f58a7"
            }
          ]
        },
        {
          "id": "fc06c0cf-d7f6-4455-b912-3297f76b979d",
          "name": "GetAttachment6",
          "request": {
            "url": {
              "protocol": "http",
              "host": "graph.microsoft.com",
              "path": [
                "users/:id | userPrincipalName/mailFolders/:id/messages/:id/attachments/:id"
              ],
              "variable": [
                {
                  "id": "id",
                  "value": "id",
                  "type": "string"
                },
                {
                  "id": "id | userPrincipalName",
                  "value": "id | userPrincipalName",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "header": [
              {
                "key": "Authorization",
                "value": "Authorization",
                "description": "Bearer",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Get attachment\nRead the properties and relationships of an attachment, attached to an event,\nmessage, or post."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "fc9a64f7-bdb4-4c3a-9345-f97918e5e17f"
            }
          ]
        },
        {
          "id": "cc2e17cc-343e-4440-a878-e6f2fdf66762",
          "name": "AddAttachment",
          "request": {
            "url": {
              "protocol": "http",
              "host": "graph.microsoft.com",
              "path": [
                "me/mailFolders/:id/childFolders/:id/.../messages/:id/attachments/:id"
              ],
              "variable": [
                {
                  "id": "id",
                  "value": "id",
                  "type": "string"
                }
              ]
            },
            "method": "POST",
            "header": [
              {
                "key": "Authorization",
                "value": "Authorization",
                "description": "Bearer",
                "disabled": false
              },
              {
                "key": "Content-Type",
                "value": "Content-Type",
                "description": "Nature of the data in the body of an entity",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Add attachment Use this API to add an attachment to a message."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "cf2ae2a1-9d2f-4faf-9cee-772613ae3f96"
            }
          ]
        },
        {
          "id": "c3a9c785-7682-4106-96df-64cd6bef16bc",
          "name": "AddAttachment",
          "request": {
            "url": {
              "protocol": "http",
              "host": "graph.microsoft.com",
              "path": [
                "users/:id | userPrincipalName/mailFolders/:id/childFolders/:id/messages/:id/attachments/:id"
              ],
              "variable": [
                {
                  "id": "id",
                  "value": "id",
                  "type": "string"
                },
                {
                  "id": "id | userPrincipalName",
                  "value": "id | userPrincipalName",
                  "type": "string"
                }
              ]
            },
            "method": "POST",
            "header": [
              {
                "key": "Authorization",
                "value": "Authorization",
                "description": "Bearer",
                "disabled": false
              },
              {
                "key": "Content-Type",
                "value": "Content-Type",
                "description": "Nature of the data in the body of an entity",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Add attachment Use this API to add an attachment to a message."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "a67aada5-6d09-4c2f-83fa-4dbf9ac1ad5c"
            }
          ]
        },
        {
          "id": "f6d68a17-4dda-420c-b03a-e82a4eaff564",
          "name": "GetAttachment9",
          "request": {
            "url": {
              "protocol": "http",
              "host": "graph.microsoft.com",
              "path": [
                "groups/:id/threads/:id/posts/:id/attachments/:id"
              ],
              "variable": [
                {
                  "id": "id",
                  "value": "id",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "header": [
              {
                "key": "Authorization",
                "value": "Authorization",
                "description": "Bearer",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Get attachment\nRead the properties and relationships of an attachment, attached to an event,\nmessage, or post."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "7e972126-6423-457b-a1f1-4a5d6a58a785"
            }
          ]
        },
        {
          "id": "db1743fb-d315-44a0-bacf-47badd232922",
          "name": "GetAttachment10",
          "request": {
            "url": {
              "protocol": "http",
              "host": "graph.microsoft.com",
              "path": [
                "groups/:id/conversations/:id/threads/:id/posts/:id/attachments/:id"
              ],
              "variable": [
                {
                  "id": "id",
                  "value": "id",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "header": [
              {
                "key": "Authorization",
                "value": "Authorization",
                "description": "Bearer",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Get attachment\nRead the properties and relationships of an attachment, attached to an event,\nmessage, or post."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "45d2d6e6-26ef-4236-b148-91af0e26e99f"
            }
          ]
        },
        {
          "id": "2e12893b-532a-4e87-8f19-7433bcd50c72",
          "name": "AddAttachment1",
          "request": {
            "url": {
              "protocol": "http",
              "host": "graph.microsoft.com",
              "path": [
                "me/events/:id/attachments"
              ],
              "variable": [
                {
                  "id": "id",
                  "value": "id",
                  "type": "string"
                }
              ]
            },
            "method": "POST",
            "header": [
              {
                "key": "Authorization",
                "value": "Authorization",
                "description": "Bearer",
                "disabled": false
              },
              {
                "key": "Content-Type",
                "value": "Content-Type",
                "description": "Nature of the data in the body of an entity",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Add attachment Use this API to add an attachment to an event. Since there is currently a limit of 4MB on the total size of each REST request, this limits the size of the attachment you can add to under 4MB."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "e7cf933d-3a93-4db2-aa30-fad14132a1d7"
            }
          ]
        },
        {
          "id": "6a5326ba-9616-41e7-8154-0f2f8f603a5a",
          "name": "AddAttachment1",
          "request": {
            "url": {
              "protocol": "http",
              "host": "graph.microsoft.com",
              "path": [
                "users/:id | userPrincipalName/events/:id/attachments"
              ],
              "variable": [
                {
                  "id": "id",
                  "value": "id",
                  "type": "string"
                },
                {
                  "id": "id | userPrincipalName",
                  "value": "id | userPrincipalName",
                  "type": "string"
                }
              ]
            },
            "method": "POST",
            "header": [
              {
                "key": "Authorization",
                "value": "Authorization",
                "description": "Bearer",
                "disabled": false
              },
              {
                "key": "Content-Type",
                "value": "Content-Type",
                "description": "Nature of the data in the body of an entity",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Add attachment Use this API to add an attachment to an event. Since there is currently a limit of 4MB on the total size of each REST request, this limits the size of the attachment you can add to under 4MB."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "cd9bf783-d6b3-4862-a1df-cdb154eb105c"
            }
          ]
        },
        {
          "id": "6fc7b74b-e69a-4a25-98fb-ae89b5c06ded",
          "name": "AddAttachment2",
          "request": {
            "url": {
              "protocol": "http",
              "host": "graph.microsoft.com",
              "path": [
                "groups/:id/events/:id/attachments"
              ],
              "variable": [
                {
                  "id": "id",
                  "value": "id",
                  "type": "string"
                }
              ]
            },
            "method": "POST",
            "header": [
              {
                "key": "Authorization",
                "value": "Authorization",
                "description": "Bearer",
                "disabled": false
              },
              {
                "key": "Content-Type",
                "value": "Content-Type",
                "description": "Nature of the data in the body of an entity",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Add attachment Use this API to add an attachment to an event. Since there is currently a limit of 4MB on the total size of each REST request, this limits the size of the attachment you can add to under 4MB."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "e6d36442-451f-4e96-8041-54391fe5c1b8"
            }
          ]
        },
        {
          "id": "ae780944-fc58-4b61-acda-ecaced6e7e3b",
          "name": "AddAttachment3",
          "request": {
            "url": {
              "protocol": "http",
              "host": "graph.microsoft.com",
              "path": [
                "me/calendar/events/:id/attachments"
              ],
              "variable": [
                {
                  "id": "id",
                  "value": "id",
                  "type": "string"
                }
              ]
            },
            "method": "POST",
            "header": [
              {
                "key": "Authorization",
                "value": "Authorization",
                "description": "Bearer",
                "disabled": false
              },
              {
                "key": "Content-Type",
                "value": "Content-Type",
                "description": "Nature of the data in the body of an entity",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Add attachment Use this API to add an attachment to an event. Since there is currently a limit of 4MB on the total size of each REST request, this limits the size of the attachment you can add to under 4MB."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "85840bce-c5e9-4a32-ad5c-3976fd1f1143"
            }
          ]
        },
        {
          "id": "f60bc848-cd5b-4bf6-85fe-4ecc2ef11490",
          "name": "AddAttachment2",
          "request": {
            "url": {
              "protocol": "http",
              "host": "graph.microsoft.com",
              "path": [
                "users/:id | userPrincipalName/calendar/events/:id/attachments"
              ],
              "variable": [
                {
                  "id": "id",
                  "value": "id",
                  "type": "string"
                },
                {
                  "id": "id | userPrincipalName",
                  "value": "id | userPrincipalName",
                  "type": "string"
                }
              ]
            },
            "method": "POST",
            "header": [
              {
                "key": "Authorization",
                "value": "Authorization",
                "description": "Bearer",
                "disabled": false
              },
              {
                "key": "Content-Type",
                "value": "Content-Type",
                "description": "Nature of the data in the body of an entity",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Add attachment Use this API to add an attachment to an event. Since there is currently a limit of 4MB on the total size of each REST request, this limits the size of the attachment you can add to under 4MB."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "2c8a73aa-1275-4f93-9117-7ca10226c4db"
            }
          ]
        },
        {
          "id": "dea0dd2a-f239-4eec-b6dc-74c0a8bbebd6",
          "name": "AddAttachment4",
          "request": {
            "url": {
              "protocol": "http",
              "host": "graph.microsoft.com",
              "path": [
                "groups/:id/calendar/events/:id/attachments"
              ],
              "variable": [
                {
                  "id": "id",
                  "value": "id",
                  "type": "string"
                }
              ]
            },
            "method": "POST",
            "header": [
              {
                "key": "Authorization",
                "value": "Authorization",
                "description": "Bearer",
                "disabled": false
              },
              {
                "key": "Content-Type",
                "value": "Content-Type",
                "description": "Nature of the data in the body of an entity",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Add attachment Use this API to add an attachment to an event. Since there is currently a limit of 4MB on the total size of each REST request, this limits the size of the attachment you can add to under 4MB."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "8303a542-937f-40bc-9189-cc91614380e6"
            }
          ]
        },
        {
          "id": "03f63c82-520c-4306-9a9a-d0b60d5469d4",
          "name": "AddAttachment5",
          "request": {
            "url": {
              "protocol": "http",
              "host": "graph.microsoft.com",
              "path": [
                "me/calendars/:id/events/:id/attachments"
              ],
              "variable": [
                {
                  "id": "id",
                  "value": "id",
                  "type": "string"
                }
              ]
            },
            "method": "POST",
            "header": [
              {
                "key": "Authorization",
                "value": "Authorization",
                "description": "Bearer",
                "disabled": false
              },
              {
                "key": "Content-Type",
                "value": "Content-Type",
                "description": "Nature of the data in the body of an entity",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Add attachment Use this API to add an attachment to an event. Since there is currently a limit of 4MB on the total size of each REST request, this limits the size of the attachment you can add to under 4MB."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "72c0a2b3-78f1-4595-b743-66f7cffca081"
            }
          ]
        },
        {
          "id": "21cf7d51-272e-40df-b447-1640dad2fb38",
          "name": "AddAttachment3",
          "request": {
            "url": {
              "protocol": "http",
              "host": "graph.microsoft.com",
              "path": [
                "users/:id | userPrincipalName/calendars/:id/events/:id/attachments"
              ],
              "variable": [
                {
                  "id": "id",
                  "value": "id",
                  "type": "string"
                },
                {
                  "id": "id | userPrincipalName",
                  "value": "id | userPrincipalName",
                  "type": "string"
                }
              ]
            },
            "method": "POST",
            "header": [
              {
                "key": "Authorization",
                "value": "Authorization",
                "description": "Bearer",
                "disabled": false
              },
              {
                "key": "Content-Type",
                "value": "Content-Type",
                "description": "Nature of the data in the body of an entity",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Add attachment Use this API to add an attachment to an event. Since there is currently a limit of 4MB on the total size of each REST request, this limits the size of the attachment you can add to under 4MB."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "a198ac90-6eb0-4108-a1c3-c886ffebacae"
            }
          ]
        },
        {
          "id": "21e94881-ea88-4c72-bf65-55b4ab2fad8d",
          "name": "AddAttachment6",
          "request": {
            "url": {
              "protocol": "http",
              "host": "graph.microsoft.com",
              "path": [
                "me/calendargroup/calendars/:id/events/:id/attachments"
              ],
              "variable": [
                {
                  "id": "id",
                  "value": "id",
                  "type": "string"
                }
              ]
            },
            "method": "POST",
            "header": [
              {
                "key": "Authorization",
                "value": "Authorization",
                "description": "Bearer",
                "disabled": false
              },
              {
                "key": "Content-Type",
                "value": "Content-Type",
                "description": "Nature of the data in the body of an entity",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Add attachment Use this API to add an attachment to an event. Since there is currently a limit of 4MB on the total size of each REST request, this limits the size of the attachment you can add to under 4MB."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "62485f2c-ba52-4b91-8899-cfe217f3145c"
            }
          ]
        },
        {
          "id": "93f86c5f-5069-4cb2-939a-6dfcb550bb18",
          "name": "AddAttachment4",
          "request": {
            "url": {
              "protocol": "http",
              "host": "graph.microsoft.com",
              "path": [
                "users/:id | userPrincipalName/calendargroup/calendars/:id/events/:id/attachments"
              ],
              "variable": [
                {
                  "id": "id",
                  "value": "id",
                  "type": "string"
                },
                {
                  "id": "id | userPrincipalName",
                  "value": "id | userPrincipalName",
                  "type": "string"
                }
              ]
            },
            "method": "POST",
            "header": [
              {
                "key": "Authorization",
                "value": "Authorization",
                "description": "Bearer",
                "disabled": false
              },
              {
                "key": "Content-Type",
                "value": "Content-Type",
                "description": "Nature of the data in the body of an entity",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Add attachment Use this API to add an attachment to an event. Since there is currently a limit of 4MB on the total size of each REST request, this limits the size of the attachment you can add to under 4MB."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "d1f9bd41-46cc-4bb8-8d46-e2a650175a75"
            }
          ]
        },
        {
          "id": "86c19e69-4d66-4e10-af8a-e950b3b47758",
          "name": "AddAttachment7",
          "request": {
            "url": {
              "protocol": "http",
              "host": "graph.microsoft.com",
              "path": [
                "me/calendargroups/:id/calendars/:id/events/:id/attachments"
              ],
              "variable": [
                {
                  "id": "id",
                  "value": "id",
                  "type": "string"
                }
              ]
            },
            "method": "POST",
            "header": [
              {
                "key": "Authorization",
                "value": "Authorization",
                "description": "Bearer",
                "disabled": false
              },
              {
                "key": "Content-Type",
                "value": "Content-Type",
                "description": "Nature of the data in the body of an entity",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Add attachment Use this API to add an attachment to an event. Since there is currently a limit of 4MB on the total size of each REST request, this limits the size of the attachment you can add to under 4MB."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "70d48768-14b9-4804-88ba-73cda9fa37dd"
            }
          ]
        },
        {
          "id": "a49e8f72-6576-4e51-987c-99561fc96232",
          "name": "AddAttachment5",
          "request": {
            "url": {
              "protocol": "http",
              "host": "graph.microsoft.com",
              "path": [
                "users/:id | userPrincipalName/calendargroups/:id/calendars/:id/events/:id/attachments"
              ],
              "variable": [
                {
                  "id": "id",
                  "value": "id",
                  "type": "string"
                },
                {
                  "id": "id | userPrincipalName",
                  "value": "id | userPrincipalName",
                  "type": "string"
                }
              ]
            },
            "method": "POST",
            "header": [
              {
                "key": "Authorization",
                "value": "Authorization",
                "description": "Bearer",
                "disabled": false
              },
              {
                "key": "Content-Type",
                "value": "Content-Type",
                "description": "Nature of the data in the body of an entity",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Add attachment Use this API to add an attachment to an event. Since there is currently a limit of 4MB on the total size of each REST request, this limits the size of the attachment you can add to under 4MB."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "c576e74d-704f-4a4b-ad7e-2cce4c9eaf98"
            }
          ]
        },
        {
          "id": "9ef7b700-27d8-4ddd-8563-feaf5aa22e46",
          "name": "AddAttachment8",
          "request": {
            "url": {
              "protocol": "http",
              "host": "graph.microsoft.com",
              "path": [
                "me/messages/:id/attachments"
              ],
              "variable": [
                {
                  "id": "id",
                  "value": "id",
                  "type": "string"
                }
              ]
            },
            "method": "POST",
            "header": [
              {
                "key": "Authorization",
                "value": "Authorization",
                "description": "Bearer",
                "disabled": false
              },
              {
                "key": "Content-Type",
                "value": "Content-Type",
                "description": "Nature of the data in the body of an entity",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Add attachment Use this API to add an attachment to a message."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "b5328480-c6a5-4295-b59b-dc43d09deccc"
            }
          ]
        },
        {
          "id": "1a2f14e9-9725-4955-8464-26063d5cf3ba",
          "name": "AddAttachment6",
          "request": {
            "url": {
              "protocol": "http",
              "host": "graph.microsoft.com",
              "path": [
                "users/:id | userPrincipalName/messages/:id/attachments"
              ],
              "variable": [
                {
                  "id": "id",
                  "value": "id",
                  "type": "string"
                },
                {
                  "id": "id | userPrincipalName",
                  "value": "id | userPrincipalName",
                  "type": "string"
                }
              ]
            },
            "method": "POST",
            "header": [
              {
                "key": "Authorization",
                "value": "Authorization",
                "description": "Bearer",
                "disabled": false
              },
              {
                "key": "Content-Type",
                "value": "Content-Type",
                "description": "Nature of the data in the body of an entity",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Add attachment Use this API to add an attachment to a message."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "034e3630-129d-44b2-801a-696de1832fb7"
            }
          ]
        },
        {
          "id": "a45d1f6c-5da5-42d9-8144-d4652414dc07",
          "name": "AddAttachment9",
          "request": {
            "url": {
              "protocol": "http",
              "host": "graph.microsoft.com",
              "path": [
                "me/mailFolders/:id/messages/:id/attachments"
              ],
              "variable": [
                {
                  "id": "id",
                  "value": "id",
                  "type": "string"
                }
              ]
            },
            "method": "POST",
            "header": [
              {
                "key": "Authorization",
                "value": "Authorization",
                "description": "Bearer",
                "disabled": false
              },
              {
                "key": "Content-Type",
                "value": "Content-Type",
                "description": "Nature of the data in the body of an entity",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Add attachment Use this API to add an attachment to a message."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "f6fb0798-2b19-4db7-ae4e-48dc42965910"
            }
          ]
        },
        {
          "id": "5f6f23f2-7d10-40bc-926c-3994930aeb03",
          "name": "AddAttachment7",
          "request": {
            "url": {
              "protocol": "http",
              "host": "graph.microsoft.com",
              "path": [
                "users/:id | userPrincipalName/mailFolders/:id/messages/:id/attachments"
              ],
              "variable": [
                {
                  "id": "id",
                  "value": "id",
                  "type": "string"
                },
                {
                  "id": "id | userPrincipalName",
                  "value": "id | userPrincipalName",
                  "type": "string"
                }
              ]
            },
            "method": "POST",
            "header": [
              {
                "key": "Authorization",
                "value": "Authorization",
                "description": "Bearer",
                "disabled": false
              },
              {
                "key": "Content-Type",
                "value": "Content-Type",
                "description": "Nature of the data in the body of an entity",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Add attachment Use this API to add an attachment to a message."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "a5fa6522-848b-4ae2-9b6e-5644d344a991"
            }
          ]
        },
        {
          "id": "c46932fb-b659-4c6b-bef6-124ed6b9ddbf",
          "name": "AddAttachment",
          "request": {
            "url": {
              "protocol": "http",
              "host": "graph.microsoft.com",
              "path": [
                "groups/:id/threads/:id/posts/:id/attachments"
              ],
              "variable": [
                {
                  "id": "id",
                  "value": "id",
                  "type": "string"
                }
              ]
            },
            "method": "POST",
            "header": [
              {
                "key": "Authorization",
                "value": "{}",
                "description": "Bearer",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Add attachment Use this API to add an attachment to a post. Since there is currently a limit of 4MB on the total size of each REST request, this limits the size of the attachment you can add to under 4MB."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "fa692de1-61a7-4fc7-9ce8-f7867b7c1916"
            }
          ]
        },
        {
          "id": "4969fe40-a7af-479a-9ff2-e11a6119d403",
          "name": "AddAttachment1",
          "request": {
            "url": {
              "protocol": "http",
              "host": "graph.microsoft.com",
              "path": [
                "groups/:id/conversations/:id/threads/:id/posts/:id/attachments"
              ],
              "variable": [
                {
                  "id": "id",
                  "value": "id",
                  "type": "string"
                }
              ]
            },
            "method": "POST",
            "header": [
              {
                "key": "Authorization",
                "value": "{}",
                "description": "Bearer",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Add attachment Use this API to add an attachment to a post. Since there is currently a limit of 4MB on the total size of each REST request, this limits the size of the attachment you can add to under 4MB."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "15c2a0a2-fca3-4845-8ceb-284de1b1a584"
            }
          ]
        }
      ]
    },
    {
      "name": "List",
      "item": [
        {
          "id": "561db1f9-65ca-4db0-8a17-9a9c030c6f1b",
          "name": "ListAttachments",
          "request": {
            "url": {
              "protocol": "http",
              "host": "graph.microsoft.com",
              "path": [
                "me/mailFolders/:id/childFolders/:id/.../messages/:id/attachments/:id"
              ],
              "variable": [
                {
                  "id": "id",
                  "value": "id",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "header": [
              {
                "key": "Authorization",
                "value": "Authorization",
                "description": "Bearer",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "List attachments Retrieve a list of attachment objects attached to a message."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "4df992ed-d567-4fc2-8612-8324cbd0af37"
            }
          ]
        },
        {
          "id": "770ba476-2f2f-4e1e-a8cf-f46d46f5f6cd",
          "name": "ListAttachments",
          "request": {
            "url": {
              "protocol": "http",
              "host": "graph.microsoft.com",
              "path": [
                "users/:id | userPrincipalName/mailFolders/:id/childFolders/:id/messages/:id/attachments/:id"
              ],
              "variable": [
                {
                  "id": "id",
                  "value": "id",
                  "type": "string"
                },
                {
                  "id": "id | userPrincipalName",
                  "value": "id | userPrincipalName",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "header": [
              {
                "key": "Authorization",
                "value": "Authorization",
                "description": "Bearer",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "List attachments Retrieve a list of attachment objects attached to a message."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "69fad1a5-d43d-4644-ab54-d2d9a2047020"
            }
          ]
        },
        {
          "id": "fa1eff5c-5f2d-4075-bf11-0dfe8aa36fa6",
          "name": "ListCalendarView",
          "request": {
            "url": "http://graph.microsoft.com/me/calendar/calendarView?endDateTime=endDateTime&startDateTime=startDateTime",
            "method": "GET",
            "header": [
              {
                "key": "Authorization",
                "value": "Authorization",
                "description": "Bearer",
                "disabled": false
              },
              {
                "key": "Content-Type",
                "value": "Content-Type",
                "description": "application/json",
                "disabled": false
              },
              {
                "key": "Prefer",
                "value": "Prefer",
                "description": "",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "List calendarView\nGet the occurrences, exceptions, and single instances of events in a calendar view defined by a time range,\nfrom the default calendar (../me/calendarview) of a user or group, or some other calendar of the user's."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "31d1c990-863d-4828-9894-fcef6fe35a1c"
            }
          ]
        },
        {
          "id": "6080102e-0c56-4220-9a3d-405ed613798a",
          "name": "ListCalendarView",
          "request": {
            "url": {
              "protocol": "http",
              "host": "graph.microsoft.com",
              "path": [
                "users/:id | userPrincipalName/calendar/calendarView"
              ],
              "query": [
                {
                  "key": "endDateTime",
                  "value": "endDateTime",
                  "disabled": false
                },
                {
                  "key": "startDateTime",
                  "value": "startDateTime",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "id | userPrincipalName",
                  "value": "id | userPrincipalName",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "header": [
              {
                "key": "Authorization",
                "value": "{}",
                "description": "Bearer",
                "disabled": false
              },
              {
                "key": "Prefer",
                "value": "{}",
                "description": "outlook",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "List calendarView\nGet the occurrences, exceptions, and single instances of events in a calendar view defined by a time range,\nfrom the default calendar (../me/calendarview) of a user or group, or some other calendar of the user's."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "05c17aa3-8179-4c54-b64b-4d36ea0e30f6"
            }
          ]
        },
        {
          "id": "fb23c653-1b8f-44fa-afbd-d6f426c066c8",
          "name": "ListCalendarView",
          "request": {
            "url": {
              "protocol": "http",
              "host": "graph.microsoft.com",
              "path": [
                "groups/:id/calendar/calendarView"
              ],
              "query": [
                {
                  "key": "endDateTime",
                  "value": "endDateTime",
                  "disabled": false
                },
                {
                  "key": "startDateTime",
                  "value": "startDateTime",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "id",
                  "value": "id",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "header": [
              {
                "key": "Authorization",
                "value": "{}",
                "description": "Bearer",
                "disabled": false
              },
              {
                "key": "Prefer",
                "value": "{}",
                "description": "outlook",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "List calendarView\nGet the occurrences, exceptions, and single instances of events in a calendar view defined by a time range,\nfrom the default calendar (../me/calendarview) of a user or group, or some other calendar of the user's."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "0d443286-a5b0-419e-a0c5-80318a494388"
            }
          ]
        },
        {
          "id": "55f30fd6-44b7-4c34-8289-9b75b2579f22",
          "name": "ListCalendarView",
          "request": {
            "url": {
              "protocol": "http",
              "host": "graph.microsoft.com",
              "path": [
                "me/calendars/:id/calendarView"
              ],
              "query": [
                {
                  "key": "endDateTime",
                  "value": "endDateTime",
                  "disabled": false
                },
   