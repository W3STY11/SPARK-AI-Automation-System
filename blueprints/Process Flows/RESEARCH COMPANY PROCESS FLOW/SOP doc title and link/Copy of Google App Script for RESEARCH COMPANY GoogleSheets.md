`function onEdit(e) {`  
 `const sheet = e.source.getActiveSheet();`  
 `const editedRange = e.range;`  
 `const editedValue = e.value;`

 `// Customize: column number and sheet name`  
 `const CHECKBOX_COLUMN = 3; // Column C`  
 `const SHEET_NAME = "Sheet1"; // your sheet name`  
 `const WEBHOOK_URL = "COPY AND PASTE THE WEBHOOK HERE FROM MAKE.COM";`

 `// Only proceed if:`  
 `if (`  
   `sheet.getName() === SHEET_NAME &&`  
   `editedRange.getColumn() === CHECKBOX_COLUMN &&`  
   `editedValue === "TRUE"`  
 `) {`  
   `const row = editedRange.getRow();`  
   `const rowData = sheet.getRange(row, 1, 1, sheet.getLastColumn()).getValues()[0];`

   `const payload = {`  
     `rowNumber: row,`  
     `values: rowData`  
   `};`

   `const options = {`  
     `method: "post",`  
     `contentType: "application/json",`  
     `payload: JSON.stringify(payload)`  
   `};`

   `UrlFetchApp.fetch(WEBHOOK_URL, options);`  
 `}`  
`}`