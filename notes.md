- 3 table elements
  - table
  - tr: table row, spans full width of table
    - each section of an email is a row
  - td: table cell AKA column data, each cell represents a column space in a row
    - tds represent content blocks (images, text, etc.)


PROCESS

1. Write scaffold
  - Write up doctype and header
  - Wrapping elements (body, center, and table simulating body (table, row, and cell))
  - Structure of email content
    - containing table
    - row-cell pair for each section of the email
2. Create blocks within scaffold, following design
3. 


- Each email section is a row in the email container table, which is in the one cell of the body table
- Use tables to subdivide content i.e. place a table within a cell of an email section row to further subdivide that row (both horizontally (inner table cells) or vertically (inner table rows))
- use table-based buttons, not button elements, b/c email clients generally strip button elements. clunky solution, but you don't want to lose your call to action
- set width of a whole section on outermost table
- set width of blocks within a section on inner tables
- outermost td, containing blocks: label with id of XXX-Container, where XXX describes the section