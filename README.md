# js-bootstrap-tables
Bootstrap tables using vanilla javascript with built-in search, serial no., event-firing, colspan, rowspan, counters and much more...

# Optional Requirements
Require-js
Bootstrap

# How to use
let headRow = [{ text: `Name` }];

let dataRows = [
{text: `Pankaj`},
{text: `Ram`},
{text: `Tarun`}
];

createTable({ divId: `tableDiv`, tableId: `tableData`, headRow, dataRows, head2Row, footRow, functionArray });

# Properties
id
align
additionalClass
rowspan
colspan
text
filterText
