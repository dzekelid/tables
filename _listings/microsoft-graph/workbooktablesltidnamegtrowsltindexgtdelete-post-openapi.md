---
swagger: "2.0"
x-collection-name: Microsoft Graph
x-complete: 0
info:
  title: Microsoft Graph Table Row Delete
  description: 'TableRow: delete Deletes the row from the table.'
  version: 1.0.0
host: graph.microsoft.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /workbook/tables(&lt;id|name&gt;)/clearFilters:
    post:
      summary: Table Clear Filters
      description: 'Table: clearFilters Clears all the filters currently applied on
        the table.'
      operationId: Table:ClearFilters
      x-api-path-slug: workbooktablesltidnamegtclearfilters-post
      parameters:
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - Table
      - Clear
      - Filters
  /workbook/worksheets(&lt;id|name&gt;)/tables(&lt;id|name&gt;)/clearFilters:
    post:
      summary: Table Clear Filters
      description: 'Table: clearFilters Clears all the filters currently applied on
        the table.'
      operationId: Table:ClearFilters
      x-api-path-slug: workbookworksheetsltidnamegttablesltidnamegtclearfilters-post
      parameters:
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - Table
      - Clear
      - Filters
  /workbook/tables(&lt;id|name&gt;)/convertToRange:
    post:
      summary: Table Convert To Range
      description: 'Table: convertToRange Converts the table into a normal range of
        cells. All data is preserved.'
      operationId: Table:ConvertToRange
      x-api-path-slug: workbooktablesltidnamegtconverttorange-post
      parameters:
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - Table
      - ConvertRange
  /workbook/worksheets(&lt;id|name&gt;)/tables(&lt;id|name&gt;)/convertToRange:
    post:
      summary: Table Convert To Range
      description: 'Table: convertToRange Converts the table into a normal range of
        cells. All data is preserved.'
      operationId: Table:ConvertToRange
      x-api-path-slug: workbookworksheetsltidnamegttablesltidnamegtconverttorange-post
      parameters:
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - Table
      - ConvertRange
  /workbook/tables(&lt;id|name&gt;)/DataBodyRange:
    post:
      summary: Table Data Body Range
      description: 'Table: DataBodyRange Gets the range object associated with the
        data body of the table.'
      operationId: Table:DataBodyRange
      x-api-path-slug: workbooktablesltidnamegtdatabodyrange-post
      parameters:
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - Table
      - Data
      - Body
      - Range
  /workbook/worksheets(&lt;id|name&gt;)/tables(&lt;id|name&gt;)/DataBodyRange:
    post:
      summary: Table Data Body Range
      description: 'Table: DataBodyRange Gets the range object associated with the
        data body of the table.'
      operationId: Table:DataBodyRange
      x-api-path-slug: workbookworksheetsltidnamegttablesltidnamegtdatabodyrange-post
      parameters:
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - Table
      - Data
      - Body
      - Range
  /workbook/tables(&lt;id|name&gt;)/delete:
    post:
      summary: Table Delete
      description: 'Table: delete Deletes the table.'
      operationId: Table:Delete
      x-api-path-slug: workbooktablesltidnamegtdelete-post
      parameters:
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - Table
  /workbook/worksheets(&lt;id|name&gt;)/tables(&lt;id|name&gt;)/delete:
    post:
      summary: Table Delete
      description: 'Table: delete Deletes the table.'
      operationId: Table:Delete
      x-api-path-slug: workbookworksheetsltidnamegttablesltidnamegtdelete-post
      parameters:
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - Table
  /workbook/tables(&lt;id|name&gt;):
    get:
      summary: Get Table
      description: Get Table Retrieve the properties and relationships of table object.
      operationId: GetTable
      x-api-path-slug: workbooktablesltidnamegt-get
      parameters:
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - Table
    patch:
      summary: Update Table
      description: Update table Update the properties of table object.
      operationId: UpdateTable
      x-api-path-slug: workbooktablesltidnamegt-patch
      parameters:
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - Table
  /workbook/worksheets(&lt;id|name&gt;)/tables(&lt;id|name&gt;):
    get:
      summary: Get Table
      description: Get Table Retrieve the properties and relationships of table object.
      operationId: GetTable
      x-api-path-slug: workbookworksheetsltidnamegttablesltidnamegt-get
      parameters:
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - Table
    patch:
      summary: Update Table
      description: Update table Update the properties of table object.
      operationId: UpdateTable
      x-api-path-slug: workbookworksheetsltidnamegttablesltidnamegt-patch
      parameters:
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - Table
  /workbook/tables(&lt;id|name&gt;)/HeaderRowRange:
    post:
      summary: Table Header Row Range
      description: 'Table: HeaderRowRange Gets the range object associated with header
        row of the table.'
      operationId: Table:HeaderRowRange
      x-api-path-slug: workbooktablesltidnamegtheaderrowrange-post
      parameters:
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - Table
      - Header
      - Row
      - Range
  /workbook/worksheets(&lt;id|name&gt;)/tables(&lt;id|name&gt;)/HeaderRowRange:
    post:
      summary: Table Header Row Range
      description: 'Table: HeaderRowRange Gets the range object associated with header
        row of the table.'
      operationId: Table:HeaderRowRange
      x-api-path-slug: workbookworksheetsltidnamegttablesltidnamegtheaderrowrange-post
      parameters:
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - Table
      - Header
      - Row
      - Range
  /workbook/tables:
    get:
      summary: List Table Collection
      description: List TableCollection Retrieve a list of table objects.
      operationId: ListTableCollection
      x-api-path-slug: workbooktables-get
      parameters:
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - List
      - Table
      - Collection
  /workbook/worksheets(&lt;id|name&gt;)/tables:
    get:
      summary: List Table Collection
      description: List TableCollection Retrieve a list of table objects.
      operationId: ListTableCollection
      x-api-path-slug: workbookworksheetsltidnamegttables-get
      parameters:
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - List
      - Table
      - Collection
  /workbook/tables(&lt;id|name&gt;)/columns:
    post:
      summary: Create Table Column
      description: Create TableColumn Use this API to create a new TableColumn.
      operationId: CreateTableColumn
      x-api-path-slug: workbooktablesltidnamegtcolumns-post
      parameters:
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - Table
      - Column
  /workbook/worksheets(&lt;id|name&gt;)/tables(&lt;id|name&gt;)/columns:
    post:
      summary: Create Table Column
      description: Create TableColumn Use this API to create a new TableColumn.
      operationId: CreateTableColumn
      x-api-path-slug: workbookworksheetsltidnamegttablesltidnamegtcolumns-post
      parameters:
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - Table
      - Column
  /workbook/tables(&lt;id|name&gt;)/rows:
    post:
      summary: Create Table Row
      description: Create TableRow Use this API to create a new TableRow.
      operationId: CreateTableRow
      x-api-path-slug: workbooktablesltidnamegtrows-post
      parameters:
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - Table
      - Row
  /workbook/worksheets(&lt;id|name&gt;)/tables(&lt;id|name&gt;)/rows:
    post:
      summary: Create Table Row
      description: Create TableRow Use this API to create a new TableRow.
      operationId: CreateTableRow
      x-api-path-slug: workbookworksheetsltidnamegttablesltidnamegtrows-post
      parameters:
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - Table
      - Row
  /workbook/tables(&lt;id|name&gt;)/Range:
    post:
      summary: Table Range
      description: 'Table: Range Gets the range object associated with the entire
        table.'
      operationId: Table:Range
      x-api-path-slug: workbooktablesltidnamegtrange-post
      parameters:
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - Table
      - Range
  /workbook/worksheets(&lt;id|name&gt;)/tables(&lt;id|name&gt;)/Range:
    post:
      summary: Table Range
      description: 'Table: Range Gets the range object associated with the entire
        table.'
      operationId: Table:Range
      x-api-path-slug: workbookworksheetsltidnamegttablesltidnamegtrange-post
      parameters:
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - Table
      - Range
  /workbook/tables(&lt;id|name&gt;)/reapplyFilters:
    post:
      summary: Table Reapply Filters
      description: 'Table: reapplyFilters Reapplies all the filters currently on the
        table.'
      operationId: Table:ReapplyFilters
      x-api-path-slug: workbooktablesltidnamegtreapplyfilters-post
      parameters:
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - Table
      - Reapply
      - Filters
  /workbook/worksheets(&lt;id|name&gt;)/tables(&lt;id|name&gt;)/reapplyFilters:
    post:
      summary: Table Reapply Filters
      description: 'Table: reapplyFilters Reapplies all the filters currently on the
        table.'
      operationId: Table:ReapplyFilters
      x-api-path-slug: workbookworksheetsltidnamegttablesltidnamegtreapplyfilters-post
      parameters:
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - Table
      - Reapply
      - Filters
  /workbook/tables(&lt;id|name&gt;)/TotalRowRange:
    post:
      summary: Table Total Row Range
      description: 'Table: TotalRowRange Gets the range object associated with totals
        row of the table.'
      operationId: Table:TotalRowRange
      x-api-path-slug: workbooktablesltidnamegttotalrowrange-post
      parameters:
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - Table
      - Total
      - Row
      - Range
  /workbook/worksheets(&lt;id|name&gt;)/tables(&lt;id|name&gt;)/TotalRowRange:
    post:
      summary: Table Total Row Range
      description: 'Table: TotalRowRange Gets the range object associated with totals
        row of the table.'
      operationId: Table:TotalRowRange
      x-api-path-slug: workbookworksheetsltidnamegttablesltidnamegttotalrowrange-post
      parameters:
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - Table
      - Total
      - Row
      - Range
  /workbook/tables/add:
    post:
      summary: Table Collection Add
      description: 'TableCollection: add Create a new table. The range source address
        determines the worksheet under which the table will be added. If the table
        cannot be added (e.g., because the address is invalid, or the table would
        overlap with another table), an error will be thrown.'
      operationId: TableCollection:Add
      x-api-path-slug: workbooktablesadd-post
      parameters:
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - Table
      - Collection
  /workbook/worksheets(&lt;id|name&gt;)/tables/add:
    post:
      summary: Table Collection Add
      description: 'TableCollection: add Create a new table. The range source address
        determines the worksheet under which the table will be added. If the table
        cannot be added (e.g., because the address is invalid, or the table would
        overlap with another table), an error will be thrown.'
      operationId: TableCollection:Add
      x-api-path-slug: workbookworksheetsltidnamegttablesadd-post
      parameters:
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - Table
      - Collection
  /workbook/tables(&lt;id|name&gt;)/columns(&lt;id|name&gt;)/DataBodyRange:
    post:
      summary: Table Column Data Body Range
      description: 'TableColumn: DataBodyRange Gets the range object associated with
        the data body of the column.'
      operationId: TableColumn:DataBodyRange
      x-api-path-slug: workbooktablesltidnamegtcolumnsltidnamegtdatabodyrange-post
      parameters:
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - Table
      - Column
      - Data
      - Body
      - Range
  /workbook/worksheets(&lt;id|name&gt;)/tables(&lt;id|name&gt;)/columns(&lt;id|name&gt;)/DataBodyRange:
    post:
      summary: Table Column Data Body Range
      description: 'TableColumn: DataBodyRange Gets the range object associated with
        the data body of the column.'
      operationId: TableColumn:DataBodyRange
      x-api-path-slug: workbookworksheetsltidnamegttablesltidnamegtcolumnsltidnamegtdatabodyrange-post
      parameters:
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - Table
      - Column
      - Data
      - Body
      - Range
  /workbook/tables(&lt;id|name&gt;)/columns(&lt;id|name&gt;)/delete:
    post:
      summary: Table Column Delete
      description: 'TableColumn: delete Deletes the column from the table.'
      operationId: TableColumn:Delete
      x-api-path-slug: workbooktablesltidnamegtcolumnsltidnamegtdelete-post
      parameters:
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - Table
      - Column
  /workbook/worksheets(&lt;id|name&gt;)/tables(&lt;id|name&gt;)/columns(&lt;id|name&gt;)/delete:
    post:
      summary: Table Column Delete
      description: 'TableColumn: delete Deletes the column from the table.'
      operationId: TableColumn:Delete
      x-api-path-slug: workbookworksheetsltidnamegttablesltidnamegtcolumnsltidnamegtdelete-post
      parameters:
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - Table
      - Column
  /workbook/tables(&lt;id|name&gt;)/columns(&lt;id|name&gt;):
    get:
      summary: Get Table Column
      description: Get TableColumn Retrieve the properties and relationships of tablecolumn
        object.
      operationId: GetTableColumn
      x-api-path-slug: workbooktablesltidnamegtcolumnsltidnamegt-get
      parameters:
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - Table
      - Column
    patch:
      summary: Update Tablecolumn
      description: Update tablecolumn Update the properties of tablecolumn object.
      operationId: UpdateTablecolumn
      x-api-path-slug: workbooktablesltidnamegtcolumnsltidnamegt-patch
      parameters:
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - Tablecolumn
  /workbook/worksheets(&lt;id|name&gt;)/tables(&lt;id|name&gt;)/columns(&lt;id|name&gt;):
    get:
      summary: Get Table Column
      description: Get TableColumn Retrieve the properties and relationships of tablecolumn
        object.
      operationId: GetTableColumn
      x-api-path-slug: workbookworksheetsltidnamegttablesltidnamegtcolumnsltidnamegt-get
      parameters:
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - Table
      - Column
    patch:
      summary: Update Tablecolumn
      description: Update tablecolumn Update the properties of tablecolumn object.
      operationId: UpdateTablecolumn
      x-api-path-slug: workbookworksheetsltidnamegttablesltidnamegtcolumnsltidnamegt-patch
      parameters:
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - Tablecolumn
  /workbook/tables(&lt;id|name&gt;)/columns(&lt;id|name&gt;)/HeaderRowRange:
    post:
      summary: Table Column Header Row Range
      description: 'TableColumn: HeaderRowRange Gets the range object associated with
        the header row of the column.'
      operationId: TableColumn:HeaderRowRange
      x-api-path-slug: workbooktablesltidnamegtcolumnsltidnamegtheaderrowrange-post
      parameters:
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - Table
      - Column
      - Header
      - Row
      - Range
  /workbook/worksheets(&lt;id|name&gt;)/tables(&lt;id|name&gt;)/columns(&lt;id|name&gt;)/HeaderRowRange:
    post:
      summary: Table Column Header Row Range
      description: 'TableColumn: HeaderRowRange Gets the range object associated with
        the header row of the column.'
      operationId: TableColumn:HeaderRowRange
      x-api-path-slug: workbookworksheetsltidnamegttablesltidnamegtcolumnsltidnamegtheaderrowrange-post
      parameters:
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - Table
      - Column
      - Header
      - Row
      - Range
  /workbook/tables(&lt;id|name&gt;)/columns(&lt;id|name&gt;)/Range:
    post:
      summary: Table Column Range
      description: 'TableColumn: Range Gets the range object associated with the entire
        column.'
      operationId: TableColumn:Range
      x-api-path-slug: workbooktablesltidnamegtcolumnsltidnamegtrange-post
      parameters:
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - Table
      - Column
      - Range
  /workbook/worksheets(&lt;id|name&gt;)/tables(&lt;id|name&gt;)/columns(&lt;id|name&gt;)/Range:
    post:
      summary: Table Column Range
      description: 'TableColumn: Range Gets the range object associated with the entire
        column.'
      operationId: TableColumn:Range
      x-api-path-slug: workbookworksheetsltidnamegttablesltidnamegtcolumnsltidnamegtrange-post
      parameters:
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - Table
      - Column
      - Range
  /workbook/tables(&lt;id|name&gt;)/columns(&lt;id|name&gt;)/TotalRowRange:
    post:
      summary: Table Column Total Row Range
      description: 'TableColumn: TotalRowRange Gets the range object associated with
        the totals row of the column.'
      operationId: TableColumn:TotalRowRange
      x-api-path-slug: workbooktablesltidnamegtcolumnsltidnamegttotalrowrange-post
      parameters:
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - Table
      - Column
      - Total
      - Row
      - Range
  /workbook/worksheets(&lt;id|name&gt;)/tables(&lt;id|name&gt;)/columns(&lt;id|name&gt;)/TotalRowRange:
    post:
      summary: Table Column Total Row Range
      description: 'TableColumn: TotalRowRange Gets the range object associated with
        the totals row of the column.'
      operationId: TableColumn:TotalRowRange
      x-api-path-slug: workbookworksheetsltidnamegttablesltidnamegtcolumnsltidnamegttotalrowrange-post
      parameters:
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - Table
      - Column
      - Total
      - Row
      - Range
  /workbook/tables(&lt;id|name&gt;)/columns/add:
    post:
      summary: Table Column Collection Add
      description: 'TableColumnCollection: add Adds a new column to the table.'
      operationId: TableColumnCollection:Add
      x-api-path-slug: workbooktablesltidnamegtcolumnsadd-post
      parameters:
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - Table
      - Column
      - Collection
  /workbook/worksheets(&lt;id|name&gt;)/tables(&lt;id|name&gt;)/columns/add:
    post:
      summary: Table Column Collection Add
      description: 'TableColumnCollection: add Adds a new column to the table.'
      operationId: TableColumnCollection:Add
      x-api-path-slug: workbookworksheetsltidnamegttablesltidnamegtcolumnsadd-post
      parameters:
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - Table
      - Column
      - Collection
  /workbook/tables(&lt;id|name&gt;)/columns/ItemAt:
    post:
      summary: Table Column Collection Item At
      description: 'TableColumnCollection: ItemAt Gets a column based on its position
        in the collection.'
      operationId: TableColumnCollection:ItemAt
      x-api-path-slug: workbooktablesltidnamegtcolumnsitemat-post
      parameters:
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - Table
      - Column
      - Collection
      - Item
      - At
  /workbook/worksheets(&lt;id|name&gt;)/tables(&lt;id|name&gt;)/columns/ItemAt:
    post:
      summary: Table Column Collection Item At
      description: 'TableColumnCollection: ItemAt Gets a column based on its position
        in the collection.'
      operationId: TableColumnCollection:ItemAt
      x-api-path-slug: workbookworksheetsltidnamegttablesltidnamegtcolumnsitemat-post
      parameters:
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - Table
      - Column
      - Collection
      - Item
      - At
  /workbook/tables(&lt;id|name&gt;)/rows(&lt;index&gt;)/delete:
    post:
      summary: Table Row Delete
      description: 'TableRow: delete Deletes the row from the table.'
      operationId: TableRow:Delete
      x-api-path-slug: workbooktablesltidnamegtrowsltindexgtdelete-post
      parameters:
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - Table
      - Row
  /workbook/worksheets(&lt;id|name&gt;)/tables(&lt;id|name&gt;)/rows(&lt;index&gt;)/delete:
    post:
      summary: Table Row Delete
      description: 'TableRow: delete Deletes the row from the table.'
      operationId: TableRow:Delete
      x-api-path-slug: workbookworksheetsltidnamegttablesltidnamegtrowsltindexgtdelete-post
      parameters:
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - Table
      - Row
  /workbook/tables(&lt;id|name&gt;)/rows(&lt;index&gt;):
    get:
      summary: Get Table Row
      description: Get TableRow Retrieve the properties and relationships of tablerow
        object.
      operationId: GetTableRow
      x-api-path-slug: workbooktablesltidnamegtrowsltindexgt-get
      parameters:
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - Table
      - Row
    patch:
      summary: Update Tablerow
      description: Update tablerow Update the properties of tablerow object.
      operationId: UpdateTablerow
      x-api-path-slug: workbooktablesltidnamegtrowsltindexgt-patch
      parameters:
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - Tablerow
  /workbook/worksheets(&lt;id|name&gt;)/tables(&lt;id|name&gt;)/rows(&lt;index&gt;):
    get:
      summary: Get Table Row
      description: Get TableRow Retrieve the properties and relationships of tablerow
        object.
      operationId: GetTableRow
      x-api-path-slug: workbookworksheetsltidnamegttablesltidnamegtrowsltindexgt-get
      parameters:
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - Table
      - Row
    patch:
      summary: Update Tablerow
      description: Update tablerow Update the properties of tablerow object.
      operationId: UpdateTablerow
      x-api-path-slug: workbookworksheetsltidnamegttablesltidnamegtrowsltindexgt-patch
      parameters:
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - Tablerow
  /workbook/tables(&lt;id|name&gt;)/rows(&lt;index&gt;)/Range:
    post:
      summary: Table Row Range
      description: 'TableRow: Range Returns the range object associated with the entire
        row.'
      operationId: TableRow:Range
      x-api-path-slug: workbooktablesltidnamegtrowsltindexgtrange-post
      parameters:
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - Table
      - Row
      - Range
  /workbook/worksheets(&lt;id|name&gt;)/tables(&lt;id|name&gt;)/rows(&lt;index&gt;)/Range:
    post:
      summary: Table Row Range
      description: 'TableRow: Range Returns the range object associated with the entire
        row.'
      operationId: TableRow:Range
      x-api-path-slug: workbookworksheetsltidnamegttablesltidnamegtrowsltindexgtrange-post
      parameters:
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - Table
      - Row
      - Range
  /workbook/tables(&lt;id|name&gt;)/rows/add:
    post:
      summary: Table Row Collection Add
      description: 'TableRowCollection: add Adds a new row to the table.'
      operationId: TableRowCollection:Add
      x-api-path-slug: workbooktablesltidnamegtrowsadd-post
      parameters:
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - Table
      - Row
      - Collection
  /workbook/worksheets(&lt;id|name&gt;)/tables(&lt;id|name&gt;)/rows/add:
    post:
      summary: Table Row Collection Add
      description: 'TableRowCollection: add Adds a new row to the table.'
      operationId: TableRowCollection:Add
      x-api-path-slug: workbookworksheetsltidnamegttablesltidnamegtrowsadd-post
      parameters:
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - Table
      - Row
      - Collection
  /workbook/tables(&lt;id|name&gt;)/rows/ItemAt:
    post:
      summary: Table Row Collection Item At
      description: 'TableRowCollection: ItemAt Gets a row based on its position in
        the collection.'
      operationId: TableRowCollection:ItemAt
      x-api-path-slug: workbooktablesltidnamegtrowsitemat-post
      parameters:
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - Table
      - Row
      - Collection
      - Item
      - At
  /workbook/worksheets(&lt;id|name&gt;)/tables(&lt;id|name&gt;)/rows/ItemAt:
    post:
      summary: Table Row Collection Item At
      description: 'TableRowCollection: ItemAt Gets a row based on its position in
        the collection.'
      operationId: TableRowCollection:ItemAt
      x-api-path-slug: workbookworksheetsltidnamegttablesltidnamegtrowsitemat-post
      parameters:
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - Table
      - Row
      - Collection
      - Item
      - At
  /workbook/tables(&lt;id|name&gt;)/sort/apply:
    post:
      summary: Table Sort Apply
      description: 'TableSort: apply Perform a sort operation.'
      operationId: TableSort:Apply
      x-api-path-slug: workbooktablesltidnamegtsortapply-post
      parameters:
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - Table
      - Sort
      - Apply
  /workbook/worksheets(&lt;id|name&gt;)/tables(&lt;id|name&gt;)/sort/apply:
    post:
      summary: Table Sort Apply
      description: 'TableSort: apply Perform a sort operation.'
      operationId: TableSort:Apply
      x-api-path-slug: workbookworksheetsltidnamegttablesltidnamegtsortapply-post
      parameters:
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - Table
      - Sort
      - Apply
  /workbook/tables(&lt;id|name&gt;)/sort/clear:
    post:
      summary: Table Sort Clear
      description: 'TableSort: clear Clears the sorting that is currently on the table.
        While this doesn''t modify the table''s ordering, it clears the state of the
        header buttons.'
      operationId: TableSort:Clear
      x-api-path-slug: workbooktablesltidnamegtsortclear-post
      parameters:
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - Table
      - Sort
      - Clear
  /workbook/worksheets(&lt;id|name&gt;)/tables(&lt;id|name&gt;)/sort/clear:
    post:
      summary: Table Sort Clear
      description: 'TableSort: clear Clears the sorting that is currently on the table.
        While this doesn''t modify the table''s ordering, it clears the state of the
        header buttons.'
      operationId: TableSort:Clear
      x-api-path-slug: workbookworksheetsltidnamegttablesltidnamegtsortclear-post
      parameters:
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - Table
      - Sort
      - Clear
  /workbook/tables(&lt;id|name&gt;)/sort:
    get:
      summary: Get Table Sort
      description: Get TableSort Retrieve the properties and relationships of tablesort
        object.
      operationId: GetTableSort
      x-api-path-slug: workbooktablesltidnamegtsort-get
      parameters:
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - Table
      - Sort
  /workbook/worksheets(&lt;id|name&gt;)/tables(&lt;id|name&gt;)/sort:
    get:
      summary: Get Table Sort
      description: Get TableSort Retrieve the properties and relationships of tablesort
        object.
      operationId: GetTableSort
      x-api-path-slug: workbookworksheetsltidnamegttablesltidnamegtsort-get
      parameters:
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - Table
      - Sort
  /workbook/tables(&lt;id|name&gt;)/sort/reapply:
    post:
      summary: Table Sort Reapply
      description: 'TableSort: reapply Reapplies the current sorting parameters to
        the table.'
      operationId: TableSort:Reapply
      x-api-path-slug: workbooktablesltidnamegtsortreapply-post
      parameters:
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - Table
      - Sort
      - Reapply
  /workbook/worksheets(&lt;id|name&gt;)/tables(&lt;id|name&gt;)/sort/reapply:
    post:
      summary: Table Sort Reapply
      description: 'TableSort: reapply Reapplies the current sorting parameters to
        the table.'
      operationId: TableSort:Reapply
      x-api-path-slug: workbookworksheetsltidnamegttablesltidnamegtsortreapply-post
      parameters:
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - Table
      - Sort
      - Reapply
  /workbook/tables/$/add:
    post:
      summary: Create Table
      description: Create Table Use this API to create a new Table.
      operationId: CreateTable
      x-api-path-slug: workbooktablesadd-post
      parameters:
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - Table
  /workbook/worksheets(&lt;id|name&gt;)/tables/$/add:
    post:
      summary: Create Table
      description: Create Table Use this API to create a new Table.
      operationId: CreateTable
      x-api-path-slug: workbookworksheetsltidnamegttablesadd-post
      parameters:
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - Table
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