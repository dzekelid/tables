swagger: "2.0"
x-collection-name: Dezrez
x-complete: 1
info:
  title: Dezrez.Rezi.Client.Api
  version: 1.0.0
host: api.dezrez.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /api/accountingsystem:
    get:
      summary: Gets accounting system for a legal entity
      description: Gets accounting system for a legal entity.
      operationId: AccountingSystem_Get
      x-api-path-slug: apiaccountingsystem-get
      parameters:
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - S
      - Accounting
      - Systema
      - Legal
      - Entity
  /api/enum:
    get:
      summary: "Returns a list of possible values for an enum if you just specify
        {typeName}.\r\nReturns a an enum if you specify {typeName} and {systemName}."
      description: "Returns a list of possible values for an enum if you just specify
        {typename}.\r\nreturns a an enum if you specify {typename} and {systemname}.."
      operationId: Enum_GetBytypeNameBysystemNameByeventCategoryType
      x-api-path-slug: apienum-get
      parameters:
      - in: query
        name: eventCategoryType
        description: Where the enum has values which are categorised, this filters
          on that category
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      - in: query
        name: systemName
        description: The system name of the enum to get
      - in: query
        name: typeName
        description: The type of enum to get
      responses:
        200:
          description: OK
      tags:
      - Returns
      - List
      - Of
      - Possible
      - Valuesan
      - Enum
      - If
      - You
      - Just
      - Specify
      - TypeName
      - Returns
      - Enum
      - If
      - You
      - Specify
      - TypeName
      - SystemName
  /api/branch/updatescheduledtaskstatus/{id}:
    post:
      summary: Update SystemStatus of ScheduledTask to Active, Inactive, Deleted or
        Archived.
      description: Update systemstatus of scheduledtask to active, inactive, deleted
        or archived..
      operationId: Branch_UpdateScheduledTaskStatusByidBysystemStatus
      x-api-path-slug: apibranchupdatescheduledtaskstatusid-post
      parameters:
      - in: path
        name: id
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      - in: query
        name: systemStatus
      responses:
        200:
          description: OK
      tags:
      - SystemStatus
      - Of
      - ScheduledTask
      - To
      - Active
      - ""
      - Inactive
      - ""
      - D
      - Archived
  /api/account/createsystemaccount:
    post:
      summary: Create a new System account eg. new client account
      description: Create a new system account eg. new client account.
      operationId: Account_CreateSystemAccountBydataContract
      x-api-path-slug: apiaccountcreatesystemaccount-post
      parameters:
      - in: body
        name: dataContract
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - New
      - System
      - Account
      - Eg
      - ""
      - New
      - Client
      - Account
  /api/account/systemaccounts:
    get:
      summary: Get list of all system accounts
      description: Get list of all system accounts.
      operationId: Account_GetSystemAccounts
      x-api-path-slug: apiaccountsystemaccounts-get
      parameters:
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - List
      - Of
      - ""
      - System
      - Accounts
  /api/account/systemaccount:
    get:
      summary: Get System Account for the Accounting System
      description: Get system account for the accounting system.
      operationId: Account_GetSystemAccount
      x-api-path-slug: apiaccountsystemaccount-get
      parameters:
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - System
      - Accountthe
      - Accounting
      - System
  /api/accountingsystem/systembalance:
    get:
      summary: Gets accounting system balance
      description: Gets accounting system balance.
      operationId: AccountingSystem_GetSystemBalance
      x-api-path-slug: apiaccountingsystemsystembalance-get
      parameters:
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - S
      - Accounting
      - System
      - Balance
    put:
      summary: Archives the accounting system
      description: Archives the accounting system.
      operationId: AccountingSystem_ArchiveSystemByforce
      x-api-path-slug: apiaccountingsystemsystembalance-put
      parameters:
      - in: query
        name: force
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - Archives
      - Accounting
      - System
  /api/accountingsystem/taxstatus:
    get:
      summary: Get Tax Status of Accounting System
      description: Get tax status of accounting system.
      operationId: AccountingSystem_GetTaxStatus
      x-api-path-slug: apiaccountingsystemtaxstatus-get
      parameters:
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - Tax
      - Status
      - Of
      - Accounting
      - System
  /api/accountingsystem/suspense:
    get:
      summary: Get amount of funds held in suspense account of the accounting system
      description: Get amount of funds held in suspense account of the accounting
        system.
      operationId: AccountingSystem_GetSuspenseFunds
      x-api-path-slug: apiaccountingsystemsuspense-get
      parameters:
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - Amount
      - Of
      - Funds
      - Held
      - In
      - Suspense
      - Account
      - Of
      - Accounting
      - System
  /api/accountingsystem/createofficeaccount:
    post:
      summary: Create an office account for the accounting system
      description: Create an office account for the accounting system.
      operationId: AccountingSystem_CreateOfficeAccountBydataContract
      x-api-path-slug: apiaccountingsystemcreateofficeaccount-post
      parameters:
      - in: body
        name: dataContract
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - Office
      - Accountthe
      - Accounting
      - System
  /api/accountingsystem/officeaccounts:
    get:
      summary: Get list of office accounts associated with the accounting system
      description: Get list of office accounts associated with the accounting system.
      operationId: AccountingSystem_GetOfficeAccounts
      x-api-path-slug: apiaccountingsystemofficeaccounts-get
      parameters:
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - List
      - Of
      - Office
      - Accounts
      - Associated
      - Accounting
      - System
  /api/accountingsystem/setprimaryaccount:
    post:
      summary: Set Primary Bank Account for Accounting System
      description: Set primary bank account for accounting system.
      operationId: AccountingSystem_SetPrimarySystemBankAccountByid
      x-api-path-slug: apiaccountingsystemsetprimaryaccount-post
      parameters:
      - in: query
        name: id
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - Set
      - Primary
      - Bank
      - AccountAccounting
      - System
  /api/cache/{itemKey}:
    get:
      summary: Retrieves an object stored in the cache system by its {itemKey}
      description: Retrieves an object stored in the cache system by its {itemkey}.
      operationId: Cache_GetObjectByitemKey
      x-api-path-slug: apicacheitemkey-get
      parameters:
      - in: path
        name: itemKey
        description: The item key
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - Retrieves
      - Object
      - Stored
      - In
      - Cache
      - System
      - By
      - Its
      - ItemKey
  /api/cache/List/{listKey}:
    get:
      summary: Retrieves a list of objects stored in the cache system by its {listKey}
      description: Retrieves a list of objects stored in the cache system by its {listkey}.
      operationId: Cache_GetListBylistKey
      x-api-path-slug: apicachelistlistkey-get
      parameters:
      - in: path
        name: listKey
        description: The list key
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - Retrieves
      - List
      - Of
      - Objects
      - Stored
      - In
      - Cache
      - System
      - By
      - Its
      - ListKey
  /api/coreplatformstate/platformissue:
    post:
      summary: Allows business workflows to post system issues to the platform state
        service.
      description: Allows business workflows to post system issues to the platform
        state service..
      operationId: CorePlatformState_PostPlatformIssueByalertDataContract
      x-api-path-slug: apicoreplatformstateplatformissue-post
      parameters:
      - in: body
        name: alertDataContract
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - Allows
      - Business
      - Workflows
      - To
      - Post
      - System
      - Issues
      - To
      - Platform
      - State
      - Service
  /api/documentgeneration/targetgroups:
    get:
      summary: Get an enum by its type and system name
      description: Get an enum by its type and system name.
      operationId: DocumentGeneration_TargetGroups
      x-api-path-slug: apidocumentgenerationtargetgroups-get
      parameters:
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - Enum
      - By
      - Its
      - Type
      - System
      - Name
  /api/enum/marketingrolestatus:
    get:
      summary: Get an enum by its type and system name
      description: Get an enum by its type and system name.
      operationId: Enum_GetMarketingRoleStatusBytransactionType
      x-api-path-slug: apienummarketingrolestatus-get
      parameters:
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      - in: query
        name: transactionType
        description: The typeo of marketingrole to get
      responses:
        200:
          description: OK
      tags:
      - Enum
      - By
      - Its
      - Type
      - System
      - Name
  /api/fee/save:
    post:
      summary: Save a new fee into the system
      description: Save a new fee into the system.
      operationId: Fee_SaveFeeByfeeDataContract
      x-api-path-slug: apifeesave-post
      parameters:
      - in: body
        name: feeDataContract
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - Save
      - New
      - Fee
      - Into
      - System
  /api/globalsearch/people:
    get:
      summary: Search for People across the system.
      description: Search for people across the system..
      operationId: GlobalSearch_PeopleBydataContract.termBydataContract.pageSizeBydataContract.pageNumberBydataContract
      x-api-path-slug: apiglobalsearchpeople-get
      parameters:
      - in: query
        name: dataContract.branchId
      - in: query
        name: dataContract.excludeArchived
      - in: query
        name: dataContract.excludeDeleted
      - in: query
        name: dataContract.groupTypes
      - in: query
        name: dataContract.lastUpdated
      - in: query
        name: dataContract.pageNumber
      - in: query
        name: dataContract.pageSize
      - in: query
        name: dataContract.serviceType
      - in: query
        name: dataContract.term
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - SearchPeople
      - Across
      - System
  /api/globalsearch/properties:
    get:
      summary: Search for Properties across the system.
      description: Search for properties across the system..
      operationId: GlobalSearch_PropertiesBydataContract.termBydataContract.pageSizeBydataContract.pageNumberBydataCont
      x-api-path-slug: apiglobalsearchproperties-get
      parameters:
      - in: query
        name: dataContract.branchId
      - in: query
        name: dataContract.excludeArchived
      - in: query
        name: dataContract.excludeDeleted
      - in: query
        name: dataContract.groupTypes
      - in: query
        name: dataContract.lastUpdated
      - in: query
        name: dataContract.pageNumber
      - in: query
        name: dataContract.pageSize
      - in: query
        name: dataContract.serviceType
      - in: query
        name: dataContract.term
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - SearchProperties
      - Across
      - System
  /api/globalsearch/groups:
    get:
      summary: Search for Groups across the system.
      description: Search for groups across the system..
      operationId: GlobalSearch_GroupsBydataContract.termBydataContract.pageSizeBydataContract.pageNumberBydataContract
      x-api-path-slug: apiglobalsearchgroups-get
      parameters:
      - in: query
        name: dataContract.branchId
      - in: query
        name: dataContract.excludeArchived
      - in: query
        name: dataContract.excludeDeleted
      - in: query
        name: dataContract.groupTypes
      - in: query
        name: dataContract.lastUpdated
      - in: query
        name: dataContract.pageNumber
      - in: query
        name: dataContract.pageSize
      - in: query
        name: dataContract.serviceType
      - in: query
        name: dataContract.term
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - SearchGroups
      - Across
      - System
  /api/globalsearch/auctions:
    get:
      summary: Search for Actions across the system.
      description: Search for actions across the system..
      operationId: GlobalSearch_AuctionsBydataContract.termBydataContract.pageSizeBydataContract.pageNumberBydataContra
      x-api-path-slug: apiglobalsearchauctions-get
      parameters:
      - in: query
        name: dataContract.branchId
      - in: query
        name: dataContract.excludeArchived
      - in: query
        name: dataContract.excludeDeleted
      - in: query
        name: dataContract.groupTypes
      - in: query
        name: dataContract.lastUpdated
      - in: query
        name: dataContract.pageNumber
      - in: query
        name: dataContract.pageSize
      - in: query
        name: dataContract.serviceType
      - in: query
        name: dataContract.term
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - SearchActions
      - Across
      - System
  /api/GlobalSearch:
    get:
      summary: The main endpoint for a global search across all entities in the system.
      description: The main endpoint for a global search across all entities in the
        system..
      operationId: GlobalSearch_IndexBytermByexcludeDeletedByexcludeArchivedBylastUpdated
      x-api-path-slug: apiglobalsearch-get
      parameters:
      - in: query
        name: excludeArchived
      - in: query
        name: excludeDeleted
      - in: query
        name: lastUpdated
        description: Get results from the last updated date
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      - in: query
        name: term
        description: Search term
      responses:
        200:
          description: OK
      tags:
      - The
      - Main
      - Endpointa
      - Global
      - Search
      - Across
      - ""
      - Entities
      - In
      - System
  /api/group/basicapplicantheatmap:
    get:
      summary: Return the lat and longs for every applicant in the system
      description: Return the lat and longs for every applicant in the system.
      operationId: Group_BasicApplicantHeatMapBypageSizeByfilter.rangeFromByfilter.rangeToByfilter.branchIdByfilter.rol
      x-api-path-slug: apigroupbasicapplicantheatmap-get
      parameters:
      - in: query
        name: filter.branchId
      - in: query
        name: filter.rangeFrom
      - in: query
        name: filter.rangeTo
      - in: query
        name: filter.roleTypes
      - in: query
        name: pageSize
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - Return
      - Lat
      - Longsevery
      - Applicant
      - In
      - System
  /api/group/{id}/setgroupmemberstatus:
    put:
      summary: Sets members Active/Inactive system status
      description: Sets members active/inactive system status.
      operationId: Group_SetGroupMemberStatusByidBygroupMemberStatusDataContract
      x-api-path-slug: apigroupidsetgroupmemberstatus-put
      parameters:
      - in: body
        name: groupMemberStatusDataContract
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: id
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - Sets
      - Members
      - Active
      - Inactive
      - System
      - Status
  /api/inboundlead/create:
    post:
      summary: Creates a lead in the system, optinally assigning the lead to a negotiator
      description: Creates a lead in the system, optinally assigning the lead to a
        negotiator.
      operationId: InboundLead_CreateLeadBydataContractByassignToNegId
      x-api-path-slug: apiinboundleadcreate-post
      parameters:
      - in: query
        name: assignToNegId
        description: Negotiator Id to assign lead too
      - in: body
        name: dataContract
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - Creates
      - Lead
      - In
      - System
      - ""
      - Optinally
      - Assigning
      - Lead
      - To
      - Negotiator
  /api/posting/uncleared:
    post:
      summary: Get uncleared items in accounting system
      description: Get uncleared items in accounting system.
      operationId: Posting_GetUnclearedItemsByunclearedItemsDataContract
      x-api-path-slug: apipostinguncleared-post
      parameters:
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      - in: body
        name: unclearedItemsDataContract
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Uncleared
      - Items
      - In
      - Accounting
      - System
  /api/receipt/agentdeposit:
    post:
      summary: Add agent funds into the system
      description: Add agent funds into the system.
      operationId: Receipt_ReceiptAgentDepositByagentDepositDataContract
      x-api-path-slug: apireceiptagentdeposit-post
      parameters:
      - in: body
        name: agentDepositDataContract
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - Agent
      - Funds
      - Into
      - System
  /api/admin/system/CreateNewSystemFeature:
    post:
      summary: Creates a new system wide feature available for activation.
      description: Creates a new system wide feature available for activation..
      operationId: System_CreateNewSystemFeatureBysaveNewFeatureCommad
      x-api-path-slug: apiadminsystemcreatenewsystemfeature-post
      parameters:
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      - in: body
        name: saveNewFeatureCommad
        description: The save new feature commad
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Creates
      - New
      - System
      - Wide
      - Feature
      - Availableactivation
  /api/admin/system/ListAgencies:
    get:
      summary: Lists the name and ID of all agencies in the system.
      description: Lists the name and id of all agencies in the system..
      operationId: System_ListAgenciesByincludeSuspended
      x-api-path-slug: apiadminsystemlistagencies-get
      parameters:
      - in: query
        name: includeSuspended
        description: if set to true [include suspended]
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - Lists
      - Name
      - ID
      - Of
      - ""
      - Agencies
      - In
      - System
  /api/tax/{id}/setasdefault:
    post:
      summary: Set default tax rate for the accounting system
      description: Set default tax rate for the accounting system.
      operationId: Tax_SetDefaultTaxRateByid
      x-api-path-slug: apitaxidsetasdefault-post
      parameters:
      - in: path
        name: id
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - Set
      - Default
      - Tax
      - Ratethe
      - Accounting
      - System
  /api/tax/create:
    post:
      summary: Create a new tax rate for the system
      description: Create a new tax rate for the system.
      operationId: Tax_CreateTaxRateBytaxRateDataContract
      x-api-path-slug: apitaxcreate-post
      parameters:
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      - in: body
        name: taxRateDataContract
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - New
      - Tax
      - Ratethe
      - System
  /api/webhook/create/{triggerName}:
    post:
      summary: Creates a new webhook in the system (scoped to agency)
      description: Creates a new webhook in the system (scoped to agency).
      operationId: Webhook_CreateWebhookBytriggerNameBycreateWebhookRequest
      x-api-path-slug: apiwebhookcreatetriggername-post
      parameters:
      - in: body
        name: createWebhookRequest
        description: Webhook callback details
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      - in: path
        name: triggerName
        description: Name of the trigger
      responses:
        200:
          description: OK
      tags:
      - Creates
      - New
      - Webhook
      - In
      - System
      - (scoped
      - To
      - Agency)